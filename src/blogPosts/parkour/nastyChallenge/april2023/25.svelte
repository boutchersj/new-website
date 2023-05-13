<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={25}
    date='April 27, 2023'
    weighIn={229}
    underGoal={false}
    goalDelta={500}
    mainMealsCount={3}
    mealsList={[
        "Cheese & salsa tortilla wraps w/ 2% milk",
        "1 slice each of mac n cheese & taco pizzas",
        "EveryPlate - roasted zucchini, bell pepper & tomato penne"
    ]}
    snacksList={[
        "Culver's - 1/2 a large order of cheese curds",
    ]}
    didPT={false}
    otherThoughts="Been fighting a cold this entire week. Ugh. The worst of it seems to be done, though."
/>