<script>
    import BlogPost from '../../../routes/blog/BlogPost.svelte'
</script>

<BlogPost dayNum={33} date='May 5, 2023' weighIn={228}>
    <div slot='content'>
        <h3 class='font-bold'>Food</h3>
        <br />
        <p>
            Over calorie goal by 300. 3 main meals:
        </p>
        <ul class='list-disc ml-10 my-3'>
            <li>Salami & Provolone on a Pretzel Bun</li>
            <li>Trek Snack Wrap</li>
            <li>Seafood Enchiladas, Rice, & Beans</li>
        </ul>
        <p>I had a margarita with dinner, too!</p>
        <br />
        <h3 class='font-bold'>PT</h3>
        <br />
        <p>Yep!</p>
        <br />
        <h3 class='font-bold'>Exercise</h3>
        <br />
        <p>Ran a mile & 15-minute bike ride.</p>
    </div>
</BlogPost>