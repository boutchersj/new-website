<script lang='ts'>
  import HamburgerMenu from '$lib/HamburgerMenu.svelte';
</script>

<header class='sticky top-0 opacity-90 flex flex-col bg-black text-white text-lg p-5 justify-center items-center'>
  <HamburgerMenu />
</header>

<slot />