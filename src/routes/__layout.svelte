<script lang="ts">
  import "../app.css";
  function toggleMenu(event: Event) {
    const { target } = event
    const isMenuHidden = document.getElementById('nav-menu')?.classList.contains('hidden')
    if (isMenuHidden) {
      document.getElementById('nav-menu')?.classList.remove('hidden')
    }
    else {
      document.getElementById('nav-menu')?.classList.add('hidden')
    }
  }
</script>

<header class='flex flex-col bg-black text-white text-lg p-5 justify-center items-center'>
  <nav class='flex justify-between items-center w-full'>
    <h1 class='text-3xl'>Steven Boutcher</h1>
    <button role='switch' on:click={toggleMenu} class='p-5 hover:bg-cyan-500 rounded-xl w-16'><img src='images/hamburger.png' alt='hamburger menu icon'/></button>
  </nav>
  <div id='nav-menu' class='hidden h-[100vh] flex flex-col justify-start items-center'>
    <a target='_blank' class='flex items-center justify-center w-[100vw] h-[25%] hover:bg-cyan-500' href="https://www.youtube.com/channel/UC3FmOiyig5g5J1MtJHj9XtQ">YouTube</a>
    <a target='_blank' class='flex justify-center items-center w-[100vw] h-[25%] hover:bg-cyan-500' href="https://blog.stevenboutcher.com">Blog</a>
    <a target='_blank' class='flex justify-center items-center w-[100vw] h-[25%] hover:bg-cyan-500' href="https://www.linkedin.com/in/boutchersj">LinkedIn</a>
    <a target='_blank' class='flex justify-center items-center w-[100vw] h-[25%] hover:bg-cyan-500' href="https://www.twitter.com/StevenBoutcher">Twitter</a>
</div>
</header>

<slot />