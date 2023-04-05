<script>
    import BlogPost from '../BlogPost.svelte'
</script>

<BlogPost dayNum={3} date='April 5, 2023' weighIn={234.6}>
    <div slot='content'>
        <p>[In progress]</p>
    </div>
</BlogPost>