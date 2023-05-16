<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={42}
    date='May 14, 2023'
    weighIn={225.8}
    underGoal={false}
    goalDelta={300}
    mainMealsCount={3}
    mealsList={[
        "Buttered homemade pretzel & swiss bread from the farmer's market",
        "Sarku Japan - spicy bourbon chicken & fried rice w/ steamed veggies",
        "EveryPlate - crispy southern chicken sandwich w/ pickled jalapeños & roasted potato wedges"
    ]}
    snacksList={[
        "1 cup of 2% cottage cheese",
    ]}
    didPT={true}
    exerciseSummary="Cardio"
    exerciseList={[
        "10-minute bike ride",
        "2-mile run"
    ]}
/>