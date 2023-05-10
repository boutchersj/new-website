<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={21} 
    date='April 23, 2023' 
    weighIn={229.4}
    underGoal={false}
    goalDelta={1000}
    mainMealsCount={3}
    mealsList={[
        "Rice cakes w/ peanut butter",
        "Burger King - spicy melt + homemade hot [sugar-free] honey mustard broccoli",
        "Homemade spicy mac n cheese"
    ]}
    didPT={false}
    otherThoughts={`
        I've been feeling a bit under the weather this weekend and it's making me not want to 
        go outside in the cold to run or bike. And I'm more in the mood to nap than exercise 
        indoors, so, it is what it is.
    `}
/>