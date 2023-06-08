<script lang='ts'>
    export let title: string;
    export let image: string='';
    export let imageAlt: string='';
    export let line1: string;
    export let year: number;
    export let line2: string;
    export let emoji: string;
    export let blogEndpoint: string='';
    export let subdomain: string='';

    const containerStyles: string = `flex flex-col items-center p-10 border border-white border-8 rounded-xl`
    const imageStyles: string = `w-full md:w-[50%] border border-white rounded-xl border-opacity-0 m-10`
</script>

<div id={`${title.toLowerCase().replace(' ','')}`} class={containerStyles}>
    <h3 class='w-full text-center mb-5 text-xl font-bold'>{title}</h3>
    {#if image && imageAlt}
        <img class={imageStyles} src={image} alt={imageAlt} />
    {/if}
    <p class='w-full text-center'>{line1}</p>
    <p class='w-full text-center py-5'>- since {year} -</p>
    <p class='w-full text-center'>{line2}</p>
    <div class='w-full flex justify-center py-10'>
        <p class='w-[25%] text-center scale-[2]'>{emoji}</p>
    </div>
    {#if blogEndpoint}
    <a href={`/${blogEndpoint}`} class='bg-[#92DCE5] text-black rounded-xl px-5 py-3 mb-5'>Read Blog</a>
    {:else if subdomain}
    <a id={`${title}-blog`} href={`https://${subdomain}.stevenboutcher.com`} target='_blank' class='bg-[#92DCE5] text-black rounded-xl px-5 py-3 mb-5'>Read Blog</a>
    {/if}
</div>