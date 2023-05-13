<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={40}
    date='May 12, 2023'
    weighIn={228.8}
    underGoal={false}
    goalDelta={950}
    mainMealsCount={2}
    mealsList={[
        "Buttered whole wheat toast, cottage cheese & an apple",
        "Mooyah - Double diablo burger w/o mayo"
    ]}
    snacksList={[
        "Buttered whole wheat toast",
        "Peanut butter toast",
        "Buttered tortilla",
    ]}
    didPT={true}
    exerciseSummary="Mixed bag"
    exerciseList={[
        "10-minute bike ride",
        "Mile run",
        "Quadrupedal movement",
        "Band-assisted pull-ups",
    ]}
/>