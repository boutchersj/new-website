<script>
    import ExerciseLog from '$lib/ExerciseLog.svelte';
</script>

<ExerciseLog
    dayNum={80}
    date='June 21, 2023'
    weighIn={223.2}
    didPT={true}
    exerciseSummary='Morning cardio'
    exerciseList={[
        'Morning bike ride to YMCA & back',
        '15-minute swim (500 yds)',
        'Rock climbing sesh'
    ]}
    fruitCups={2}
    veggiesCups={4}
/>