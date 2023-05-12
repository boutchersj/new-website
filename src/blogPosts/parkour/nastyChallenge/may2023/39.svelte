<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={39}
    date='May 11, 2023'
    weighIn={227.4}
    underGoal={false}
    goalDelta={800}
    mainMealsCount={4}
    mealsList={[
        "Sweet potato zucchini pancakes w/ mixed berries",
        "Turkey wrap & BBQ brisket pizza slice",
        "Pretzel bun swiss cheeseburger",
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