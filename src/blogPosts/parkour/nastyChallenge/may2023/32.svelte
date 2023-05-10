<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={32}
    date='May 4, 2023'
    weighIn={229.6}
    underGoal={true}
    goalDelta={100}
    mainMealsCount={3}
    mealsList={[
        "Prosciutto & cheese wrap",
        "A salad I made at Trek's salad bar",
        "EveryPlate - kale & sausage soup"
    ]}
    snacksList={[
        "Chips",
        "Cottage cheese",
        "1 buttered tortilla"
    ]}
    didPT={true}
    exerciseSummary="Mixed bag"
    exerciseList={[
        "bike ride",
        "mile run",
        "upper body workout"
    ]}
/>