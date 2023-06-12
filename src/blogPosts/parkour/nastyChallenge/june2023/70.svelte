<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={70}
    date='June 11, 2023'
    weighIn={225}
    underGoal={false}
    goalDelta={1000}
    mainMealsCount={3}
    mealsList={[
        "Starbucks - Plain iced latte + double smoked bacon sandwich",
        "EveryPlate - Mushroom quesadillas",
        "EveryPlate - Harissa-roasted chickpea bowls"
    ]}
    snacksList={[
        "Pillsbury crescent rolls",
        "Buttered whole-grain rye sourdough bread",
    ]}
    didPT={false}
/>