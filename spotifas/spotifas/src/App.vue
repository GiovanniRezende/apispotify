<template>
  <div class="container">
    <header class="blog-header lh-1 py-3">
      <div class="row flex-nowrap justify-content-between align-items-center">
        <div class="col-4 pt-1">
          <a class="link-secondary" href="#">Subscribe</a>
        </div>
        <div class="col-4 text-center">
          <a class="blog-header-logo text-dark" href="#">Spotifas</a>
        </div>
        <div class="col-4 d-flex justify-content-end align-items-center">
          <a class="link-secondary" href="#" aria-label="Search">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="20"
              height="20"
              fill="none"
              stroke="currentColor"
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              class="mx-3"
              role="img"
              viewBox="0 0 24 24"
            >
              <title>Search</title>
              <circle cx="10.5" cy="10.5" r="7.5" />
              <path d="M21 21l-5.2-5.2" />
            </svg>
          </a>
          <a class="btn btn-sm btn-outline-secondary" href="#">Sign up</a>
        </div>
      </div>
    </header>
  </div>

  <main class="container">
    <img src="images/blackmetalbanner.jpg" class="img-fluid">
    <div class="p-4 p-md-5 mb-4 rounded text-bg-dark">
      <div class="col-md-6 px-0">
        <h1 class="display-4 fst-italic">Black Metal Blog</h1>
        <p class="lead my-3">This is the greatest black metal blog</p>

        <p class="lead mb-0">
          <a href="#" class="text-white fw-bold">Continue reading...</a>
        </p>
      </div>
    </div>
    
    


    <div class="row mb-2">
      <div class="col-md-6">
        <div
          class="row g-0 border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative"
        >
          <div class="col p-4 d-flex flex-column position-static">
            <strong class="d-inline-block mb-2 text-primary"
              >Recommended Bands</strong
            >
            <h3 class="mb-0">CANNIBAL CORPSE</h3>
            
            <div class="mb-1 text-muted">Nov 12</div>
            <p class="card-text mb-auto">
              ITS A DEATHMETAL BAND
            </p>
            <a href="#" class="stretched-link">Continue reading</a>
          </div>
          <div class="col-auto d-none d-lg-block">
            <img src="images/canniballogo.jpeg" class="img-thumbnail">
            
            
          </div>
        </div>
      </div>
     
        </div>
        <div class="row mb-2">
      <div class="col-md-6">
        <div
          class="row g-0 border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative"
        >
          <div class="col p-4 d-flex flex-column position-static">
            <strong class="d-inline-block mb-2 text-primary"
              >Recommended Bands</strong
            >
            <h3 class="mb-0">Darkthrone</h3>
            <div class="mb-1 text-muted">Nov 12</div>
            <p class="card-text mb-auto">
              its an norwegian
            </p>
            <a href="#" class="stretched-link">Continue reading</a>
          </div>
          <div class="col-auto d-none d-lg-block">
            <img src="images/transilvanian.png" class="img-thumbnail">
          </div>
        </div>
      </div>
        </div>
    <div class="row g-5">
      <div class="col-md-8">
        <h3 class="pb-4 mb-4 fst-italic border-bottom">
          Actual hits 
        </h3>

        <article class="blog-post">
          <h1></h1>
        </article>

        <article class="blog-post">
          <h2 class="blog-post-title mb-1">Sample blog post</h2>
          <p class="blog-post-meta">January 1, 2021 by <a href="#">Mark</a></p>

          <p>
            This blog post shows a few different types of content that???s
            supported and styled with Bootstrap. Basic typography, lists,
            tables, images, code, and more are all supported as expected.
          </p>
          <hr />
          
          
          <p>
            Most of these elements are styled by browsers with few modifications
            on our part.
          </p>
          <h2>Heading</h2>
          <p>
            This is some additional paragraph placeholder content. It has been
            written to fill the available space and show how a longer snippet of
            text affects the surrounding content. We'll repeat it often to keep
            the demonstration flowing, so be on the lookout for this exact same
            string of text.
          </p>
          <h3>Sub-heading</h3>
          <p>
            This is some additional paragraph placeholder content. It has been
            written to fill the available space and show how a longer snippet of
            text affects the surrounding content. We'll repeat it often to keep
            the demonstration flowing, so be on the lookout for this exact same
            string of text.
          </p>
          
        </article>

        <article class="blog-post">
          <h2 class="blog-post-title mb-1">Another blog post</h2>
          <p class="blog-post-meta">
            December 23, 2020 by <a href="#">Jacob</a>
          </p>

          <p>
            This is some additional paragraph placeholder content. It has been
            written to fill the available space and show how a longer snippet of
            text affects the surrounding content. We'll repeat it often to keep
            the demonstration flowing, so be on the lookout for this exact same
            string of text.
          </p>
          <blockquote>
            <p>
              Longer quote goes here, maybe with some
              <strong>emphasized text</strong> in the middle of it.
            </p>
          </blockquote>
          <p>
            This is some additional paragraph placeholder content. It has been
            written to fill the available space and show how a longer snippet of
            text affects the surrounding content. We'll repeat it often to keep
            the demonstration flowing, so be on the lookout for this exact same
            string of text.
          </p>
         
        </article>

        
        <nav class="blog-pagination" aria-label="Pagination">
          <a class="btn btn-outline-primary rounded-pill" href="#">Older</a>
          <a class="btn btn-outline-secondary rounded-pill disabled">Newer</a>
        </nav>
      </div>

      <div class="col-md-4">
        <div class="position-sticky" style="top: 2rem">
          <div class="p-4 mb-3 bg-light rounded">
            <h4 class="fst-italic">Player</h4>
            <p class="mb-0">
              Customize this section to tell your visitors a little bit about
              your publication, writers, content, or something else entirely.
              Totally up to you.
            </p>
          </div>

          <div class="p-4">
            <h4 class="fst-italic">Archives</h4>
            <ol class="list-unstyled mb-0">
              <li><a href="#">March 2021</a></li>
              <li><a href="#">February 2021</a></li>
              <li><a href="#">January 2021</a></li>
              <li><a href="#">December 2020</a></li>
              <li><a href="#">November 2020</a></li>
              <li><a href="#">October 2020</a></li>
              <li><a href="#">September 2020</a></li>
              <li><a href="#">August 2020</a></li>
              <li><a href="#">July 2020</a></li>
              <li><a href="#">June 2020</a></li>
              <li><a href="#">May 2020</a></li>
              <li><a href="#">April 2020</a></li>
            </ol>
          </div>

          <div class="p-4">
            <h4 class="fst-italic">Elsewhere</h4>
            <ol class="list-unstyled">
              <li><a href="#">GitHub</a></li>
              <li><a href="#">Twitter</a></li>
              <li><a href="#">Facebook</a></li>
            </ol>
          </div>
        </div>
      </div>
    </div>
  </main>

  <footer class="blog-footer">
    <p>
      Blog template built for
      <a href="https://getbootstrap.com/">Bootstrap</a> by
      <a href="https://twitter.com/mdo">@mdo</a>.
    </p>
    <p>
      <a href="#">Back to top</a>
    </p>
  </footer>
</template>

<style scoped>
.bd-placeholder-img {
  font-size: 1.125rem;
  text-anchor: middle;
  -webkit-user-select: none;
  -moz-user-select: none;
  user-select: none;
}

@media (min-width: 768px) {
  .bd-placeholder-img-lg {
    font-size: 3.5rem;
  }
}

.b-example-divider {
  height: 3rem;
  background-color: rgba(0, 0, 0, 0.1);
  border: solid rgba(0, 0, 0, 0.15);
  border-width: 1px 0;
  box-shadow: inset 0 0.5em 1.5em rgba(0, 0, 0, 0.1),
    inset 0 0.125em 0.5em rgba(0, 0, 0, 0.15);
}

.b-example-vr {
  flex-shrink: 0;
  width: 1.5rem;
  height: 100vh;
}

.bi {
  vertical-align: -0.125em;
  fill: currentColor;
}

.nav-scroller {
  position: relative;
  z-index: 2;
  height: 2.75rem;
  overflow-y: hidden;
}

.nav-scroller .nav {
  display: flex;
  flex-wrap: nowrap;
  padding-bottom: 1rem;
  margin-top: -1px;
  overflow-x: auto;
  text-align: center;
  white-space: nowrap;
  -webkit-overflow-scrolling: touch;
}
</style>
