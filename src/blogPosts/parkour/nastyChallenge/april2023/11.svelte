<script lang='ts'>
    const dayNum: number = 11
    const date: string ='April 13, 2023'
    const weighIn: number = 233.4
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
            Today went pretty well! Still holding the streak. Only thing is I didn't do any exercise. Reason being, 
            I didn't want to risk aggravating my knee which was inflamed yesterday from a hard landing. It felt better by the 
            end of the day, but I'm sure another night's rest will help it out even more.
        </p>
        <br />
        <p>
            The only not-great food choice I made was getting chicken strips & ched'r peppers from Sonic for a post-dinner 
            snack. But the rest of the day, it was the healthy no-sugar-added snacks I've been eating the past few days. I worked from 
            home, so no salad, but I did try rice cakes with a cottage cheese & cream cheese blend, and it was stellar. I definitely 
            love that I can have the creaminess of cream cheese + the protein of cottage cheese.
        </p>
    </div>
</section>