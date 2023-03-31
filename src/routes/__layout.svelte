<script lang='ts'>
  import HamburgerMenu from './HamburgerMenu.svelte';
  import "../app.css";
</script>

<header class='flex flex-col bg-black text-white text-lg p-5 justify-center items-center'>
  <HamburgerMenu />
</header>

<slot />