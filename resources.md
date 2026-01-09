<style>
  /* --- Global site-wide nav (CV · About · Links & resources) --- */
  .site-nav {
    position: sticky;
    top: 0;
    background: white;
    padding: 0.5rem 0;
    border-bottom: 1px solid #ddd;
    z-index: 2000;
  }

  .site-nav a {
    margin-right: 0.4rem;
  }

  /* --- Page-specific sticky nav (sections within the page) --- */
  .page-nav {
    position: sticky;
    top: 2.4rem; /* roughly the height of the site-nav; tweak if needed */
    background: white;
    padding: 0.4rem 0;
    border-bottom: 1px solid #eee;
    z-index: 1500;
  }

  .page-nav a {
    margin-right: 0.4rem;
  }

  /* Smooth scrolling */
  html {
    scroll-behavior: smooth;
  }

  /* Offset anchored headings so they appear below both nav bars */
  h2[id],
  h3[id] {
    scroll-margin-top: 126px; /* adjust if combined nav height changes */
  }
</style>

<nav class="site-nav">
  My pages:
  <a href="/about">About</a> ·
  <a href="/resources">Resources</a> .
  <a href="/index">CV</a>
</nav>

<nav class="page-nav">
  Resources menu:
   <a href="#websites">Websites</a> ·
  <a href="#podcasts">Podcasts</a> ·
  <a href="#books">Books</a> ·
  <a href="#essays">Notes & essays</a>
</nav>

# Resources

A collection of links to resources I find useful or interesting.

---

## Websites {#websites}

- ...

## Podcasts {#podcasts}

- ...

## Books {#books}

- ...

## Notes & essays {#essays}

- ...
