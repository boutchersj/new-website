<script>
    import ExerciseLog from '$lib/ExerciseLog.svelte';
</script>

<ExerciseLog
    dayNum={148}
    date='August 28, 2023'
    weighIn={216.4}
    didPT={false}
    exerciseSummary='Bike to work & back'
    exerciseList={[
        '17.71-mile bike ride to work - 1h 18min',
        ''
    ]}
    fruitCups={2}
    veggiesCups={4}
    flax={true}
    lGlutamine={true}
    fishOil={true}
>
    <div slot='extraContent'>
        <h3 class='text-2xl my-5'>4th Bike Ride to Work & Back</h3>
        <p>
            something cool
        </p>
        <br />
        <img src='/4th_ride_to_work.png' alt='My 4th bike ride to & from work - Strava recording details' />
    </div>
</ExerciseLog>