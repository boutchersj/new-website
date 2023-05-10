<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={20}
    date='April 22, 2023'
    weighIn={230.0}
    underGoal={false}
    goalDelta={400}
    mainMealsCount={3}
    mealsList={[
        "Cottage cheese & rice cakes w/ peanut butter",
        "EveryPlate - shoyu-style beef meatball ramen with ginger & scallions",
        "Homemade bacon corn potato chowder"
    ]}
    snacksList={[
        "Tropical Smoothie Cafe - detox island green smoothie w/ Splenda",
    ]}
    didPT={false}
/>