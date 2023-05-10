<script>
	import FoodExerciseLog from "$lib/FoodExerciseLog.svelte";
</script>

<FoodExerciseLog
    dayNum={29}
    date='May 1, 2023'
    weighIn={230.2}
    underGoal={false}
    goalDelta={50}
    mainMealsCount={3}
    mealsList={[
        "Guacamole on whole wheat toast w/ cottage cheese & non-fat plain Greek yogurt",
        "Buffalo veggie burger",
        "EveryPlate - crispy katsu pork chops"
    ]}
    didPT={true}
    exerciseSummary="Calisthenics"
    exerciseList={[
        "band-assisted pull-ups",
    ]}
    otherThoughts="The blog got an update yesterday! Now I have the posts separated by calendar month, and split off from the main blog page. I think this 
    will help keep that main page from getting bloated. It also leaves room for anything else parkour-related I want to blog about. Hope it wasn't 
    too hard finding this post! Also, Trek started charging $5/day for food starting today. Not fun, but it's at least still a better deal than buying my own food 
    and taking it to work with me. I've started to feel like I've been stagnating around the 228-231 pound range lately, too. I was sick for a while, so that meant I was 
    exercising less. I also could improve the quality of my food. It's likely a combination of factors."
/>