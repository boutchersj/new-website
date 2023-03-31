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
    <GameCard 
        title='Violin'
        line1='The musical instrument closest to the human voice'
        year={2004}
        line2='Deal with the devil not required to play'
        emoji='🎻'
        accentColor='orange-500'
    />
    <GameCard
        title='Parkour'
        gif='images/parkour_3_16.gif'
        gifAlt='GIF of me doing parkour'
        line1='Creative movement for efficient navigation'
        year={2010}
        line2='Bring out your inner monkey'
        emoji='🐒'
        accentColor='red-500'
    />
    <GameCard
        title='Web Development'
        line1='Making magic documents on the internet'
        year={2017}
        line2='*ahem* *points at this website*'
        emoji='🖥️'
        accentColor='purple-500'
    />
    <GameCard
        title='Software QA'
        line1='Testing apps, websites, APIs, etc.'
        year={2020}
        line2='also, automating those tests'
        emoji='🧪🤖'
        accentColor='green-500'
    />
    <GameCard
        title='Husbandhood'
        line1='Being married to my best friend!'
        year={2021}
        line2='My heart grew 3 sizes that day'
        emoji='❤️❤️❤️'
        accentColor='pink-500'
    />
</main>