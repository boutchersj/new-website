<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={57}
    date='May 29, 2023'
    weighIn={223.2}
    underGoal={false}
    goalDelta={650}
    mainMealsCount={2}
    mealsList={[
        "McDonald's - 20-piece chicken nuggets w/ sriracha mayo",
        "Noodles & Company - 3-cheese tortelloni pesto w/ grilled chicken"
    ]}
    snacksList={[
        'String cheese',
        'Hummus & carrots'
    ]}
    didPT={true}
    exerciseSummary='Summer fun'
    exerciseList={[
        'Biking to get smoothies (sugar-free) at Bambu and some stuff at Target',
        'Flying kites in the park',
        'Attempting to run a mile, only got .13 miles before my knee flared up'
    ]}
    otherThoughts={`
        No clue why I went up 3 pounds and down 3 pounds again within 2 days. The human body is weird. Maybe 
        I should stop guessing and just keep doing what I'm doing until it starts to reverse my progress.
    `}
/>