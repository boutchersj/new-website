<script>
    import ExerciseLog from '$lib/ExerciseLog.svelte';
</script>

<ExerciseLog
    dayNum={137}
    date='August 17, 2023'
    weighIn={217}
    didPT={true}
    exerciseSummary='2nd bike ride to work'
    exerciseList={[
        '16.95-mile ride to work',
        '16.63-mile ride home'
    ]}
    fruitCups={2}
    veggiesCups={4}
    flax={true}
    lGlutamine={true}
    fishOil={true}
>
    <div slot='extraContent'>
        <h3 class='text-2xl my-5'>2nd Bike Ride to Work & Back</h3>
        <p>
            The headwinds on the way back were pretty rough! I went down Highway 19 on the 
            return trip, which was a first for me. I didn't care for all the traffic! I'll probably 
            take the country roads next time, because taking 19 means encountering city roads either way.
        </p>
        <br />
        <img class='w-[50%]' src='/2nd_ride_to_work.jpeg' alt='My 2nd bike ride to & from work - Strava recording details' />
    </div>
</ExerciseLog>