<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={16}
    date='April 18, 2023'
    weighIn={231}
    underGoal={false}
    goalDelta={400}
    mainMealsCount={3}
    mealsList={[
        "Crav'n - Hatch Chile Huevos Rancheros",
        "Italian wrap",
        "EveryPlate - cheesy corn bisque"
    ]}
    snacksList={[
        "Smartsweets - sour watermelon gummies",
    ]}
    didPT={true}
    exerciseSummary={"\"Power Hour\""}
    exerciseList={[
        "10-minute bike ride",
        "Mile run"
    ]}
    otherThoughts={`
        The ease of staying away from sugar at this point can be described as \"auto-pilot\". I'm not even upset about it anymore. 
        I guess it's hard to miss a taste on the tongue when I'm getting benefits like feeling wide awake at 5am, mental clarity 
        all day, weight loss, and plenty of energy to cook and socialize with the family at night. And anything I've missed as part 
        of normal entree food, I've been able to substitute with a no-sugar-added alternative. Not sure if this is a forever thing 
        yet, but I think it can definitely be a year-long thing.
    `}
/>