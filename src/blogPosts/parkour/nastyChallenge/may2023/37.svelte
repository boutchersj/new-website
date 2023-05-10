<script>
    import BlogPost from '../../../../routes/blog/BlogPost.svelte'
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<BlogPost dayNum={37} date='May 9, 2023' weighIn={228}>
    <div slot='content'>
        <FoodExerciseLog
            underGoal={true}
            goalDelta={100}
            mainMealsCount={2}
            mealsList={[
                "A salad I made at Trek's salad bar w/ diced chicken breast",
                "EveryPlate - sweet ginger chicken stir-fry bowls w/ bell pepper & scallion rice"
            ]}
            snacksList={[
                "2 cups of 2% cottage cheese",
            ]}
            didPT={true}
            exerciseSummary="Parkour conditioning"
            exerciseList={[
                "quadrupedal movement",
                "monkey bars",
                "push-ups",
                "safety rolls"
            ]}
    />
    </div>
</BlogPost>