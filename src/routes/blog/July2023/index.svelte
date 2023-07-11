<script>
    import '../../../app.css'
    import DayJumper from '$lib/DayJumper.svelte'
    import Day90 from '../../../blogPosts/parkour/nastyChallenge/july2023/90.svelte'
    import Day91 from '../../../blogPosts/parkour/nastyChallenge/july2023/91.svelte'
    import Day92 from '../../../blogPosts/parkour/nastyChallenge/july2023/92.svelte'
    import Day93 from '../../../blogPosts/parkour/nastyChallenge/july2023/93.svelte'
    import Day94 from '../../../blogPosts/parkour/nastyChallenge/july2023/94.svelte'
    import Day95 from '../../../blogPosts/parkour/nastyChallenge/july2023/95.svelte'
    import Day96 from '../../../blogPosts/parkour/nastyChallenge/july2023/96.svelte'
    import Day97 from '../../../blogPosts/parkour/nastyChallenge/july2023/97.svelte'
    import Day98 from '../../../blogPosts/parkour/nastyChallenge/july2023/98.svelte'
    import Day99 from '../../../blogPosts/parkour/nastyChallenge/july2023/99.svelte'
</script>

<main class='flex flex-col w-[100vw] text-white'>
    <h1 id='month-header' class='w-full flex text-lg md:text-2xl justify-center items-center bg-red-500 p-10'>
        <span class='p-7 rounded-xl bg-black flex flex-col justify-evenly items-center'>
            <p class='text-red-500'>#NASTY Challenge</p>
            <p class='font-bold'>July 2023</p>
            <DayJumper startDay={90} currentMonth={true}/>
            <a class='text-sm bg-[#92DCE5] text-black p-2' href='/blog'>Back to Blog</a>
        </span>
    </h1>
    <section class='w-full flex flex-col items-center'>
        <Day90 />
        <Day91 />
        <Day92 />
        <Day93 />
        <Day94 />
        <Day95 />
        <Day96 />
        <Day97 />
        <Day98 />
        <Day99 />
    </section>
</main>