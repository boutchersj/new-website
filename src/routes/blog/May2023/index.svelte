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
    import Day37 from '../../../blogPosts/parkour/nastyChallenge/may2023/37.svelte'
    import Day38 from '../../../blogPosts/parkour/nastyChallenge/may2023/38.svelte'
    import Day39 from '../../../blogPosts/parkour/nastyChallenge/may2023/39.svelte'
    import Day40 from '../../../blogPosts/parkour/nastyChallenge/may2023/40.svelte'
    import Day41 from '../../../blogPosts/parkour/nastyChallenge/may2023/41.svelte'
    import Day42 from '../../../blogPosts/parkour/nastyChallenge/may2023/42.svelte'
    import Day43 from '../../../blogPosts/parkour/nastyChallenge/may2023/43.svelte'
    import Day44 from '../../../blogPosts/parkour/nastyChallenge/may2023/44.svelte'
    import Day45 from '../../../blogPosts/parkour/nastyChallenge/may2023/45.svelte'
    import Day46 from '../../../blogPosts/parkour/nastyChallenge/may2023/46.svelte'
    import Day47 from '../../../blogPosts/parkour/nastyChallenge/may2023/47.svelte'
    import Day48 from '../../../blogPosts/parkour/nastyChallenge/may2023/48.svelte'
    import Day49 from '../../../blogPosts/parkour/nastyChallenge/may2023/49.svelte'
    import Day50 from '../../../blogPosts/parkour/nastyChallenge/may2023/50.svelte'
    import Day51 from '../../../blogPosts/parkour/nastyChallenge/may2023/51.svelte'
    import Day52 from '../../../blogPosts/parkour/nastyChallenge/may2023/52.svelte'
    import Day53 from '../../../blogPosts/parkour/nastyChallenge/may2023/53.svelte'
    import Day54 from '../../../blogPosts/parkour/nastyChallenge/may2023/54.svelte'
    import Day55 from '../../../blogPosts/parkour/nastyChallenge/may2023/55.svelte'
    import Day56 from '../../../blogPosts/parkour/nastyChallenge/may2023/56.svelte'
    import Day57 from '../../../blogPosts/parkour/nastyChallenge/may2023/57.svelte'
</script>

<main class='flex flex-col w-[100vw] text-white'>
    <h1 id='month-header' class='w-full flex text-lg md:text-2xl justify-center items-center bg-red-500 p-10'>
        <span class='p-7 rounded-xl bg-black flex flex-col justify-evenly items-center'>
            <p class='text-red-500'>#NASTY Challenge</p>
            <p class='font-bold'>May 2023</p>
            <DayJumper startDay={29} currentMonth={true}/>
            <a class='text-sm bg-[#92DCE5] text-black p-2' href='/blog'>Back to Blog</a>
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
        <Day37 />
        <Day38 />
        <Day39 />
        <Day40 />
        <Day41 />
        <Day42 />
        <Day43 />
        <Day44 />
        <Day45 />
        <Day46 />
        <Day47 />
        <Day48 />
        <Day49 />
        <Day50 />
        <Day51 />
        <Day52 />
        <Day53 />
        <Day54 />
        <Day55 />
        <Day56 />
        <Day57 />
    </section>
</main>