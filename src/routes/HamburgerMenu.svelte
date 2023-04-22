<script lang='ts'>
    function toggleMenu() {
        const isMenuHidden = document.getElementById('nav-menu')?.classList.contains('hidden')
        if (isMenuHidden) {
        document.getElementById('nav-menu')?.classList.remove('hidden')
        }
        else {
        document.getElementById('nav-menu')?.classList.add('hidden')
        }
    }
</script>

<nav class='flex justify-between items-center w-full'>
    <a href='/'>
        <h1 class='text-3xl'>
            Steven Boutcher
        </h1>
    </a>
    <button role='switch' on:click={toggleMenu} class='p-5 hover:bg-cyan-500 rounded-xl w-16'>
        <img src='images/hamburger.png' alt='hamburger menu icon'/>
    </button>
</nav>
<div id='nav-menu' class='hidden h-[100vh] flex flex-col justify-start items-center'>
    <a on:click={toggleMenu} class='flex items-center justify-center w-[100vw] h-[20%] hover:bg-cyan-500' href="/">Home</a>
    <a on:click={toggleMenu} target='_blank' class='flex justify-center items-center w-[100vw] h-[20%] hover:bg-cyan-500' href="https://linktr.ee/stevenboutcher">Contact</a>
    <a on:click={toggleMenu} target='_blank' class='flex justify-center items-center w-[100vw] h-[20%] hover:bg-cyan-500' href="https://stevenboutcher.gumroad.com/">Shop</a>
</div>