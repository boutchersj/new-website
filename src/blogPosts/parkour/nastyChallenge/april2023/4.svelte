<script lang='ts'>
    const dayNum: number = 4
    const date: string ='April 6, 2023'
    const weighIn: number = 236
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
            I've taken to eating bread & butter as a snack and that might be influencing my weigh-in a bit. 
            I realized I'm going to need to start having some high-protein snacks and no-cook options in the house now 
            that I can't just go out and get a sugary snack whenever I want, and most of the fast food options I crave are now 
            things I can't have. Oof.
        </p>
        <br />
        <p>
            I had some veggies at work today so that helped, but I think the extra mile in the morning really kicks up my appetite 
            and unless I eat high-protein or high-fiber options all day, I end up eating myself into a surplus. As far as staying away from 
            sugar goes, I think it's still pretty easy to do. I haven't had too many sources of temptation. One thing I noticed that's replacing 
            the sugary foods is running to get fried fast foods like cheese curds or chicken nuggets. Those aren't great, either. 
            I may need to start meal-prepping to make sure my snacks are better quality.
        </p>
    </div>
</section>