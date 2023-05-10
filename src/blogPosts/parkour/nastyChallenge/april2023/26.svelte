<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={26}
    date='April 28, 2023'
    weighIn={229.8}
    underGoal={false}
    goalDelta={1600}
    mainMealsCount={3}
    mealsList={[
        "Tropical Smoothie Cafe - Avocado grilled cheese, peanut paradise smoothie w/ pea protein & Splenda",
        "Dave's Killer Bread toast w/ peanut butter",
        "Red Lobster - Half salmon entree w/ orzo rice & broccoli w/ cheddar bay biscuits"
    ]}
    didPT={false}
    exerciseSummary="Running errands"
    exerciseList={[
        "Biking to Walgreens & Woodman's",
    ]}
/>