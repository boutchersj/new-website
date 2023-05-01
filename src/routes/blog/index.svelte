<script>
    import '../../app.css'
    import BlogIntro from './BlogIntro.svelte'
    import Day29 from '../../blogPosts/parkour/29.svelte'
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
        <Day29 />
    </section>
</main>