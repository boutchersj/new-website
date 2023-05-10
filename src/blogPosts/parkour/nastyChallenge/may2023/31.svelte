<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={31}
    date='May 3, 2023'
    weighIn={230}
    underGoal={false}
    goalDelta={300}
    mainMealsCount={2}
    mealsList={[
        "Panera - chipotle chicken avocado melt w/ plain cold brew & a fruit cup",
        "EveryPlate - sweet potato & onion tacos"
    ]}
    didPT={false}
/>
