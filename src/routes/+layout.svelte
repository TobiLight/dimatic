<script lang="ts">
  import "../app.css";
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
  @import url('https://fonts.googleapis.com/css2?family=Inter:wght@500&display=swap');

  main {
    font-family: 'Inter', sans-serif;
  }

</style>