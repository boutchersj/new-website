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
            
        </p>
        <br />
        <img class='w-[50%]' src='/.png' alt='' />
    </div>
</ExerciseLog>