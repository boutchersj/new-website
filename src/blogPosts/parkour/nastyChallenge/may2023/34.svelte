<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={34}
    date='May 6, 2023'
    weighIn={228.4}
    underGoal={false}
    goalDelta={700}
    mainMealsCount={2}
    mealsList={[
        "Beans & Cream - Ham & Cheese Croissant w/ a latte",
        "Domino's - 1/2 a large sausage & pineapple pizza"
    ]}
    snacksList={[
        "buttered homemade 3-cheese pesto bread",
    ]}
    didPT={true}
    exerciseSummary="Evening cardio"
    exerciseList={[
        "45-minute bike ride",
    ]}
/>