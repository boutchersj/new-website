<script lang='ts'>
    export let dayNum: number;
    export let date: string;
    export let weighIn: number;
</script>

<section class='m-20'>
    <div class='w-full text-3xl lg:text-3xl text-red-500 mb-5 flex flex-col justify-evenly items-center text-center'>
        <h2>Day {dayNum}</h2>
    </div>
    <p class='flex flex-col w-full items-center justify-between text-sm text-red-500 mb-5'>
        {date}
    </p>
    <p class='flex flex-col w-full items-center justify-between text-sm text-red-500 mb-5'>
        Weigh-in: {weighIn} lbs.
    </p>
    <br />

    <slot name='content' />
    <br />
</section>