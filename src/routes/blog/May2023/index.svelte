<script>
    import '../../../app.css'
    import DayJumper from '$lib/DayJumper.svelte'
    import Day29 from '../../../blogPosts/parkour/nastyChallenge/may2023/29.svelte'
    import Day30 from '../../../blogPosts/parkour/nastyChallenge/may2023/30.svelte'
    import Day31 from '../../../blogPosts/parkour/nastyChallenge/may2023/31.svelte'
    import Day32 from '../../../blogPosts/parkour/nastyChallenge/may2023/32.svelte'
    import Day33 from '../../../blogPosts/parkour/nastyChallenge/may2023/33.svelte'
    import Day34 from '../../../blogPosts/parkour/nastyChallenge/may2023/34.svelte'
    import Day35 from '../../../blogPosts/parkour/nastyChallenge/may2023/35.svelte'
    import Day36 from '../../../blogPosts/parkour/nastyChallenge/may2023/36.svelte'
</script>

<main class='flex flex-col w-[100vw] text-white'>
    <h1 id='month-header' class='w-full flex text-lg md:text-2xl justify-center items-center bg-red-500 p-10'>
        <span class='p-7 rounded-xl bg-black flex flex-col justify-evenly items-center'>
            <p class='text-red-500'>#NASTY Challenge</p>
            <p class='font-bold'>May 2023</p>
            <DayJumper startDay={29} />
            <a class='text-sm text-red-500' href='/blog'>Back to Blog</a>
        </span>
    </h1>
    <section class='w-full flex flex-col items-center'>
        <Day29 />
        <Day30 />
        <Day31 />
        <Day32 />
        <Day33 />
        <Day34 />
        <Day35 />
        <Day36 />
    </section>
</main>