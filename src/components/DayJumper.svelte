<script lang='ts'>
    // By default, this will create a range from April 3, 2023, to the current day of the challenge
    const challengeStartDate: Date = new Date('04/03/2023');
    const today: Date = new Date();
    const daysSinceStart: number = Math.ceil((today.getTime() - challengeStartDate.getTime()) / (1000 * 3600 * 24))
    export let startDay: number = 1;
    export let endDay: number = daysSinceStart;
</script>

<div id='jumpToDay' class='flex my-5 items-center justify-center w-full'>
    <a 
        class='flex justify-center items-center mx-3 p-3 bg-green-500 border border-black text-black my rounded'
        href={`#day${endDay}`}
    >
            Jump
    </a>
    <p>to day</p>
    <input
        class='text-black mx-3 w-14 h-14 text-center text-lg'
        type='number'
        value={endDay}
        min={startDay}
        max={endDay}
    />
</div>