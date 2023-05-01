<script>
    import '../../../app.css'
    import DayJumper from '$lib/DayJumper.svelte'
    import Day29 from '../../../blogPosts/parkour/29.svelte'
</script>

<main class='flex flex-col w-[100vw] text-white'>
    <h1 class='w-full flex text-lg md:text-2xl justify-center items-center bg-red-500 p-10'>
        <span class='p-7 rounded-xl bg-black flex flex-col justify-evenly items-center'>
            <p class='text-red-500'>#NASTY Challenge</p>
            <p class='font-bold'>May 2023</p>
            <DayJumper />
            <a class='text-sm' href='/blog'>Back to Blog</a>
        </span>
    </h1>
    <section class='w-full flex flex-col items-center'>
        <Day29 />
    </section>
</main>