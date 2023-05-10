<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={27}
    date='April 29, 2023'
    weighIn={230}
    underGoal={false}
    goalDelta={550}
    mainMealsCount={3}
    mealsList={[
        "Dave's Killer Bread whole wheat peanut butter toast",
        "Panda Express - plate w/ super greens, sizzling shrimp & orange chicken",
        "Drafthaus buffalo chicken pizza"
    ]}
    snacksList={[
        "Dave's Killer Bread buttered whole wheat toast",
    ]}
    didPT={false}
/>