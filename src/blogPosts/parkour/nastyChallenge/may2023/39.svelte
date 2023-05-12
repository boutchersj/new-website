<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={39}
    date='May 11, 2023'
    weighIn={227.4}
    underGoal={false}
    goalDelta={500}
    mainMealsCount={3}
    mealsList={[
        "Sweet potato zucchini pancakes w/ mixed berries",
        "Pretzel bun swiss cheeseburger & turkey wrap",
        "Culver's - double deluxe cheeseburger w/o mayo"
    ]}
    snacksList={[
        "Starbucks - peach green tea lemonade",
        "Starbucks - egg white, turkey bacon & white cheddar sandwich"
    ]}
    didPT={false}
    exerciseSummary="Trail riding"
    exerciseList={[
        "Mountain biking on the Trek trails",
    ]}
/>