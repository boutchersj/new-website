<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={17}
    date='April 19, 2023'
    weighIn={230.6}
    underGoal={false}
    goalDelta={500}
    mainMealsCount={3}
    mealsList={[
        "Rxbar, Lean Body protein shake, and beef & cheese sticks",
        "Coconut curry & rice",
        "EveryPlate - BBQ chicken with cheddar potatoes"
    ]}
    snacksList={[
        "Budweiser appetizers - beer-battered pickles",
    ]}
    didPT={true}
/>