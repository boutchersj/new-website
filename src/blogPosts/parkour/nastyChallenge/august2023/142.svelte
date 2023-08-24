<script>
    import ExerciseLog from '$lib/ExerciseLog.svelte';
</script>

<ExerciseLog
    dayNum={142}
    date='August 22, 2023'
    weighIn={216.8}
    didPT={true}
    exerciseSummary=''
    exerciseList={[
        '3x3 bodyweight pull-ups',
        'Bike ride to & from work'
    ]}
    fruitCups={2}
    veggiesCups={4}
    flax={true}
    lGlutamine={true}
    fishOil={true}
>
    <div slot='extraContent'>
        <h3 class='text-2xl my-5'>3rd Bike Ride to Work & Back</h3>
        <p>
            This ride wasn't as bad! I took the most direct route this time, down Hwy 19 and 
            through Main St. to the other side of Sun Prairie where I live. It's the busiest route but 
            it was shorter by 2 miles, apparently. I didn't realize how unbikeable Main St. was until now, 
            but at least the sidewalk is clear 90% of the time so I can use that instead of the street. I will 
            be taking the country roads next time.
        </p>
        <br />
        <img class='w-[50%]' src='/3rd_ride_to_work.png' alt='My 3rd bike ride to & from work - Strava recording details' />
    </div>
</ExerciseLog>