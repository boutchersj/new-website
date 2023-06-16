<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={74}
    date='June 15, 2023'
    weighIn={220.8}
    underGoal={false}
    goalDelta={400}
    mainMealsCount={2}
    mealsList={[
        "2 homemade breakfast burritos - roasted sweet potato & poblano, shredded montery jack & mozzarella, bacon & eggs + salsa on the side",
        "EveryPlate - pork & poblano tacos"
    ]}
    snacksList={[
        "green apple",
        "Iconic - protein shake",
        "Oh Snap! - pickled chili-seasoned pineapple bites",
        "Joyride - berry gummy guppies & sour gummy bears",
        "Koe - strawberry-lemonade kombucha"
    ]}
    didPT={false}
/>