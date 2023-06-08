<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={60}
    date='June 1, 2023'
    weighIn={223.4}
    underGoal={true}
    goalDelta={22}
    mainMealsCount={1}
    mealsList={[
        "EveryPlate - cheesy chicken & pepper quesadillas",
    ]}
    snacksList={[
        "Gala apple",
        "String cheese",
        "Quest - Protein cookie",
        "Kettle - BBQ kettle-cooked potato chips"
    ]}
    didPT={true}
    exerciseSummary='Biking'
    exerciseList={[
        '40-minute bike ride with my team',
    ]}
    otherThoughts={`
        I got my full BioScreen results back today and I PASSED this time! Much like how I did a side-by-side comparison for the InBody 
        body composition tests from February & May, I'm going to show the lab results from January 25 adjacent the May 31 lab results.
    `}
>
    <div slot='extraContent'>
        <h3 class='text-2xl my-5'>BioScreen Results Comparison</h3>
        <p>
            I have never seen my blood pressure this low! And just like my nutritionist predicted, my cholesterol came down as a result of 
            my lifestyle changes. This goes to show that committing to eliminating added sugar and including a modest amount of cardio can go 
            a long way.
        </p>
        <br />
        <img src='/blood_panel_comparison.png' alt='Comparison table of the lab results from my BioScreens on January 25 and May 31 2023' />
    </div>
</FoodExerciseLog>