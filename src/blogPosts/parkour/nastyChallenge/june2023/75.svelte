<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={75}
    date='June 16, 2023'
    weighIn={221.6}
    underGoal={false}
    goalDelta={1050}
    mainMealsCount={3}
    mealsList={[
        "McDonald's iced latte w/ cottage cheese & kiwi",
        "Trek Cafe - salad w/ mozz & chicken",
        "Culver's - double PBB&J butterburger w/ cheese curds"
    ]}
    snacksList={[
        "Cottage cheese",
    ]}
    didPT={true}
    exerciseSummary='Mixed bag'
    exerciseList={[
        'Morning bike ride to YMCA & back',
        '15-minute swim',
        'Rock climbing sesh'
    ]}
/>