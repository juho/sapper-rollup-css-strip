<script context="module">
  export async function preload(page) {
    return;
  }
</script>

<script>
  export let segment;
</script>

<style>
  main {
    position: relative;
    z-index: 1;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
  }
</style>

<main>
  <slot />
</main>
