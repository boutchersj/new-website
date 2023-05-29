<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={56}
    date='May 28, 2023'
    weighIn={226.4}
    underGoal={false}
    goalDelta={1600}
    mainMealsCount={2}
    mealsList={[
        "Pepperoni twist bread - a lot of it",
        "Palermo's - slice of cheese pizza @ the kite festival in Veteran's Park in Milwaukee"
    ]}
    snacksList={[
        'String cheese',
        'Almonds w/ peanut butter',
        'Keto peanut butter ice cream bars'
    ]}
    didPT={false}
    exerciseSummary='Summer fun'
    exerciseList={[
        'Flying kites - a surprising amount of walking',
        'Bike sprints - HIIT-style - 3 rounds',
    ]}
    otherThoughts={`
        Based on my weigh-in today and how I was feeling last night, I'm pretty sure eating white bread and black beans 
        gives me some level of digestive dysfunction. I'm not sure how or why, but I think avoiding those 2 foods is 
        probably going to help me feel better, if not reduce inflammation and continue losing weight.
    `}
/>