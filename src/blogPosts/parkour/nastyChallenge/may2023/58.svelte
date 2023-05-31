<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={58}
    date='May 30, 2023'
    weighIn={223.8}
    underGoal={false}
    goalDelta={200}
    mainMealsCount={3}
    mealsList={[
        "Trek cafe - salad w/ chicken & mozzarella",
        "Trek cafe - wrap w/ turkey & prosciutto",
        "EveryPlate - salisbury steaks w/ herb mashed potatoes & carrots"
    ]}
    snacksList={[
        'String cheese',
        'Green apple'
    ]}
    didPT={false}
/>