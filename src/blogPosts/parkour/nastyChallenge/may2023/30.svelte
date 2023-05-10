<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={30}
    date='May 2, 2023'
    weighIn={229.6}
    underGoal={true}
    goalDelta={300}
    mainMealsCount={2}
    mealsList={[
        "A salad I made at Trek's salad bar",
        "EveryPlate - cheesy tex-mex cavatappi with a kick"
    ]}
    snacksList={[
        "McDonald's - double quarter cheese deluxe",
    ]}
    didPT={true}
    exerciseSummary="A mixed bag"
    exerciseList={[
        "yoga",
        "core workout - bodyweight & some weighted exercises"
    ]}
/>