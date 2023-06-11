<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={68}
    date='June 9, 2023'
    weighIn={221.2}
    underGoal={true}
    goalDelta={22}
    mainMealsCount={3}
    mealsList={[
        "Whole grain sourdough buttered toast",
        "Trek Cafe - southwest chicken panini",
        "Trek Cafe - cheesy chicken quesadilla"
    ]}
    snacksList={[
        "Joyride - sour gummy bears",
        "Halo Top - peanut butter cup ice cream"
    ]}
    didPT={false}
    otherThoughts={`
        Intentionally took a rest day today so I could be fresh for the Trek 100 tomorrow.
    `}
/>