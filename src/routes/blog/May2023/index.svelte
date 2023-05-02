<script>
    import '../../../app.css'
    import DayJumper from '$lib/DayJumper.svelte'
    import Day29 from '../../../blogPosts/parkour/nastyChallenge/29.svelte'
    import Day30 from '../../../blogPosts/parkour/nastyChallenge/30.svelte'
</script>

<main class='flex flex-col w-[100vw] text-white'>
    <h1 class='w-full flex text-lg md:text-2xl justify-center items-center bg-red-500 p-10'>
        <span class='p-7 rounded-xl bg-black flex flex-col justify-evenly items-center'>
            <p class='text-red-500'>#NASTY Challenge</p>
            <p class='font-bold'>May 2023</p>
            <DayJumper startDay={29} />
            <a class='text-sm' href='/blog'>Back to Blog</a>
        </span>
    </h1>
    <section class='w-full flex flex-col items-center'>
        <Day29 />
        <Day30 />
    </section>
</main>