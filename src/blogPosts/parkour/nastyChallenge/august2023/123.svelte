<script>
    import ExerciseLog from '$lib/ExerciseLog.svelte';
</script>

<ExerciseLog
    dayNum={123}
    date='August 3, 2023'
    weighIn={215.8}
    didPT={false}
    exerciseSummary='Mountain Biking?'
    exerciseList={[
        'Did I ride a bike today?'
    ]}
    fruitCups={2}
    veggiesCups={4}
    flax={true}
    lGlutamine={true}
    fishOil={true}
/>