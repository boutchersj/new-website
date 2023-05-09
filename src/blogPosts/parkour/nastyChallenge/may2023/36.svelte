<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
    import BlogPost from '../../../../routes/blog/BlogPost.svelte'
</script>

<BlogPost dayNum={36} date='May 8, 2023' weighIn={229.4}>
    <div slot='content'>
        <FoodExerciseLog
            underGoal={true}
            goalDelta={200}
            mainMealsCount={2}
            mealsList={[
                "McDonald's - steak egg & cheese bagel w/ a plain iced latte",
                "EveryPlate - cream of mushroom soup"
            ]}
            snacksList={[
                "a salad I made at Trek's salad bar"
            ]}
            didPT={false}
            exerciseSummary="Parkour conditioning"
            exerciseList={[
                "quadrupedal movement",
                "monkey bars",
                "push-ups"
            ]}
    />
    </div>
</BlogPost>