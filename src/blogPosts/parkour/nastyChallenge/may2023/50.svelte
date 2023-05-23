<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={50}
    date='May 22, 2023'
    weighIn={227}
    underGoal={false}
    goalDelta={1100}
    mainMealsCount={4}
    mealsList={[
        "Nonfat plain Greek yogurt w/ mixed berries & pineapple chunks",
        "Gnocchi w/ marinara & squash/zucchini medley",
        "EveryPlate - Saucy chicken & pepper stir fry",
        "McDonald's - Big Mac"
    ]}
    snacksList={[
        "Joyride - berry gummy guppies",
        "Salted almonds w/ peanut butter",
        "2% milk",
        "String cheese"
    ]}
    didPT={false}
    exerciseSummary="Mixed bag"
    exerciseList={[
        "10-minute morning bike ride",
        "Trek Gym - rock climbing",
        "Trek Trails - 2.27-mile run on the Joe V trail"
    ]}
>
    <div slot='extraContent'>
        <img alt='selfie in the woods on the Joe V trail of the Trek Trail system' src='/trail_run_selfie_5_22_23.jpeg' />
        <br />
        <img alt='Nike Run Club run details from trail run - 2.27 miles - average pace of 11:36 per mile' src='/trail_run_5_22_23.PNG' />
    </div>
</FoodExerciseLog>