<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={66}
    date='June 7, 2023'
    weighIn={223.4}
    underGoal={true}
    goalDelta={17}
    mainMealsCount={3}
    mealsList={[
        "Trek Cafe + McDonald's - Nonfat plain greek yogurt w/ mixed berries + iced sugar-free vanilla latte",
        "Trek Cafe - 'Guac my world' wrap -- turkey, guacamole, and other veggies & maybe prosciutto?",
        "Noodles & Company - Backyard BBQ Chicken salad w/ 3 potstickers"
    ]}
    snacksList={[
        "Kind - oats & honey bar",
        "String cheese",
        "Pink Lady apple"
    ]}
    didPT={false}
/>