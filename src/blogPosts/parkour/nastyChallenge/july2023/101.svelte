<script>
    import ExerciseLog from '$lib/ExerciseLog.svelte';
</script>

<ExerciseLog
    dayNum={101}
    date='July 12, 2023'
    weighIn={217.2}
    didPT={true}
    exerciseSummary='Afternoon at the Y'
    exerciseList={[
        'Bike ride to YMCA & back',
        'eGym circuit',
    ]}
    fruitCups={2}
    veggiesCups={4}
    flax={true}
    lGlutamine={true}
    fishOil={true}
/>