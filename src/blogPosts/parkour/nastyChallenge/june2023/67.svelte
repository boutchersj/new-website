<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={67}
    date='June 8, 2023'
    weighIn={221.6}
    underGoal={false}
    goalDelta={370}
    mainMealsCount={2}
    mealsList={[
        "Homemade big breakfast - 4 cheesy eggs w/ nonfat plain greek yogurt & salsa + spring mix salad w/ 3 tomato slices & ginger vinaigrette",
        "EveryPlate - tomato chicken sausage cavatappi with roasted garlic & bell pepper"
    ]}
    snacksList={[
        "Lily's - [sugar-free] peanut butter filled chocolate bar",
        "Joyride - [sugar-free] sour gummy bears",
        "Yerba mate",
        "Halo Top - peanut butter cup ice cream (12g added)",
        "Humm! - kombucha (0g added)"
    ]}
    didPT={true}
    exerciseSummary='Core & Climb'
    exerciseList={[
        'Core workout from my strength coach',
        'Short rock climbing sesh'
    ]}
/>