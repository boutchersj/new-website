<script lang='ts'>
    export let title: string;
    export let image: string='';
    export let imageAlt: string='';
    export let line1: string;
    export let year: number;
    export let line2: string;
    export let emoji: string;
    export let accentColor: string;
    export let blogEndpoint: string='';

    const containerStyles: string = `flex flex-col text-lg md:text-2xl justify-center items-center h-full bg-gradient-to-b from-white ${accentColor} to-white p-10`
    const imageStyles: string = `w-full md:w-[50%] border border-white rounded-xl border-opacity-0 m-10`
</script>

<div id={`${title.toLowerCase().replace(' ','')}`} class={containerStyles}>
    <h3 class='text-2xl md:text-4xl w-full text-center mb-5'>{title}</h3>
    {#if image && imageAlt}
        <img class={imageStyles} src={image} alt={imageAlt} />
    {/if}
    <p class='w-full text-center'>{line1}</p>
    <p class='w-full text-md md:text-xl text-center py-5'>- since {year} -</p>
    <p class='w-full text-center'>{line2}</p>
    <div class='w-full flex justify-center py-10'>
        <p class='w-[25%] text-center scale-[2]'>{emoji}</p>
    </div>
    {#if blogEndpoint}
    <a href={blogEndpoint} target='_blank' class='bg-green-500 rounded-xl px-5 py-3 mb-5'>Read Blog</a>
    {/if}
    <a href='#tableOfContents'>Back to top ⬆️</a>
</div>