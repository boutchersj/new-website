<script>
    import ExerciseLog from '$lib/ExerciseLog.svelte';
</script>

<ExerciseLog
    dayNum={77}
    date='June 18, 2023'
    weighIn={222.8}
    didPT={false}
    exerciseSummary='Beach Day'
    exerciseList={[
        'Light badminton & kite flying on the beach (the sand offered some resistance)'
    ]}
    otherThoughts={`
        I've decided today to stop tracking my food. It's started to feel like mental overhead that is subtracting 
        from my energy and holding me back. At the outset, it was a fantastic accountability tool, but I feel lately 
        like I'm going through the motions when I track my food. My intuition about what I should eat and how much has 
        greatly improved since Day 0 of this challenge. My new default behavior is to choose foods without added sugar 
        and to exercise several times per week. While I don't adhere to my calorie goal very often anymore, that hasn't 
        stopped me from losing weight. I'm also aware of how much I can eat and still hit my calorie goal even without looking at 
        the app. I just tend to not give as much weight to the calorie limit as I do to my protein, fiber, and sugar consumption. 
        Going forward, I'm going to continue to track my weight, PT, and exercise, as usual.
    `}
>
    <div slot='extraContent'>
        <h2 class="text-xl font-bold">2023 Weight Loss Journey - First Half</h2>
        <br />
        <img src='/first_half_2023_weight_loss.jpeg' alt="Weight Loss chart for January to June 2023 - I'm 20 lbs down from 6 months ago" />
    </div>
</ExerciseLog>