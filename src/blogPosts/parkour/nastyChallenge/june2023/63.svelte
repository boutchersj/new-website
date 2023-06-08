<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={63}
    date='June 4, 2023'
    weighIn={223.2}
    underGoal={false}
    goalDelta={1500}
    mainMealsCount={3}
    mealsList={[
        "McDonald's - sausage burrito + sourdough bread",
        "Organic beef & cheese quesadilla w/ peppers & onions + nonfat greek yogurt/chipotle powder crema",
        "EveryPlate - salisbury steaks w/ herb mashed potatoes"
    ]}
    snacksList={[
        "String cheese",
        "Garlic knots",
        "Keto cookie dough ice cream"
    ]}
    didPT={true}
    exerciseSummary='Swimming & Squats'
    exerciseList={[
        'Swimming at the outdoor pool',
        "Kettlebell squats"
    ]}
/>