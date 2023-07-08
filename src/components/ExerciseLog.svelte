<script lang='ts'>
    export let dayNum: number;
    export let date: string;
    export let weighIn: number;
    export let didPT: boolean;
    export let exerciseSummary: string='';
    export let exerciseList: string[]=[];
    export let veggiesCups: number=0;
    export let fruitCups: number=0;
    export let flax: boolean=false;
    export let lGlutamine: boolean=false;
    export let fishOil: boolean=false;
    export let otherThoughts: string='';
</script>

<section class='my-10 w-[90%] border p-5 rounded-xl md:w-[50%]'>
    <div class='w-full text-3xl lg:text-3xl text-red-500 mb-5 flex flex-col justify-evenly items-center text-center'>
        <h2 id={`day${dayNum}`}>Day {dayNum}</h2>
    </div>
    <p class='flex flex-col w-full items-center justify-between text-sm text-red-500 mb-5'>
        {date}
    </p>
    <p class='flex flex-col w-full items-center justify-between text-sm text-red-500 mb-5'>
        Weigh-in: {weighIn} lbs.
    </p>

    <br />

    <h3 class='font-bold'>PT (Physical Therapy)</h3>
    <br />
    <p>{didPT ? 'Yes' : 'No'}</p>

    <br />

    <h3 class='font-bold'>Exercise</h3>
    <br />
    <p>{exerciseSummary ? `${exerciseSummary}:` : 'No exercise today.'}</p>
    <ul class='list-disc ml-10 my-3'>
        {#each exerciseList as exercise}
            <li>{exercise}</li>
        {/each}
    </ul>

    <h3 class='font-bold'>Food</h3>

    <br />
    {#if fruitCups == 0}
        <s><h3>Cups of Fruit</h3></s>
    {:else}
        <span>Cups of Fruit</span>
    {/if}
    {#each {length: fruitCups} as _, i}
        <span>🍓</span>
    {/each}
    <br />
    <br />


    {#if veggiesCups == 0}
        <s><h3>Cups of Non-Starchy Veggies</h3></s>
    {:else}
        <span>Cups of Non-Starchy Veggies</span>
    {/if}
    {#each {length: veggiesCups} as _, i}
        <span>🥕</span>
    {/each}
    <br />
    <br />

    {#if dayNum >= 96}
        <h3 class='font-bold'>Supplements</h3>
        <br />

        {#if flax}
            <h3>✅ 1 tbsp. ground flax seed</h3>
        {:else}
            <s><h3>1 tbsp. ground flax seed</h3></s>
        {/if}
        <br />

        {#if lGlutamine}
            <h3>✅ L-Glutamine</h3>
        {:else}
            <s><h3>L-Glutamine supplement</h3></s>
        {/if}
        <br />

        {#if fishOil}
            <h3>✅ Fish Oil</h3>
        {:else}
            <s><h3>Fish Oil supplement</h3></s>
        {/if}
    {/if}

    {#if otherThoughts}
        <br />
        <h3>Other Thoughts</h3>
        <br />
        <p>{otherThoughts}</p>
        <br />
    {/if}

    <slot name='extraContent' />

    <br />

    <a class='text-sm bg-[#92DCE5] text-black p-2' href='#month-header'>Back to Top</a>
</section>