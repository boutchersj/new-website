<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={36}
    date='May 8, 2023'
    weighIn={229.4}
    underGoal={true}
    goalDelta={200}
    mainMealsCount={2}
    mealsList={[
        "McDonald's - steak egg & cheese bagel w/ a plain iced latte",
        "EveryPlate - cream of mushroom soup"
    ]}
    snacksList={[
        "a salad I made at Trek's salad bar"
    ]}
    didPT={false}
    exerciseSummary="Parkour conditioning"
    exerciseList={[
        "quadrupedal movement",
        "monkey bars",
        "push-ups"
    ]}
/>