<script>
  import "../app.css";
</script>

<header class='flex justify-between bg-black text-white h-16 text-lg p-5 justify-center items-center'>
  <h1 class='text-3xl'>Steven Boutcher</h1>
  <nav class='underline flex w-[30%] justify-between'>
    <a target='_blank' class='hover:text-cyan-500' href="https://www.youtube.com/channel/UC3FmOiyig5g5J1MtJHj9XtQ">YouTube</a>
    <a target='_blank' class='hover:text-cyan-500' href="https://blog.stevenboutcher.com">Blog</a>
    <a target='_blank' class='hover:text-cyan-500' href="https://www.linkedin.com/in/boutchersj">LinkedIn</a>
    <a target='_blank' class='hover:text-cyan-500' href="https://www.twitter.com/StevenBoutcher">Twitter</a>
  </nav>
</header>

<slot />