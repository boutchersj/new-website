<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={33}
    date='May 5, 2023'
    weighIn={228}
    underGoal={false}
    goalDelta={300}
    mainMealsCount={3}
    mealsList={[
        "Salami & Provolone on a Pretzel Bun",
        "Trek Snack Wrap",
        "Buck & Honey's - Seafood Enchiladas, Rice & Beans"
    ]}
    snacksList={[
        "A margarita with dinner",
    ]}
    didPT={true}
    exerciseSummary="Morning cardio"
    exerciseList={[
        "Mile run",
        "Bike ride"
    ]}
/>