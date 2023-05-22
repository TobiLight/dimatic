<script lang="ts">
  import "../app.css";
  import "@fontsource-variable/inter";

</script>

<svelte:head>
  <title>Digitimatic</title>
  <meta name="description" content="This is an example of a
meta description. This will often show up in search results.">
</svelte:head>

<main class="min-h-screen py-8 px-4 md:w-2/3 md:mx-auto">
    <slot />
</main>

<style lang="postcss">
  :global(body) {
    font-family: "Open Sans Variable", sans-serif;
  }
  
  
  main {
    font-family: 'Inter Variable', sans-serif;
    font-display: swap;
  }

</style>