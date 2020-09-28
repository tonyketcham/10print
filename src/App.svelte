<script>
  export let library;
  import Canvas from "./p5/Canvas.svelte";
</script>

<main>
  <header>
    <h1>10print</h1>
  </header>

  <Canvas />
</main>

<style>
  main {
    text-align: center;
    padding: 1em;
    max-width: 240px;
    margin: 0 auto;
  }

  header {
    margin-bottom: 3rem;
  }

  h1 {
    font-size: 3em;
    font-weight: 200;
  }

  @media (min-width: 640px) {
    main {
      max-width: none;
    }
  }
</style>
