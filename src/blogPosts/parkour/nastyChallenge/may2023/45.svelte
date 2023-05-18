<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={45}
    date='May 17, 2023'
    weighIn={225.2}
    underGoal={false}
    goalDelta={1100}
    mainMealsCount={3}
    mealsList={[
        "McDonald's - Steak egg & cheese bagel w/ plain iced latte",
        "Trek Cafe - rice bowl with shrimp, chicken, sweet potatoes, and zucchi/squash medley",
        "Ian's Pizza (Madison, WI) - Smoky the Bandit (BBQ) slice, Pomodoro (tomato, spinach & feta) slice, and 1 breadstick"
    ]}
    snacksList={[
        "Kwik Trip - 2 cheese-filled breadsticks",
    ]}
    didPT={false}
    exerciseSummary="Climbing"
    exerciseList={[
        "Rock climbing on the Trek bouldering wall",
    ]}
    otherThoughts={`
        I'll be honest, I don't know how to record the Ian's Pizza meal I had because they don't have any nutritional 
        information anywhere. I will say that this isn't a normal dinner for me lately. My wife & I went to see The 
        Lion King musical at the Overture Center downtown today, and we wanted to stop somewhere special beforehand 
        instead of making the EveryPlate meal I had started cooking. Ian's is definitely not something I'm going to be 
        making a habit of, and thankfully, it's all the way downtown. But yeah, this meal was probably over 1000 calories, 
        so I'm just adding 1000 to my deficit of 60 and rounding up, so I know what happened if my weight changes tomorrow.
    `}
/>