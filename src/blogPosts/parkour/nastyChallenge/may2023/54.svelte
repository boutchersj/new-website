<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={54}
    date='May 26, 2023'
    weighIn={222.6}
    underGoal={false}
    goalDelta={900}
    mainMealsCount={2}
    mealsList={[
        "Culver's - smokehouse bbq cheddar pub burger",
        "EveryPlate - italian pork sausage sandos w/ garlic potato wedges"
    ]}
    snacksList={[
        'String cheese',
        'Buttered crescent rolls w/ pepperoni & cheese'
    ]}
    didPT={true}
    exerciseSummary='Mixed bag'
    exerciseList={[
        '20-minute bike ride',
        'Climbing around on a playground',
        '1/2-mile run',
    ]}
    otherThoughts={`
        Haven't been at this weight since September 2020!
    `}
/>