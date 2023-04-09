<script>
    import BlogIntro from './BlogIntro.svelte'
    import Day1 from './posts/1.svelte'
    import Day2 from './posts/2.svelte'
    import Day3 from './posts/3.svelte'
    import Day4 from './posts/4.svelte'
    import Day5 from './posts/5.svelte'
    import Day6 from './posts/6.svelte'
    import Day7 from './posts/7.svelte'
</script>

<main class='flex flex-col w-[100vw] text-white'>
    <h1 class='w-full flex text-lg md:text-2xl justify-center items-center h-48 bg-red-500 p-10'>
        <span class='p-7 rounded-xl bg-black flex justify-center items-center'>
            <span class='text-4xl mr-5'>🐒</span>
            My Monkey Life
            <span class='text-4xl ml-5'>🐒</span>
        </span>
    </h1>
    <section class='w-full flex flex-col items-center'>
        <BlogIntro />
        <Day1 />
        <Day2 />
        <Day3 />
        <Day4 />
        <Day5 />
        <Day6 />
        <Day7 />
    </section>
</main>