<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={62}
    date='June 3, 2023'
    weighIn={223.6}
    underGoal={false}
    goalDelta={350}
    mainMealsCount={3}
    mealsList={[
        "Eggs & buttered sourdough bread",
        "Beef & cheese bowl w/ onion & peppers",
        "EveryPlate - tunisian-spiced chicken w/ couscous & carrots"
    ]}
    snacksList={[
        "Humm! - zero sugar raspberry lemonade kombucha",
    ]}
    didPT={true}
    exerciseSummary='Bikes & Squats'
    exerciseList={[
        'Short bike ride to Target & back',
        'Dumbbell squats'
    ]}
    otherThoughts={`
        I noticed I've been staying around 222-224 lbs. since about May 25, so almost 
        2 weeks now. While it's nice I'm not going back up in weight, I've noticed my exercise has 
        been decreasing during that same timeframe. So has my fiber consumption, so I may 
        just need to keep up with my veggies, which I tend to slack on when I'm not tracking it. Might need 
        to add "eat a bowl of veggies" to my habit tracking app, and make it 5 days a week. And 
        one way or another, get myself back to doing strength workouts 4 days per week, excluding 
        my PT, so, core & upper body exclusively. First my callouses need to heal up on my hands a bit more, 
        but they're almost there from when they opened up a week ago while swinging on monkey bars.
    `}
/>