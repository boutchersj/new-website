<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={43}
    date='May 15, 2023'
    weighIn={227}
    underGoal={false}
    goalDelta={500}
    mainMealsCount={4}
    mealsList={[
        "Dave's Killer Bread epic everything peanut butter toast w/ cottage cheese",
        "Cheese tortellini",
        "Olive & feta wrap",
        "Grass-fed strip steak w/ asparagus & reishi and oyster mushrooms"
    ]}
    snacksList={[
        "Chili-seasoned pickled pineapple",
        "Dave's Killer Bread epic everything buttered bread"
    ]}
    didPT={false}
    exerciseSummary="Strength training"
    exerciseList={[
        "Core workout",
        "Rail vaulting at the park"
    ]}
/>