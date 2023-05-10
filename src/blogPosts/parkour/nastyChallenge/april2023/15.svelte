<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={15}
    date='April 17, 2023'
    weighIn={232.8}
    underGoal={true}
    goalDelta={500}
    mainMealsCount={3}
    mealsList={[
        "Starbucks - Kale & Portobello Mushroom Sous Vide Egg Bites",
        "EveryPlate - creamy mushroom & pea cavatappi",
        "2x Healthy Choice meals (the variety with no added sugar)"
    ]}
    snacksList={[
        "Peanut butter chocolate Rx bar",
    ]}
    didPT={true}
    exerciseSummary={"\"Power Hour\""}
    exerciseList={[
        "10-minute bike ride",
        "Mile run",
        "Kettlebell walks"
    ]}
/>