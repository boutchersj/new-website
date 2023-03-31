<script lang='ts'>
    export let title: string;
    export let gif: string='';
    export let gifAlt: string='';
    export let line1: string;
    export let year: number;
    export let line2: string;
    export let emoji: string;
    export let accentColor: string;

    const containerStyles: string = `flex flex-col text-lg md:text-2xl justify-center items-center h-full bg-gradient-to-b from-white ${accentColor} to-white p-10`
</script>

<div class={containerStyles}>
    <h3 class='text-2xl md:text-4xl w-full text-center my-5'>{title}</h3>
    {#if gif && gifAlt}
        <img class='h-full border border-white rounded-xl border-opacity-0 my-10' src={gif} alt={gifAlt} />
    {/if}
    <p class='w-full text-center'>{line1}</p>
    <p class='w-full text-md md:text-xl text-center py-5'>- since {year} -</p>
    <p class='w-full text-center'>{line2}</p>
    <div class='w-full flex justify-center py-10'>
        <p class='w-[25%] text-center scale-[2]'>{emoji}</p>
    </div>
</div>