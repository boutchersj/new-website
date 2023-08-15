<script>
    import ExerciseLog from '$lib/ExerciseLog.svelte';
</script>

<ExerciseLog
    dayNum={133}
    date='August 13, 2023'
    weighIn={220.2}
    didPT={false}
    exerciseSummary='Charity bike ride + morning jog'
    exerciseList={[
        '1/2-mile run',
        '50k (31-mile) bike ride',
    ]}
    fruitCups={0}
    veggiesCups={0}
    flax={false}
    lGlutamine={true}
    fishOil={true}
>
    <div slot='extraContent'>
        <h3 class='text-2xl my-5'>My First 50K Bike Ride</h3>
        <p>
            I was shocked I was able to complete this! Earlier in the week on Tuesday, I had biked 36 miles round trip 
            to & from the office in Waterloo. That was the most miles I'd completed in a day or a week at that point. So, 
            adding another 31 on top of that for the week, I was excited about what turned out to be possible for me. That 
            said, I don't think I'll be biking to work more then 2x per week until my body gets more used to it.
        </p>
        <br />
        <img class='w-[50%]' src='/my_first_50k.jpeg' alt='My first 50k bike ride - Strava recording details' />
    </div>
</ExerciseLog>