<h1>Welcome to SvelteKit</h1>

<style>
  @custom-media --small-viewport (max-width: 30em);

  h1 {
    color: blue;

    &:hover {
      color: red;
    }

    @media (--small-viewport) {
      color: green;
    }
  }

</style>
