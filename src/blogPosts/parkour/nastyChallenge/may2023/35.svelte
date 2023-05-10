<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={35}
    date='May 7, 2023'
    weighIn={229.8}
    underGoal={false}
    goalDelta={900}
    mainMealsCount={2}
    mealsList={[
        "Hot honey mustard chicken & veggie stir fry",
        "Culver's - Double Deluxe Burger w/ onion rings"
    ]}
    snacksList={[
        "buttered homemade 3-cheese pesto bread",
    ]}
    didPT={false}
/>