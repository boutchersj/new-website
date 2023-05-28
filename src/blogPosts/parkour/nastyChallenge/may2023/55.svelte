<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={55}
    date='May 27, 2023'
    weighIn={223.4}
    underGoal={false}
    goalDelta={850}
    mainMealsCount={3}
    mealsList={[
        "Farmer's market - steak tacos & vanilla cold brew",
        "Bartaco - 3 tacos & fresh pineapple w/ chili seasoning",
        "EveryPlate - black bean stew"
    ]}
    snacksList={[
        "Farmer's market - buttered pepperoni twist bread",
    ]}
    didPT={false}
/>