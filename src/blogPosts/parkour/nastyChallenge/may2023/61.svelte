<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={61}
    date='June 2, 2023'
    weighIn={222}
    underGoal={false}
    goalDelta={750}
    mainMealsCount={3}
    mealsList={[
        "McDonald's - sausage burrito w/ sugar-free vanilla iced latte",
        "Chipotle - chicken al pastor bowl",
        "EveryPlate - bacon & roasted tomato linguine"
    ]}
    snacksList={[
        "Tid Bits (low-sugar brand) - citrus gummies",
        "Alani Nu (low-sugar brand) - smoothie gummies",
        "Body Armor - Peach Mango Lyte (no added sugar)",
        "String cheese",
        "Chipotle - tortilla chips w/ salsa verde"
    ]}
    didPT={false}
    exerciseSummary='Barefoot training'
    exerciseList={[
        '1-mile jog, half of it barefoot',
        'Barefooot bear crawling, ~0.2 miles'
    ]}
/>