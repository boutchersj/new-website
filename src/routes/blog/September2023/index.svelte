<script>
    import '../../../app.css'
    import MonthHeader from '$lib/MonthHeader.svelte'
    import Day152 from '../../../blogPosts/parkour/nastyChallenge/september2023/152.svelte'
    import Day153 from '../../../blogPosts/parkour/nastyChallenge/september2023/153.svelte'
    import Day154 from '../../../blogPosts/parkour/nastyChallenge/september2023/154.svelte'
    import Day155 from '../../../blogPosts/parkour/nastyChallenge/september2023/155.svelte'
    import Day156 from '../../../blogPosts/parkour/nastyChallenge/september2023/156.svelte'
    import Day157 from '../../../blogPosts/parkour/nastyChallenge/september2023/157.svelte'
    // import Day158 from '../../../blogPosts/parkour/nastyChallenge/september2023/158.svelte'
</script>

<main class='flex flex-col w-[100vw] text-white'>
    <MonthHeader
        month='September'
        year={2023}
        startDay={152}
        currentMonth={true}
    />
    <section class='w-full flex flex-col items-center'>
        <Day152 />
        <Day153 />
        <Day154 />
        <Day155 />
        <Day156 />
        <Day157 />
        <!-- <Day158 /> -->
    </section>
</main>