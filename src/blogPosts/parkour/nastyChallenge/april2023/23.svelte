<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={23}
    date='April 25, 2023'
    weighIn={228.4}
    underGoal={false}
    goalDelta={750}
    mainMealsCount={3}
    mealsList={[
        "McDonald's - bacon egg & cheese biscuit",
        "Spinach, Feta, Olive, & Arugula flatbread pizza",
        "EveryPlate - BBQ bacon & onion flatbreads w/ mozzarella & pickled jalapeño"
    ]}
    snacksList={[
        "Cheese & salsa tortilla wraps",
    ]}
    didPT={true}
    exerciseSummary={"\"Power Hour\""}
    exerciseList={[
        "10-minute bike ride",
        "Mile run"
    ]}
/>