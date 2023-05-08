<script>
    import BlogPost from '../../../routes/blog/BlogPost.svelte'
</script>

<BlogPost dayNum={35} date='May 7, 2023' weighIn={229.8}>
    <div slot='content'>
        <h3 class='font-bold'>Food</h3>
        <br />
        <p>
            Over calorie goal by 900. 2 main meals:
        </p>
        <ul class='list-disc ml-10 my-3'>
            <li>Hot honey mustard chicken & veggie stir fry</li>
            <li>Culver's Double Deluxe Burger w/ onion rings</li>
        </ul>
        <p>Snacks included buttered bread again.</p>
        <br />
        <h3 class='font-bold'>PT</h3>
        <br />
        <p>No</p>
        <br />
        <h3 class='font-bold'>Exercise</h3>
        <br />
        <p>No exercise today.</p>
    </div>
</BlogPost>