<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={51}
    date='May 23, 2023'
    weighIn={226.4}
    underGoal={false}
    goalDelta={750}
    mainMealsCount={2}
    mealsList={[
        "Tropical Smoothie Cafe - baja chicken wrap & peanut paradise smoothie w/ whey protein & Splenda",
        "EveryPlate - brown sugar chipotle pork chops"
    ]}
    snacksList={[
        "Hummus & carrots",
        "String cheese"
    ]}
    didPT={false}
    exerciseSummary="Biking"
    exerciseList={[
        "Morning bike ride to the store & back",
    ]}
    otherThoughts={`
        My wife Sam and I were feeling very sad today. Our cat was diagnosed with FIP, a fatal illness. 
        We ended up going to the emergency vet late at night to find out we needed to put him down. I'm not 
        sure how long grieving's going to take or how demotivated I'll be to continue exercising, 
        but I think keeping up with the no-added-sugar thing is an autopilot thing for me at this point, so I'll 
        keep it up in the meantime. I'm writing this post the following day and I can say this is all taking 
        a massive toll on us emotionally.
    `}
/>