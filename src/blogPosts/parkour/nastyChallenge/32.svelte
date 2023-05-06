<script>
    import BlogPost from '../../../routes/blog/BlogPost.svelte'
</script>

<BlogPost dayNum={32} date='May 4, 2023' weighIn={229.6}>
    <div slot='content'>
        <h3 class='font-bold'>Food</h3>
        <br />
        <p>
            Under calorie goal by 100. 3 main meals:
        </p>
        <ul class='list-disc ml-10 my-3'>
            <li>Prosciutto & Cheese Wrap</li>
            <li>Salad</li>
            <li>Kale & Sausage Soup</li>
        </ul>
        <p>For snacks, I had some chips, cottage cheese, and a buttered tortilla.</p>
        <br />
        <h3 class='font-bold'>PT</h3>
        <br />
        <p>Yes! Lunges are getting easier. Started using 20-pound weights with my squats.</p>
        <br />
        <h3 class='font-bold'>Exercise</h3>
        <br />
        <p>Short bike ride, mile run, and an upper body workout.</p>
    </div>
</BlogPost>