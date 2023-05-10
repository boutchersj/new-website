<script lang='ts'>
    const dayNum: number = 14
    const date: string ='April 16, 2023'
    const weighIn: number = 230.8
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
            Well, I didn't end up working out at all over the weekend. I haven't done any PT or exercise since Tuesday. I've been 
            in a weird mood overall. Sleep schedule's been all over the place, and that mountain bike incident last Wednesday threw me 
            off my game. That and some other intersecting stressors made me not want to go outside much this weekend. So here I am. I'm pretty 
            sure that, along with some fast food burgers I've had this weekend, is why I'm putting on weight again.
        </p>
        <br />
        <p>
            That said, I'm still going strong on the no added sugar front. I do need to eat more vegetables, though. I bought a kale & tomato salad 
            from the deli today, ate some, saving most of it for tomorrow because there's a good chance I'll be working from home again if I'm able to. 
            I'm going to start tracking my calories again starting tomorrow. It's been 2 full weeks and I don't think my stress is coming from avoiding sugar 
            anymore. It's important that I know how much I'm eating against my daily calorie goal. For all I know, I could be in a surplus when I think I'm in a 
            deficit and vice versa.
        </p>
        <br />
        <p>
            As far as what I ate today, I had a double Culver's deluxe cheeseburger for lunch. I didn't eat breakfast because I woke up at 10:30. For dinner, I 
            had half a frozen pizza and some fried pickle chips. So overall, not the healthiest day, and I had some brain fog toward the end of the day which was 
            probably caused by the food. When Sam and I went to the movies I had a sugar-free soda which probably had not-great artificial sweeteners in it. Folks, 
            there's a right and a wrong way to eat no added sugar and I didn't do it right today. I'll do better tomorrow.
        </p>
    </div>
</section>