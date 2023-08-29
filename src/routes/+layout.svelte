<script>
  import "../app.css";
</script>

<slot />

<style lang="postcss">
  :global(html) {
    background-color: theme(colors.slate.800);
    color: theme(colors.slate.100);
  }

  :global(a) {
    color: theme(colors.teal.300);
  }

  :global(a:hover) {
    color: theme(colors.teal.500);
  }

  :global(h1) {
    font-size: 3rem;
  }

  :global(h2) {
    font-size: 1.875rem;
  }

  :global(h3) {
    font-size: 1.5rem;
  }

  :global(h4) {
    font-size: 1.25rem;
  }
</style>