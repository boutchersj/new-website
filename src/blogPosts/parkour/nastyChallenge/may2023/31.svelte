<script>
    import BlogPost from '../../../../routes/blog/BlogPost.svelte'
</script>

<BlogPost dayNum={31} date='May 3, 2023' weighIn={230}>
    <div slot='content'>
        <p>
            Feeling like a quick summary today:
        </p>
        <br />
        <h3 class='font-bold'>Food</h3>
        <br />
        <p>
            Over calorie goal by 300. 2 main meals:
        </p>
        <ul class='list-disc ml-10 my-3'>
            <li>Chipotle Chicken Avocado Melt from Panera</li>
            <li>Sweet Potato Onion Tacos from our EveryPlate box</li>
        </ul>
        <p>Other than that, some whole wheat bread & butter for a snack</p>
        <br />
        <h3 class='font-bold'>PT</h3>
        <br />
        <p>Rest day</p>
        <br />
        <h3 class='font-bold'>Exercise</h3>
        <br />
        <p>Rest day</p>
    </div>
</BlogPost>