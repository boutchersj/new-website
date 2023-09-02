<script>
    import '../../../app.css'
    import MonthHeader from '$lib/MonthHeader.svelte'
    import Day152 from '../../../blogPosts/parkour/nastyChallenge/september2023/152.svelte'
    // import Day153 from '../../../blogPosts/parkour/nastyChallenge/september2023/153.svelte'
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
        <!-- <Day153 /> -->
    </section>
</main>