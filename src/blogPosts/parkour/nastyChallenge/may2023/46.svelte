<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={46}
    date='May 18, 2023'
    weighIn={227.4}
    underGoal={false}
    goalDelta={850}
    mainMealsCount={4}
    mealsList={[
        "Starbucks - Spinach & feta wrap w/ plain flat white",
        "Trek Cafe - spinach/aruguala salad with chicken",
        "Trek Cafe - 'Hercules wrap' - hummus & chicken w/ veggies",
        "EveryPlate - Southwest-spiced beef & rice bowls w/ pico de gallo & lime crema"
    ]}
    snacksList={[
        "6 slices of Dave's Killer Bread with butter",
    ]}
    didPT={true}
    exerciseSummary="Mixed bag"
    exerciseList={[
        "15-minute bike ride",
        "Mile run",
        "10 x 1 bodyweight pull-ups",
        "3 x 12 push-ups"
    ]}
    otherThoughts={`
        I had my 3rd InBody scan today! According to my nutritionist, I've been skimping on 
        protein & veggies overall, and according to me, I've been skimping on strength training. Those combined to 
        create a drop in muscle mass of about 2 pounds, and all my cardio & sugar elimination gave me 
        a drop in body fat of 1 pound. Overall, my body fat percentage went up, because I lost 
        more muscle than fat. That said, if I make sure that my "bread snacks" include some protein 
        and I keep up my strength training & veggie consumption, I should be in a good 
        place by the next InBody scan.
    `}
>
    <div slot='extraContent'>
        <h3 class='text-2xl my-5'>Today's InBody Scan!</h3>
        <img src='/InBody_5_18_2023.png' alt='InBody results from May 18, 2023' />
    </div>
</FoodExerciseLog>