<script>
    import '../../../app.css'
    import DayJumper from '$lib/DayJumper.svelte'
    import Day60 from '../../../blogPosts/parkour/nastyChallenge/june2023/60.svelte'
    import Day61 from '../../../blogPosts/parkour/nastyChallenge/june2023/61.svelte'
    import Day62 from '../../../blogPosts/parkour/nastyChallenge/june2023/62.svelte'
    import Day63 from '../../../blogPosts/parkour/nastyChallenge/june2023/63.svelte'
    import Day64 from '../../../blogPosts/parkour/nastyChallenge/june2023/64.svelte'
    import Day65 from '../../../blogPosts/parkour/nastyChallenge/june2023/65.svelte'
    import Day66 from '../../../blogPosts/parkour/nastyChallenge/june2023/66.svelte'
    import Day67 from '../../../blogPosts/parkour/nastyChallenge/june2023/67.svelte'
    import Day68 from '../../../blogPosts/parkour/nastyChallenge/june2023/68.svelte'
    import Day69 from '../../../blogPosts/parkour/nastyChallenge/june2023/69.svelte'
    import Day70 from '../../../blogPosts/parkour/nastyChallenge/june2023/70.svelte'
    import Day71 from '../../../blogPosts/parkour/nastyChallenge/june2023/71.svelte'
    import Day72 from '../../../blogPosts/parkour/nastyChallenge/june2023/72.svelte'
    import Day73 from '../../../blogPosts/parkour/nastyChallenge/june2023/73.svelte'
    import Day74 from '../../../blogPosts/parkour/nastyChallenge/june2023/74.svelte'
    import Day75 from '../../../blogPosts/parkour/nastyChallenge/june2023/75.svelte'
    import Day76 from '../../../blogPosts/parkour/nastyChallenge/june2023/76.svelte'
    import Day77 from '../../../blogPosts/parkour/nastyChallenge/june2023/77.svelte'
    import Day78 from '../../../blogPosts/parkour/nastyChallenge/june2023/78.svelte'
    import Day79 from '../../../blogPosts/parkour/nastyChallenge/june2023/79.svelte'
    import Day80 from '../../../blogPosts/parkour/nastyChallenge/june2023/80.svelte'
    import Day81 from '../../../blogPosts/parkour/nastyChallenge/june2023/81.svelte'
    import Day82 from '../../../blogPosts/parkour/nastyChallenge/june2023/82.svelte'
    import Day83 from '../../../blogPosts/parkour/nastyChallenge/june2023/83.svelte'
    import Day84 from '../../../blogPosts/parkour/nastyChallenge/june2023/84.svelte'
</script>

<main class='flex flex-col w-[100vw] text-white'>
    <h1 id='month-header' class='w-full flex text-lg md:text-2xl justify-center items-center bg-red-500 p-10'>
        <span class='p-7 rounded-xl bg-black flex flex-col justify-evenly items-center'>
            <p class='text-red-500'>#NASTY Challenge</p>
            <p class='font-bold'>June 2023</p>
            <DayJumper startDay={60} currentMonth={true}/>
            <a class='text-sm bg-[#92DCE5] text-black p-2' href='/blog'>Back to Blog</a>
        </span>
    </h1>
    <section class='w-full flex flex-col items-center'>
        <Day60 />
        <Day61 />
        <Day62 />
        <Day63 />
        <Day64 />
        <Day65 />
        <Day66 />
        <Day67 />
        <Day68 />
        <Day69 />
        <Day70 />
        <Day71 />
        <Day72 />
        <Day73 />
        <Day74 />
        <Day75 />
        <Day76 />
        <Day77 />
        <Day78 />
        <Day79 />
        <Day80 />
        <Day81 />
        <Day82 />
        <Day83 />
        <Day84 />
    </section>
</main>