<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={76}
    date='June 17, 2023'
    weighIn={221.6}
    underGoal={false}
    goalDelta={1300}
    mainMealsCount={3}
    mealsList={[
        "Homemade - chicken & cheese burrito w/ flax seed",
        "Panda Express - kung pao chicken + mushroom chicken + super greens plate",
        "EveryPlate - pizzeria pork sausage soup"
    ]}
    snacksList={[
        "Kiwi",
        "Homemade - Cheese burrito",
        "String cheese",
        "Keto - peanut butter cup pint"
    ]}
    didPT={true}
    exerciseSummary='Day at the Y'
    exerciseList={[
        'Morning bike ride to YMCA & back',
        '15-minute swim',
        'Weightlifting - bench press, shoulder press, assisted pull-ups'
    ]}
/>