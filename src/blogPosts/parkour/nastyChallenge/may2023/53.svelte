<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={53}
    date='May 25, 2023'
    weighIn={223.4}
    underGoal={false}
    goalDelta={650}
    mainMealsCount={2}
    mealsList={[
        "Dunkin - bacon breakfast tacos w/ large plain iced cappuccino",
        "Mooyah - double diablo burger w/ homemade chips",
    ]}
    snacksList={[
        "Joyride - sour gummy bears",
        "String cheese",
        "Coffee w/ collagen protein"
    ]}
    didPT={false}
    otherThoughts={`
        Not really sure how I've been continuing to lose weight even without any exercise or PT. 
        I've been in a calorie surplus for the last couple of weeks without any days under my calorie 
        goal. The only thing I can think of is that I haven't been snacking on bread for the last 3 days, 
        and I've been eating more high-protein & high-fiber snacks like string cheese, veggies & hummus. I'm 
        going to have to see what happens next time I have a lot of bread.
    `}
/>