<script>
    import FoodExerciseLog from '$lib/FoodExerciseLog.svelte';
</script>

<FoodExerciseLog
    dayNum={28}
    date='April 30, 2023'
    weighIn={229.4}
    underGoal={false}
    goalDelta={350}
    mainMealsCount={3}
    mealsList={[
        "Dave's Killer Bread whole wheat guacamole toast",
        "Stir-fried veggies w/ avocado chunks & diced chicken",
        "Salsa & cheese tortilla wraps w/ crescent rolls & cottage cheese"
    ]}
    snacksList={[
        "Dave's Killer Bread buttered whole wheat toast",
        "Lily's sour gummi worms"
    ]}
    didPT={false}
>
    <div slot='extraContent'>
        <br />
        <hr />
        <br />
        <p>
            I did want to touch on the format of this blog, though. I don't know when I'll have time to do it, but it wasn't over this past weekend 
            like I thought it was going to be. My plan is to split these blog post cards off into separate pages and link to them from this main blog 
            site. I'm thinking I'll have 1 month of posts on a page for easy scrolling, and have links to those pages that say "April 2023", "May 2023", etc. 
            The links will live on the intro blog post for this challenge at the top of the main blog. Eventually, I want this blog to be for talking about stuff 
            other than this niche nutrition challenge. I consider my parkour practice to be holistic in the sense of nutrition, physical training, as well as "spiritual" 
            training (for me, this means philosophy and mental/emotional discipline). So in order to accommodate more topics, I need to free up some space on this blog 
            by canning the space this challenge takes up.
        </p>
        <br />
        <p>
            I'm also considering making these posts less freeform and more structured so I ensure that I talk about my food, weight, and physical activity every day, plus anything else 
            significant that might impact my results that I'd want to mention. If I introduced a structured format, I'd retroactively apply it to all the previous days. I just think it 
            makes it easier to follow for people. This format was nice for getting going, but it feels too easy to go off the rails, and I'm a rambler.
        </p>
        <br />
        <p>
            In other website news, beyond this blog, on my main page, I'm looking to change the design of the "Journeys & Side Quests" cards so it's more intuitive. I 
            want this blog to be easier to find for the person who decides to stop by my website for the first time. Sam (my wife) gave me the idea to make it look like 
            a stack of cards or tabbed dividers, so I'm going to look into that approach first because I think it sounds cool.
        </p>
    </div>
</FoodExerciseLog>