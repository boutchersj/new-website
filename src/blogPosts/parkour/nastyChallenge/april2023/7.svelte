<script lang='ts'>
    const dayNum: number = 7
    const date: string ='April 9, 2023'
    const weighIn: number = 236.6
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
            Today was pretty hard. I had to say no to a great gift from Sam's sister because of this 
            challenge. She was understanding about it, but I love gummi peach rings and she got me 2 bags 
            of them for Easter. I guess if you don't have to make hard choices, it isn't really a challenge, 
            is it?
        </p>
        <br />
        <p>
            Other than that, I've been happily eating the snacks I got myself from Target the other day. Sam and I 
            ordered Pizza Hut for dinner and we chose a <a target='_blank' class='text-cyan-500' href='https://www.nutritionix.com/i/pizza-hut/super-supreme-large-original-pan-slice/23cb6838729fc48d4e4397c5'>
            Supreme</a> and some <a target='_blank' class='text-cyan-500' href='https://www.nutritionix.com/i/pizza-hut/breadsticks/23cb59550d24c2d85219268d'>breadsticks</a>. 
            There's admittedly some sugar in those but it's like 10g altogether, which is minuscule considering how many calories they are 
            overall.
        </p>
        <br />
        <p>
            Tomorrow's back to the work week, which means my workouts start up again. It'll be interesting to see if 
            I drop below 233 by the end of the week or if I keep the small gains I've made instead. First week down, only 
            51 more to go! I'm proud I've made it this far already. Hasn't felt like a week. Benefits of being almost 30, I 
            suppose. As we age, time seems to go faster. Makes it easier to stick to stuff like this, I think.
        </p>
    </div>
</section> 