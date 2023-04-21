<script>
    import BlogPost from '../BlogPost.svelte'
</script>

<BlogPost dayNum={18} date='April 20, 2023' weighIn={230.6}>
    <div slot='content'>
        <p>
            I'm just going to let no news be good news at this point. I don't think I need to announce 
            every day that I've gone another day without added sugar. I think it's a given at this point! So, 
            unless I say otherwise, let's assume that's the case.
        </p>
        <br />
        <p>
            I took an InBody scan today and apparently, I've lost 12 pounds of fat without losing any muscle! I even 
            gained a little bit of it. My nutritionist says it's because of this no-added-sugar journey, and how it's been 
            able to bring down my inflammation and allow fat to be released now that my body isn't producing so much insulin 
            anymore. I thought it'd be cool to show the InBody from February and the InBody from today in the same post here.
        </p>
        <h3 class='text-2xl my-5'>February 27, 2023</h3>
        <img src='images/InBody_2_27_2023.jpeg' alt='InBody results from February' />
        <h3 class='text-2xl my-5'>Today</h3>
        <img src='images/InBody_4_20_2023.jpeg' alt='InBody results from today' />
        <br />
        <p>
            After work, I went rock climbing at the local climbing gym. Followed that up with a high-protein dinner. I didn't 
            do any other exercise except some casual parkour vaulting work during the workday in the Trek gym over some blocks. The 
            weight's stayed constant at 230.6 lbs. Not a bad place to be, considering I was once 25 lbs. heavier than this almost a year 
            ago!
        </p>
        <br />
        <p>
            On a final note, a buddy of mine I hadn't seen since before I started this challenge told me my face looked slimmer after I told him 
            about the challenge I've been doing. And you know what? I agree with him!
        </p>
        <img class='mt-5' src='images/me_4_20.jpeg' alt='selfie while walking outside Target' />
    </div>
</BlogPost>