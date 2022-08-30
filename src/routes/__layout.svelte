<script>
  import "../app.css";
</script>

<nav class="flex w-full justify-evenly text-yellow-300 border border-x-0 border-t-0 border-b-white pb-5">
  <a href="/">About Me</a>
  <a href="/education">Education</a>
  <a href="/portfolio">Portfolio</a>
</nav>

<header class="flex flex-col items-center my-5">
  <h1 class="text-4xl mb-2">Steven Boutcher</h1>
  <h2 class="text-xl">Explorer | Builder | Educator</h2>
</header>

<slot />

<footer class="flex flex-row w-full justify-evenly text-yellow-300 pt-5 border border-x-0 border-b-0 border-t-white">
  <a target="_blank" rel="noopener noreferrer" href="https://www.github.com/boutchersj">
      GitHub
  </a>
  <a target="_blank" rel="noopener noreferrer" href="https://www.linkedin.com/in/boutchersj">
      LinkedIn
  </a>
</footer>