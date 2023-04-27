<script>
    import BlogPost from '../../routes/blog/BlogPost.svelte'
</script>

<BlogPost dayNum={1} date='April 3, 2023' weighIn={238}>
    <div slot='content'>
        <p>
            Today was a little <i>too</i> easy. I'm not sure, maybe it's the initial burst of motivation 
            that always comes with a new challenge! But I didn't have to work hard at all to eat the right foods and 
            I had tons of energy!
        </p>
    </div>
</BlogPost>