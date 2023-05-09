<script>
    import Hero from '$lib/Hero.svelte'
	import GameCard from "$lib/GameCard.svelte";
    import '../app.css'
</script>

<main class='flex flex-col w-full'>
    <Hero />
    <h1 class='flex justify-center text-3xl text-white mb-5'><span class='text-[#92DCE5]'>Journeys&nbsp;</span>& Side Quests</h1>
    <section id='lifeGrid' class='grid grid-cols-1 md:grid-cols-2 xl:grid-cols-3 gap-8 text-white w-full justify-center px-5'>
        <GameCard
            title='Parkour'
            image='/parkour_3_16.gif'
            imageAlt='GIF of me doing parkour'
            line1='Creative movement for efficient navigation'
            year={2010}
            line2='Bring out your inner monkey'
            emoji='🐒'
            blogEndpoint='blog'
        />
        <GameCard
            title='Software QA'
            image='/softwaretesting.jpeg'
            imageAlt='stock image representing software testing'
            line1='Testing apps, websites, APIs, etc.'
            year={2020}
            line2='also, automating those tests'
            emoji='🧪🤖'
            subdomain='blog'
        />
        <GameCard
            title='Web Development'
            image='/webdevelopment.jpeg'
            imageAlt='stock image of a laptop screen with HTML/CSS/JavaScript code and the word JavaScript overlaying it'
            line1='Making magic documents on the internet'
            year={2017}
            line2='*ahem* *points at this website*'
            emoji='🖥️'
        />
        <GameCard
            title='International Travel'
            image='/sevilla_alcazar.png'
            imageAlt='Sam and I standing next at a gate in the Royal Alcazar of Sevilla'
            line1='Experiencing as much of the world as possible'
            year={2016}
            line2='One misadventure at a time'
            emoji='🌍'
        />
        <GameCard
            title='Husbandhood'
            image='/wedding_forest.png'
            imageAlt='wedding photo of me and Sam in an autumn forest'
            line1='Being married to my best friend!'
            year={2021}
            line2='My heart grew 3 sizes that day'
            emoji='❤️❤️❤️'
        />
        <GameCard
            title='Video Games'
            image='/spiderman2Game.png'
            imageAlt='the start screen for my favorite video game, Spiderman 2'
            line1='Going on simulated adventures in strange lands'
            year={2004}
            line2='#Playstation'
            emoji='🎮'
        />
        <GameCard
            title='Violin'
            image='/violin.jpeg'
            imageAlt='a violin'
            line1='The musical instrument closest to the human voice'
            year={2004}
            line2='Deal with the devil not required to play'
            emoji='🎻'
        />
        <GameCard
            title='Spanish'
            image='/sevilla.jpeg'
            imageAlt='A view from the setas in Sevilla of the city at night'
            line1='Reading, writing, listening, and speaking Castilian Spanish.'
            year={2008}
            line2="I could not roll my R's until 2013"
            emoji='🇪🇸'
        />
        <GameCard
            title='Driving Stick'
            image='/stickshift.jpeg'
            imageAlt='manual transmission gear shift'
            line1="It's like regular driving but more vroom vroom"
            year={2019}
            line2='Only 18% of Americans can drive stick'
            emoji='🕹️'
        />
    </section>
</main>