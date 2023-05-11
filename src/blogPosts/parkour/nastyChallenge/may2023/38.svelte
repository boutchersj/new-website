<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={38}
    date='May 10, 2023'
    weighIn={226.8}
    underGoal={false}
    goalDelta={1300}
    mainMealsCount={3}
    mealsList={[
        "Starbucks - kale & portobello mushroom egg bites w/ a cappuccino",
        "Stir-fry veggies with hot [sugar-free] honey mustard, chicken, & avocado",
        "EveryPlate - Farmer's Market Linguine"
    ]}
    snacksList={[
        "Dave's Killer Bread buttered everything bagel-seasoned bread",
        "a few cups of 2% milk",
        "a snack-sized bag of BBQ potato chips"
    ]}
    didPT={false}
    exerciseSummary="Mixed bag"
    exerciseList={[
        "10-minute bike ride",
        "Mile run",
        "Rock climbing"
    ]}
/>