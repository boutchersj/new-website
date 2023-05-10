<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={19}
    date='April 21, 2023' 
    weighIn={230.6}
    underGoal={false}
    goalDelta={1800}
    mainMealsCount={3}
    mealsList={[
        "Gluten-free ravioli w/ marinara & grass-fed ground beef",
        "Beef brisket sandwich on a pretzel bun w/ potato chips",
        "Red Robin - Madlove burger w/ steak fries & onion rings"
    ]}
    snacksList={[
        "Rice cake w/ peanut butter",
    ]}
    didPT={false}
    exerciseSummary="Mountain biking"
    exerciseList={[
        "Trail riding at Trek",
    ]}
    otherThoughts={`
        I did a lot of mountain biking today and crashed! Got a few cuts and bruises, nothing serious. I 
        aggravated my bad knee again, and that wasn't fun, but it should be fine again tomorrow. I've noticed 
        the flare-up doesn't last very long the last few times I've landed hard on it.\n\n

        I was disappointed to find out after-the-fact that the MadLove burger I ordered from Red Robin tonight 
        had Island Heat sauce in it, which definitely contributed to it having 27g of sugar overall. Gonna bet that this technically breaks 
        the rules of the challenge, except for the fact that I didn't knowingly order a burger with sugar. That said, I should do better research 
        next time. I ordered a side of Island Heat sauce too before realizing I'd need to throw it away when it arrived because 1 dipping cup has 29g of 
        added sugar in it. It wasn't hard to throw it away. I was just being a little lazy when reading the nutrition facts sheet for the 
        restaurant because I was mostly concerned with optimizing for high protein.
    `}
/>