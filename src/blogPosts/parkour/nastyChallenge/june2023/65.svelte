<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={65}
    date='June 6, 2023'
    weighIn={222.8}
    underGoal={false}
    goalDelta={250}
    mainMealsCount={2}
    mealsList={[
        "Beef, cheese, pepper & onion quesadilla (corn tortilla) w/ Pace hot salsa",
        "EveryPlate - tunisian-spiced chicken w/ couscous & roasted carrots"
    ]}
    snacksList={[
        "String cheese",
        "Whole wheat sourdough bread w/ organic butter",
        "Culver's - cheese curds"
    ]}
    didPT={false}
/>