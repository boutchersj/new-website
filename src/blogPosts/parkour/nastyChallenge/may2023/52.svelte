<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={52}
    date='May 24, 2023'
    weighIn={224.2}
    underGoal={false}
    goalDelta={850}
    mainMealsCount={2}
    mealsList={[
        "McDonald's - double quarter pounder with cheese deluxe",
        "Olive Garden - ravioli carbonara w/ side garden salad & breadsticks"
    ]}
    snacksList={[
        "String cheese",
    ]}
    didPT={false}
    otherThoughts={`
        I can say that if I wasn't tracking my calories or doing this challenge right now, given 
        the fact we just had to say goodbye last night to our 9-month-old kitten after only having 
        him for 3 months, I'd be binge-eating junk food today because that's how I cope with stress usually. 
        However trivial this challenge is by comparison, and it's suuuuper trivial, I'm comforted by the knowledge 
        that I'm still making sure I'm doing the bare minimum to keep my body & mind in a good state. Fast food isn't the 
        best choice but we're just not in the mood to do anything useful right now. We both took off 
        of work for the remainder of the week today, and we left work early yesterday after the news we got from the vet in 
        the morning. Today, we spent most of today sleeping, mourning, or watching TV to distract ourselves.
    `}
/>