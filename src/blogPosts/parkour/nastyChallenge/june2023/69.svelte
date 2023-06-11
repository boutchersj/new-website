<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={69}
    date='June 10, 2023'
    weighIn={221}
    underGoal={false}
    goalDelta={2150}
    mainMealsCount={3}
    mealsList={[
        "Greek yogurt w/ raspberries, honey & ground flax + buttered whole grain sourdough toast",
        "Trek 100 catering - mustard chicken sandwich on pretzel bun w/ green beans, corn & mac n' cheese",
        "Highway 18 drive-in theater - 'gutbuster' 2/3-lb. cheeseburger + cheese curds, mozz sticks & onion rings"
    ]}
    snacksList={[
        "Lean Body - 14oz protein shake",
        "Optimal Nutrition - preworkout energy drink",
        "Kate's Real Food - 2 energy bars",
        "Orange"
    ]}
    didPT={false}
    exerciseSummary='Trek 100'
    exerciseList={[
        '19-mile bike ride - took about 2 hours, forgot to record it in Strava',
    ]}
    otherThoughts={`
        Today was the Trek 100! Woohoo! My first bike event! I biked the 19-mile route. 
        The first 10 miles, I was on my personal acoustic bike, and then at the rest stop, 
        I swapped it for an electric BCycle bike because my legs were getting pretty sore. 
        I had excellent pre-event nutrition, but after the event was over, I kinda stopped watching 
        what I was eating. I did make sure to avoid sources of added sugar, but I ate a lot of fried 
        and barbecued food post-event and at the drive-in movie theater Sam & I went to later in the 
        evening. That was our first drive-in theater experience, and I was more interested in sampling 
        their concession stand offerings than meeting my calorie goal for the day.
    `}
/>