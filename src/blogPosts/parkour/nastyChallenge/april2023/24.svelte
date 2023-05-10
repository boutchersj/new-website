<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={24}
    date='April 26, 2023'
    weighIn={229.4}
    underGoal={true}
    goalDelta={200}
    mainMealsCount={3}
    mealsList={[
        "Cheese & salsa tortilla wraps & cottage cheese",
        "Honey-sriracha stir-fried chicken & veggies",
        "EveryPlate - pork & green pepper tacos"
    ]}
    snacksList={[
        "Collagen protein shake",
    ]}
    didPT={true}
    exerciseSummary={"\"Power Hour\""}
    exerciseList={[
        "10-minute bike ride",
        "Mile run",
        "Bicep curls",
        "Bodyweight Dips"
    ]}
/>