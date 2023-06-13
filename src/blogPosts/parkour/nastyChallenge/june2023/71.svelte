<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={71}
    date='June 12, 2023'
    weighIn={222.4}
    underGoal={false}
    goalDelta={1400}
    mainMealsCount={3}
    mealsList={[
        "Greek yogurt w/ raspberries, honey & flax",
        "PB&J w/ milk + pretzels w/ peanut butter",
        "Toppers Pizza - Wisconsin curds & bacon pizza w/ tacostix"
    ]}
    didPT={false}
    exerciseSummary='Morning cardio'
    exerciseList={[
        'Bike to the Sun Prairie YMCA & back',
        '15-minute lap swim'
    ]}
/>