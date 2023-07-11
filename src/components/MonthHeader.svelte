<script lang='ts'>
    import DayJumper from '$lib/DayJumper.svelte'
    export let month: string;
    export let year: number;
    export let startDay: (number|undefined);
    export let currentMonth: (boolean|undefined);
    export let endDay: (number|undefined)=undefined;
</script>


<h1 id='month-header' class='w-full flex text-lg md:text-2xl justify-center items-center bg-red-500 p-10'>
    <span class='p-7 rounded-xl bg-black flex flex-col justify-evenly items-center'>
        <p class='text-red-500'>#NASTY Challenge</p>
        <p class='font-bold'>{month} {year}</p>
        <DayJumper startDay={startDay} currentMonth={currentMonth} endDay={endDay} />
        <a class='text-sm bg-[#92DCE5] text-black p-2' href='/blog'>Back to Blog</a>
    </span>
</h1>