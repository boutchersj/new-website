<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={22}
    date='April 24, 2023'
    weighIn={230.8}
    underGoal={true}
    goalDelta={300}
    mainMealsCount={3}
    mealsList={[
        "Starbucks - kale & portobello mushroom egg bites w/ nitro cold brew",
        "Rice cakes w/ peanut butter",
        "EveryPlate - \"bacon me hungry\" tortelloni"
    ]}
    snacksList={[
        "Olipop cream soda",
        "SmartSweets gummi worms"
    ]}
    didPT={false}
    otherThoughts={`
        Today I felt really sick, and ended up working from home so I could manage 
        my headaches and body aches.
    `}
/>