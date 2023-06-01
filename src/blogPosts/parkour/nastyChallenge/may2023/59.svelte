<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={59}
    date='May 31, 2023'
    weighIn={224.4}
    underGoal={false}
    goalDelta={550}
    mainMealsCount={2}
    mealsList={[
        "Trek Cafe - bacon egg & cheese muffin",
        "McDonald's - 20-piece nuggets w/ buffalo sauce"
    ]}
    snacksList={[
        "Cheez-Its - a regular-size box",
        "Gatorlyte - a 12oz bottle (technically had sugar but I'd just had my blood drawn)",
        "Cold brew & 2 green apples"
    ]}
    didPT={true}
    exerciseSummary='Biking & Jumping'
    exerciseList={[
        '20-minute trail ride on the Trek Trails',
        'Box jumps of varying heights to challenge my bad knee'
    ]}
/>