<script lang='ts'>
    export let dayNum: number;
    export let date: string;
    export let weighIn: number;
    export let underGoal: boolean;
    export let goalDelta: number;
    export let mainMealsCount: number;
    export let mealsList: string[];
    export let snacksList: string[]=[];
    export let didPT: boolean=true;
    export let exerciseSummary: string='';
    export let exerciseList: string[]=[];
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

    <h3 class='font-bold'>Meals</h3>
    <br />
    <p>{underGoal ? 'Under' : 'Over'} calorie goal by {goalDelta}.</p>
    <br />
    <p>{mainMealsCount} main meals:</p>
    <ul class='list-disc ml-10 my-3'>
        {#each mealsList as meal}
            <li>
                {meal}
            </li>
        {/each}
    </ul>

    <br />

    <h3 class='font-bold'>Snacks</h3>
    {#if snacksList.length > 0}
        <ul class='list-disc ml-10 my-3'>
            {#each snacksList as snack}
                <li>{snack}</li>
            {/each}
        </ul>
    {:else}
        <br />
        <p>No snacks today.</p>
    {/if}
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