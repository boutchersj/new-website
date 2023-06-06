<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={64}
    date='June 5, 2023'
    weighIn={223.8}
    underGoal={false}
    goalDelta={850}
    mainMealsCount={3}
    mealsList={[
        "McDonald's - steak egg & cheese bagel w/ iced sugar free vanilla latte",
        "Trek Cafe - spinach & ricotta cheese manicotti",
        "EveryPlate - bacon & roasted tomato linguine"
    ]}
    snacksList={[
        "Humm! - mango passionfruit kombucha",
        "Sugar-free gummies (Alani & Tid Bits brands)",
        "String cheese",
        "Cheese, beef, peppers & onion quesadilla (corn tortilla) w/ Pace hot salsa"
    ]}
    didPT={true}
    exerciseSummary='Bikes & Parkour'
    exerciseList={[
        'Jump exercises as add-on to PT',
        'Kong vaulting up to a block from an aerobic step',
        '2-hour casual team bike ride on the Trek trails',
        'Bodyweight pull-ups - (5-5-3)'
    ]}
/>