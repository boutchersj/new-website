<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={48}
    date='May 20, 2023'
    weighIn={227}
    underGoal={false}
    goalDelta={300}
    mainMealsCount={2}
    mealsList={[
        "Peppers, onions & cheese rice bowl w/ sriracha mayo",
        "Red Robin - Double guacamole bacon burger w/ pineapple & jalapeños + side salad w/ oil & vinegar"
    ]}
    snacksList={[
        "Rx Bar - Peanut butter chocolate",
        "Gatorade Zero - lemon lime"
    ]}
    didPT={false}
    exerciseSummary="Long bike ride"
    exerciseList={[
        "2-hour-15-minute bike ride (22 miles; to the Capitol & back)",
    ]}
>
    <div slot='extraContent'>
        <img src='/first_long_bike_ride.PNG' alt='InBody results from May 18, 2023' />
    </div>
</FoodExerciseLog>