<script lang='ts'>
    const dayNum: number = 3
    const date: string ='April 5, 2023'
    const weighIn: number = 234.6
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
            Today I started to notice more cravings. I went to Woodman's in the morning to get some raspberries and sugar-free gummi worms. 
            During the work day, I didn't have as many veggies or as much water as I could've, and I ate at least 1 more food item than I normally 
            would've on a typical day. I also had Culver's after work, but no sweets, just chicken tenders and cheese curds. I had to miss out on 
            the honey mustard cup I got with it because after looking up the nutrition facts, I learned that it had 18g of sugar, which is absurd to me.
        </p>
        <br />
        <p>
            I noticed I had more energy than usual again, too. I played a couple's card game called Let's Get Deeper and a few rounds of Song Quiz on Alexa. 
            I didn't feel tired playing with the cats at night with her, either. I was able to have a philosophical conversation with her at length during the 
            card game that I normally wouldn't have been emotionally stable nor focused enough to have. I have to wonder if removing excess sugar has made me less 
            moody, too.
        </p>
    </div>
</section>