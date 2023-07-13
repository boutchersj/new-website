<script>
    import ExerciseLog from '$lib/ExerciseLog.svelte';
</script>

<ExerciseLog
    dayNum={100}
    date='July 11, 2023'
    weighIn={218.6}
    didPT={false}
    exerciseSummary='Morning at the Y'
    exerciseList={[
        'Bike ride to YMCA & back',
        'eGym - abs - 1 set eccentric & concentric',
        '250-yard swim'
    ]}
    fruitCups={2}
    veggiesCups={4}
    flax={true}
    lGlutamine={true}
    fishOil={true}
/>