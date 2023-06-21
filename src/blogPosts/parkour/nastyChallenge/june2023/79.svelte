<script>
    import ExerciseLog from '$lib/ExerciseLog.svelte';
</script>

<ExerciseLog
    dayNum={79}
    date='June 20, 2023'
    weighIn={220.6}
    didPT={true}
    exerciseSummary='Mixed bag'
    exerciseList={[
        'Afternoon bike ride to YMCA & back',
        '15-minute swim',
        'Weightlifting - bench press, incline bench press, pull-ups'
    ]}
    fruitCups={1}
    veggiesCups={4}
    otherThoughts={`
        My nutritionist & I agreed that it'd more productive to continue tracking food, but to reduce the granularity if 
        I think it's bothersome to track in MyFitnessPal. So, I've added a feature to the new blog post format so I can track the 
        number of cups of fruits & non-starchy veggies using emojis.
    `}
/>