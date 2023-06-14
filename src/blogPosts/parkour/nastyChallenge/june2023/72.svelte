<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={72}
    date='June 13, 2023'
    weighIn={224.6}
    underGoal={true}
    goalDelta={500}
    mainMealsCount={2}
    mealsList={[
        "Trek Cafe - salad",
        "EveryPlate - kung pao beef bowls"
    ]}
    snacksList={[
        "Greek yogurt w/ strawberries & honey",
        "Toppers - tacostix w/ sriracha mayo dipping sauce"
    ]}
    didPT={true}
    exerciseSummary='Morning cardio'
    exerciseList={[
        'Bike to the Sun Prairie YMCA & back',
        '15-minute lap swim'
    ]}
/>