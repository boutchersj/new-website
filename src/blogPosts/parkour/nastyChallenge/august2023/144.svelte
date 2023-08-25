<script>
    import ExerciseLog from '$lib/ExerciseLog.svelte';
</script>

<ExerciseLog
    dayNum={144}
    date='August 24, 2023'
    weighIn={216.6}
    didPT={false}
    exerciseSummary='Morning @ the Y'
    exerciseList={[
        'eGym circuit',
        '1/2-mile treadmill run @ 6 mph'
    ]}
    fruitCups={2}
    veggiesCups={0}
    flax={true}
    lGlutamine={true}
    fishOil={true}
>
    <div slot='extraContent'>
        <h3 class='text-2xl my-5'>InBody Measurement</h3>
        <p>
            I'm excited to announce that I've lost another 1.2% of my body fat! The downside is 
            I've been consistently losing about 2 lbs. of muscle for every 10 lbs. of body fat I lose. 
            According to my nutritionist, my rate of muscle loss isn't alarming by any means. 
            I just need to eat more protein!
        </p>
        <br />
        <img class='w-full' src='/In_Body_8_24_23.jpeg' alt='InBody scan - full results - August 24, 2023 - highlight: loss of 1.2% body fat' />
    </div>
</ExerciseLog>