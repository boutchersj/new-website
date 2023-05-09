<script>
    import BlogPost from '../../../../routes/blog/BlogPost.svelte'
</script>

<BlogPost dayNum={36} date='May 8, 2023' weighIn={229.4}>
    <div slot='content'>
        <h3 class='font-bold'>Food</h3>
        <br />
        <p>Under calorie goal by 200.</p>
        <br />
        <p>2 main meals:</p>
        <ul class='list-disc ml-10 my-3'>
            <li>McDonald's - steak egg & cheese bagel w/ a plain iced latte</li>
            <li>EveryPlate - cream of mushroom soup</li>
        </ul>
        <p>Snacks - a salad I made at Trek's salad bar</p>

        <br />

        <h3 class='font-bold'>PT</h3>
        <br />
        <p>No</p>

        <br />

        <h3 class='font-bold'>Exercise</h3>
        <br />
        <p>Parkour-style conditioning:</p>
        <ul class='list-disc ml-10 my-3'>
            <li>quadrupedal movement</li>
            <li>monkey bars</li>
            <li>push-ups</li>
        </ul>
    </div>
</BlogPost>