<script lang='ts'>
    const dayNum: number = 12
    const date: string ='April 14, 2023'
    const weighIn: number = 233
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
            Another success! I worked from home again today, which meant no salad because I haven't bought any yet. 
            I didn't work out either, just to make sure my knee had another day to rest up. I'm going to get 
            back to PT over the weekend, just to keep the tendon engaged.
        </p>
        <br />
        <p>
            Mostly Rx bars, cottage cheese, and a double cheeseburger from Mooyah. I admit I probably should've had more food than that, but I had 
            coffee and just wasn't very hungry most of the day. Almost 2 weeks now with this challenge and it feels like at 
            this point, avoiding sugar is becoming a natural choice and no longer an emotional struggle. I literally sat down the couch 
            from Sam's box of Girl Scout cookies and felt nothing. I effortlessly ignored the box of cookies. It's kinda wild.
        </p>
    </div>
</section>