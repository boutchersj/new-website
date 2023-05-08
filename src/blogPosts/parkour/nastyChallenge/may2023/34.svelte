<script>
    import BlogPost from '../../../../routes/blog/BlogPost.svelte'
</script>

<BlogPost dayNum={34} date='May 6, 2023' weighIn={228.4}>
    <div slot='content'>
        <h3 class='font-bold'>Food</h3>
        <br />
        <p>
            Over calorie goal by 700. 2 main meals:
        </p>
        <ul class='list-disc ml-10 my-3'>
            <li>Ham & Cheese Croissant w/ a latte</li>
            <li>1/2 a large Domino's Sausage Pizza</li>
        </ul>
        <p>Snacks included buttered bread again. Seems like a favorite when I have it on hand.</p>
        <br />
        <h3 class='font-bold'>PT</h3>
        <br />
        <p>Yes</p>
        <br />
        <h3 class='font-bold'>Exercise</h3>
        <br />
        <p>Went on a 45-minute evening bike ride.</p>
    </div>
</BlogPost>