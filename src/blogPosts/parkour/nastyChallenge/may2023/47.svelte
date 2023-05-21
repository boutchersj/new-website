<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={47}
    date='May 19, 2023'
    weighIn={225}
    underGoal={false}
    goalDelta={1350}
    mainMealsCount={3}
    mealsList={[
        "Chiptole turkey burger",
        "2 hot dogs & Cheddar sour cream chips",
        "EveryPlate - Tomato & Pork Sausage Linguine with Garlic Bread",
    ]}
    snacksList={[
        "Cottage cheese",
        "1/2 a cup of milk",
        "Joyride - Sugar-free gummies",
        "Cheddar Bay Biscuits",
    ]}
    didPT={false}
/>