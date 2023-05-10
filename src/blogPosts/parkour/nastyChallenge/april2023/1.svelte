<script lang='ts'>
    const dayNum: number = 1
    const date: string ='April 3, 2023'
    const weighIn: number = 238
</script>

<section class='my-10 w-[90%] border p-5 rounded-xl md:w-[50%]'>
    <div class='w-full text-3xl lg:text-3xl text-red-500 mb-5 flex flex-col justify-evenly items-center text-center'>
        <h2 id={`day${dayNum}`}>Day {dayNum}</h2>
    </div>
    <p class='flex flex-col w-full items-center justify-between text-sm text-red-500 mb-5'>
        {date}
    </p>
    <p class='flex flex-col w-full items-center justify-between text-sm text-red-500 mb-5'>
        Weigh-in: {weighIn} lbs.
    </p>

    <br />

    <div>
        <p>
            Today was a little <i>too</i> easy. I'm not sure, maybe it's the initial burst of motivation 
            that always comes with a new challenge! But I didn't have to work hard at all to eat the right foods and 
            I had tons of energy!
        </p>
    </div>
</section>