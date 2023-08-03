<script>
    import '../../../app.css'
    import MonthHeader from '$lib/MonthHeader.svelte'
    import Day121 from '../../../blogPosts/parkour/nastyChallenge/august2023/121.svelte'
    import Day122 from '../../../blogPosts/parkour/nastyChallenge/august2023/122.svelte'
    // import Day123 from '../../../blogPosts/parkour/nastyChallenge/august2023/123.svelte'
</script>

<main class='flex flex-col w-[100vw] text-white'>
    <MonthHeader
        month='August'
        year={2023}
        startDay={121}
        currentMonth={true}
    />
    <section class='w-full flex flex-col items-center'>
        <Day121 />
        <Day122 />
        <!-- <Day123 /> -->
    </section>
</main>