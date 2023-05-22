<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={49}
    date='May 21, 2023'
    weighIn={226.2}
    underGoal={false}
    goalDelta={900}
    mainMealsCount={2}
    mealsList={[
        "Zuzu's - Lablabi breakfast",
        "EveryPlate - creamy smothered pork chops"
    ]}
    snacksList={[
        "Henry Vilas Zoo - bavarian pretzel w/ nacho cheese cup",
        "2x Rockin' Refuel 30g protein shakes + 6oz carton of raspberries (post-workout)",
        "4x Pillsbury crescent rolls each rolled up with 3 pepperoni"
    ]}
    didPT={true}
    exerciseSummary="Mixed bag"
    exerciseList={[
        "7.6-mile bike ride to D.R.E.A.M. Park (Sun Prairie) and back",
        "Parkour - vaulting, climbing, balancing, tiny jumps, push-ups",
        "2-mile run"
    ]}
    otherThoughts={`
        I'm thinking that the place I could've added more protein today was at the zoo. I didn't have any food with me, 
        so I just ate whatever they were selling that didn't have sugar in it. Surprisingly few options at a zoo, or 
        maybe not so surprising. In any case, I bought some string cheese today so I could have some better snacking 
        options. I'm holding off on replacing my bread loaf for now because it's too easy to have 4-6 slices in a day.
    `}
>
    <div slot='extraContent'>
        <img src='/bike_ride_5_21_23.jpeg' alt='Strava ride details - 7.6 miles to D.R.E.A.M Park and back for about 45 minutes at about 10 mph' />
        <br />
        <!-- svelte-ignore a11y-media-has-caption -->
        <video preload='auto' controls muted autoplay loop>
            <source src='/Parkour_5_21_23.mp4' type='video/mp4'>
        </video>
    </div>
</FoodExerciseLog>