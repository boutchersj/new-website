<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={73}
    date='June 14, 2023'
    weighIn={221.8}
    underGoal={false}
    goalDelta={650}
    mainMealsCount={3}
    mealsList={[
        "McDonald's - iced sugar-free vanilla coffee + steak, egg & cheese biscuit",
        "Trek Cafe - PB&J + 2 apples",
        "EveryPlate - garlicky roasted pepper penne w/ toasted panko & parmesan"
    ]}
    snacksList={[
        "Lean Body - cookies & cream protein shake",
        "Quest - peanut butter protein cookie"
    ]}
    didPT={false}
    exerciseSummary='Crossfit class - 6 rounds in 20 minutes'
    exerciseList={[
        '6 x 5 [band-assisted] pull-ups',
        '6 x 10 push-ups',
        '6 x 15 squats'
    ]}
/>