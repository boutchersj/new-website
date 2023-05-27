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
        Not really sure how I've been continuing to lose weight even without any exercise or PT. I'll keep an eye out 
        for trends. Could just be the stress of losing our kitty.
    `}
/>