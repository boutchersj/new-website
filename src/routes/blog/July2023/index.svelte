<script>
    import '../../../app.css'
    import MonthHeader from '$lib/MonthHeader.svelte'
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
    import Day100 from '../../../blogPosts/parkour/nastyChallenge/july2023/100.svelte'
    import Day101 from '../../../blogPosts/parkour/nastyChallenge/july2023/101.svelte'
    import Day102 from '../../../blogPosts/parkour/nastyChallenge/july2023/102.svelte'
</script>

<main class='flex flex-col w-[100vw] text-white'>
    <MonthHeader
        month='July'
        year={2023}
        startDay={90}
        currentMonth={true}
    />
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
        <Day100 />
        <Day101 />
        <Day102 />
    </section>
</main>