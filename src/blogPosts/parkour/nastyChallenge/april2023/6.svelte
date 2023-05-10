<script lang='ts'>
    const dayNum: number = 6
    const date: string ='April 8, 2023'
    const weighIn: number = 236.2
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
            I'm still not tracking my calories, but eating more of the snacks I bought hasn't 
            seemed to stop me from eating a lot of food every day. Not sure what to do about that except 
            space my meals out and not give myself free license to snack every hour of the day. Once I get 
            comfortable with sugary food not being an option, I'll go back to tracking my macros. I'll probably 
            start up again on Day 15 so I know it's been 2 weeks, which is always the hardest time period.
        </p>
        <br />
        <p>
            I will say, though, that saying no to sugary snacks feels like it might be getting easier. I can tell 
            there's still a nagging craving for it, but I'm starting to get back some control over it. When Sam and I 
            went to the art museum today, I said no to a sugary coffee drink and bought a plain latte instead. We also went 
            for pizza beforehand and I chose boxed water instead of a can of soda. I'm starting to notice how many opportunities 
            there normally are to buy sugary food for convenience because I'm having to find a sugar-free alternative in each instance. 
            It's sort of eye-opening!
        </p>
    </div>
</section> 