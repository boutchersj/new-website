<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={18}
    date='April 20, 2023'
    weighIn={230.6}
    underGoal={false}
    goalDelta={500}
    mainMealsCount={3}
    mealsList={[
        "McDonald's - Steak egg & cheese bagel w/ large plain hot latte",
        "Turkey, cheese, & guac wrap",
        "Gluten-free ravioli w/ marinara & grass-fed ground beef"
    ]}
    didPT={false}
    exerciseSummary="Casual calisthenics"
    exerciseList={[
        "indoor parkour vaulting",
        "indoor rock climbing"
    ]}
    otherThoughts={`
        I took an InBody scan today and apparently, I've lost 12 pounds of fat without losing any muscle! I even 
        gained a little bit of it. My nutritionist says it's because of this no-added-sugar journey, and how it's been 
        able to bring down my inflammation and allow fat to be released now that my body isn't producing so much insulin 
        anymore. I thought it'd be cool to show the InBody from February and the InBody from today in the same post here.
    `}
>
    <div slot='extraContent'>
        <h3 class='text-2xl my-5'>February 27, 2023</h3>
        <img src='/InBody_2_27_2023.jpeg' alt='InBody results from February' />
        <h3 class='text-2xl my-5'>Today</h3>
        <img src='/InBody_4_20_2023.jpeg' alt='InBody results from today' />
        <br />
        <p>
            On a final note, a buddy of mine I hadn't seen since before I started this challenge told me my face looked slimmer after I told him 
            about the challenge I've been doing. And you know what? I agree with him!
        </p>
        <img class='mt-5' src='/me_4_20.jpeg' alt='selfie while walking outside Target' />
    </div>
</FoodExerciseLog>