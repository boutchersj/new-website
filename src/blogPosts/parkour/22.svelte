<script>
    import BlogPost from '../../routes/blog/BlogPost.svelte'
</script>

<BlogPost dayNum={22} date='April 24, 2023' weighIn={230.8}>
    <div slot='content'>
        <p>
            Today I felt really sick, and ended up working from home so I could manage my headaches and body 
            aches. Needless to say, I didn't work out or do any PT. I was mostly either working on the couch or 
            taking a nap. Not a great day overall.
        </p>
        <br />
        <p>
            I noticed the mac n cheese overload from yesterday caught up to me this morning. That said, I finished the day under 
            my calorie goal, so I'm confident tomorrow's weigh-in will be better. Hard to believe I've been at this more than 3 
            weeks now.
        </p>
    </div>
</BlogPost>