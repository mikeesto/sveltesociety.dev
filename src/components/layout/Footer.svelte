<script>
  // get the year for the copyright statement
  var date = new Date();
  var year = date.getFullYear();
</script>

<footer class="shaded">
  <div>&copy; Svelte Society {year}</div>

  <div>
    Want to contribute? Pick up an issue on
    <a
      class="ghlink"
      href="https://github.com/svelte-society/sveltesociety.dev"
      target="_blank"
      rel="noopener">GitHub</a
    >!
  </div>
</footer>

<style>
  .shaded {
    max-width: 100%;
    background: #f3f6f9;
  }

  a {
    color: black;
    font-size: 19px;
  }

  footer {
    display: flex;
    justify-content: space-between;
    max-width: unset;
    padding: 3em;
  }

  @media only screen and (max-width: 768px) {
    footer {
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      max-width: unset;
      padding: 2em;
      font-size: 15px;
    }

    a.ghlink {
      font-size: 15px;
    }
  }
</style>
