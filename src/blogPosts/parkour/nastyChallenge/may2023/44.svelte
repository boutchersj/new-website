<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={44}
    date='May 16, 2023'
    weighIn={227.8}
    underGoal={false}
    goalDelta={300}
    mainMealsCount={3}
    mealsList={[
        "Eggs, whole wheat toast, and cottage cheese",
        "Poblano pepper & onion cheese fajitas",
        "EveryPlate - creamy garlic riggies with chicken plus tomato & lemon"
    ]}
    snacksList={[
        "Buttered whole wheat toast",
    ]}
    didPT={true}
    exerciseSummary="Power hour"
    exerciseList={[
        "10-minute bike ride",
        "Mile run"
    ]}
/>