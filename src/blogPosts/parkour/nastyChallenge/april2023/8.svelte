<script lang='ts'>
    const dayNum: number = 8
    const date: string ='April 10, 2023'
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
            Today was interesting for a couple of reasons. First of all, right as I was about to leave early to the office this morning, 
            I realized I lost my apartment key over the weekend. So I had to get a new one cut, but had to wait til after 9 to do so. That 
            was fun! The second reason is I didn't feel like eating a whole lot today.
        </p>
        <br />
        <p>
            Normally I'm eating all day but I think the lack of workouts over the weekend made me less hungry. Either way, I kept the same weight 
            from Sunday, and I got my workout & PT in, plus an evening jog. I ate a salad, but I also had some cheese curds at night, but a smaller size, 
            and I shared with Sam. Breakfast was a bacon egg & cheese biscuit, and I sipped on some cold brew and sparkling water throughout the day. 
            Because of the lost key situation, I didn't get into the office til 11, and I was mostly busy with heads-down work or working out in the gym. 
            Not much time to think about snacks, I suppose.
        </p>
        <br />
        <p>
            In addition to the workouts today, I went on a short bike ride as part of my QA work today. It was just for a few minutes, but it probably 
            still counts for something. I didn't think about food much today, and I was able to walk past a basket of miniature Reese's cups without 
            any emotional reaction whatsoever. I think I'm starting to lose interest in sugary foods as a source of comfort. They still sound tasty, but I 
            don't feel like I need them as much, at least not today.
        </p>
    </div>
</section>