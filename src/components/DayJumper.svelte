<script lang='ts'>
    // By default, this will create a range from April 3, 2023, to the current day of the challenge
    const challengeStartDate: Date = new Date('04/03/2023');
    const today: Date = new Date();
    const daysSinceStart: number = Math.ceil((today.getTime() - challengeStartDate.getTime()) / (1000 * 3600 * 24))
    export let startDay: number = 1;
    export let currentMonth: boolean = false;
    export let endDay: number = currentMonth ? (daysSinceStart - 1) : daysSinceStart;
    let specifiedDay: number = endDay
    
    function handleChange(event: any) {
        const { value } = event.target as HTMLInputElement;
        specifiedDay = Number(value);
    }
</script>

<div id='jumpToDay' class='flex my-5 items-center justify-center w-full'>
    <a 
        class='flex justify-center items-center mx-3 p-3 bg-[#92DCE5] border border-black text-black my rounded'
        href={`#day${specifiedDay}`}
    >
            Jump
    </a>
    <p>to day</p>
    <input
        id='dayPicker'
        class='text-black mx-3 w-14 h-14 text-center text-lg'
        type='number'
        pattern="\d*"
        value={endDay}
        min={startDay}
        max={endDay}
        on:change={handleChange}
    />
</div>