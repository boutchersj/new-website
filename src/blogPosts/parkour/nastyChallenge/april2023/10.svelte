<script lang='ts'>
    const dayNum: number = 10
    const date: string ='April 12, 2023'
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
            I went jogging in the morning and ate well all day! No surprise there. I also went for a mountain bike 
            ride on my lunch on the Trek trails -- by myself! It was another great cardio workout. It was my rest day 
            for my strength workouts, so that's all I did for exercise. I had some Rx bars, no-sugar high-protein cereal, 
            and a salad during the day. Also some cottage cheese.
        </p>
        <br />
        <p>
            I did happen to have a small crash on my mountain bike while out on the trails, and I was forced to choose between falling 
            with my bike or jumping into a parkour roll away from my bike, and I chose the latter. I ended up taking a lesser portion of the 
            fall impact on my bad knee, which inflamed it for the rest of the day. Spoiler alert: the next morning, it was back to normal. 
            Still, that was a bummer. Kinda felt cool to save my bacon with a parkour move, though. It's not the first time!
        </p>
        <br />
        <p>
            This drop down to 233 is the most progress I've made since starting the blog! A whole 5 pounds lost in the first 10 days of this 
            challenge. I'm excited to see if the trend & velocity continues along the same lines.
        </p>
    </div>
</section>