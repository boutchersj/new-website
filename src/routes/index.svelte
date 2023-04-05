<script>
	import GameCard from "./GameCard.svelte";
</script>
<main class='flex flex-col w-full'>
    <div class='flex flex-col text-lg md:text-2xl justify-center items-center h-full bg-gradient-to-b from-white via-cyan-500 to-white p-10'>
        <p class='flex text-center text-3xl leading-[2] h-full p-10'>
            Nobody knows why we are here,
            <br/>
            and it doesn't matter.
            <br />
            ~
            <br />
            The world is our playground,
            <br />
            and we must learn to play.
            <br />
            ~
            <br />
            If we don't choose our own game,
            <br />
            we will play someone else's game.
            <br />
            ~
            <br />
            These are some of the games I've chosen to play:
        </p>
    </div>
    <section id='tableOfContents' class='text-white flex flex-col w-full justify-evenly items-center'>
        <a class='text-center w-full py-5 hover:bg-cyan-500' href='#videogames'>Video Games</a>
        <a class='text-center w-full py-5 hover:bg-cyan-500' href='#violin'>Violin</a>
        <a class='text-center w-full py-5 hover:bg-cyan-500' href='#spanish'>Spanish</a>
        <a class='text-center w-full py-5 hover:bg-cyan-500' href='#parkour'>Parkour</a>
        <a class='text-center w-full py-5 hover:bg-cyan-500' href='#internationaltravel'>International Travel</a>
        <a class='text-center w-full py-5 hover:bg-cyan-500' href='#webdevelopment'>Web Development</a>
        <a class='text-center w-full py-5 hover:bg-cyan-500' href='#drivingstick'>Driving Stick</a>
        <a class='text-center w-full py-5 hover:bg-cyan-500' href='#softwareqa'>Software QA</a>
        <a class='text-center w-full py-5 hover:bg-cyan-500' href='#husbandhood'>Husbandhood</a>
    </section>
    <GameCard
        title='Video Games'
        line1='Going on simulated adventures in strange lands'
        year={2004}
        line2='#Playstation'
        emoji='🎮'
        accentColor='via-green-300'
    />
    <GameCard
        title='Violin'
        line1='The musical instrument closest to the human voice'
        year={2004}
        line2='Deal with the devil not required to play'
        emoji='🎻'
        accentColor='via-orange-500'
    />
    <GameCard
        title='Spanish'
        line1='Reading, writing, listening, and speaking Castilian Spanish.'
        year={2008}
        line2="I could not roll my R's until 2013"
        emoji='🇪🇸'
        accentColor='via-yellow-500'
    />
    <GameCard
        title='Parkour'
        image='images/parkour_3_16.gif'
        imageAlt='GIF of me doing parkour'
        line1='Creative movement for efficient navigation'
        year={2010}
        line2='Bring out your inner monkey'
        emoji='🐒'
        accentColor='via-red-500'
        blogEndpoint='/blog'
    />
    <GameCard
        title='International Travel'
        image='images/sevilla_alcazar.png'
        imageAlt='Sam and I standing next at a gate in the Royal Alcazar of Sevilla'
        line1='Experiencing as much of the world as possible'
        year={2016}
        line2='One misadventure at a time'
        emoji='🌍'
        accentColor='via-green-700 via-blue-800'
    />
    <GameCard
        title='Web Development'
        line1='Making magic documents on the internet'
        year={2017}
        line2='*ahem* *points at this website*'
        emoji='🖥️'
        accentColor='via-purple-500'
    />
    <GameCard
        title='Driving Stick'
        line1="It's like regular driving but more vroom vroom"
        year={2019}
        line2='Only 18% of Americans can drive stick'
        emoji='🕹️'
        accentColor='via-red-300'
    />
    <GameCard
        title='Software QA'
        line1='Testing apps, websites, APIs, etc.'
        year={2020}
        line2='also, automating those tests'
        emoji='🧪🤖'
        accentColor='via-green-500'
    />
    <GameCard
        title='Husbandhood'
        image='images/wedding_forest.png'
        imageAlt='wedding photo of me and Sam in an autumn forest'
        line1='Being married to my best friend!'
        year={2021}
        line2='My heart grew 3 sizes that day'
        emoji='❤️❤️❤️'
        accentColor='via-pink-500'
    />
</main>