---
title: "Events"
draft: false
---

# Events
<!-- test leaders HTML in markdown file -->
<style>
* {
  box-sizing: border-box;
}
/*
body {
  font-family: "Open Sans", sans-serif;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  gap: 1rem 2rem;
  justify-content: flex-start;
  align-items: auto;
  background: #f3f3f9;
}
 */
img#img1 {
  display: block;
  width: 100%;
}
/*
h2 {
	margin: 0;
	font-size: 1.4rem;
}

@media (min-width: 50em) {
	h2 {
		font-size: 1.8rem;
	}
}
*/
.cta-card {
  --shadowColor: 187 60% 40%;
  display: flex;
  flex-wrap: wrap;
  background: #d9d6d3;
  max-width: 56rem;
  width: 100%;
  /* box-shadow: 0.65rem 0.65rem 0 hsl(var(--shadowColor) / 1);*/
  border-radius: 0.8rem;
  overflow: hidden;
  border: 0.25rem solid;
}

.cta-card img {
  aspect-ratio: 3 / 2;
  object-fit: contain;
  flex: 1.3 1 220px;
  outline: 0.18rem solid;
}

.cta-card__text-column {
  padding: min(2rem, 4vw) min(2rem, 4vw) min(2rem, 4vw);
  flex: 1 0 50%;
}

.cta-card__text-column > * + * {
  margin: min(1.2rem, 2.3vw) 0 0 0;
}
/*
.cta-card a {
  display: inline-block;
  color: black;
  padding: 0.5rem 1rem;
  text-decoration: none;
  background: hsl(187 75% 64%);
  border-radius: 0.6rem;
  font-weight: 700;
  border: 0.35rem solid;
}
*/
.rowcol2 {
  background: #ffecd1;
  color: #ef3e2d;
}
.fa {
  padding: 0.25rem 2rem 0.25rem 2rem;
  margin: 0.3rem 4rem 0.3rem 4rem;
}
.flexrow {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
  min-width: 100%;
}
</style>

<div class="d-flex flex-wrap">
  <article class="cta-card" style="background: #efefef">
    <img id="img1" src="https://www.ninjaonlinedating.com/blog/wp-content/uploads/2019/08/SmileModifiedKRAK.jpg" alt="Profile image 1" class="img-fluid rounded-start"></img>
    <div class="cta-card__text-column">
      <h4 class="card-title">FirstName LastName</h4>
      <h5 class="card-title">Title Subtitle</h5>
      <p class="card-text">
        This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer. Aute magna in aliqua voluptate exercitation in. Nulla incididunt excepteur id officia labore id mollit enim cupidatat sit. Culpa magna occaecat proident officia officia cillum cupidatat dolore. In id proident qui exercitation occaecat nisi cillum amet minim anim eu reprehenderit nisi dolore.
      </p>
      <!--<p class="card-text">
        Et consequat culpa dolore fugiat. Labore ullamco minim sint cillum laboris dolore fugiat ipsum laboris. Cillum proident commodo proident minim duis nisi velit sit dolore. Non sint non adipisicing sint Lorem.
      </p>
      <p class="card-text">
        Est eu aliquip tempor occaecat eiusmod elit eu dolor velit ullamco reprehenderit. Nisi dolore laboris enim consectetur cupidatat dolore reprehenderit ad Lorem incididunt ad ut ea tempor.
      </p>-->
    </div>
    <div class="col rowcol2 flexrow text-center border border-warning">
      <i class="fa fa-facebook fa-2x"></i>
      <i class="fa fa-envelope-o fa-2x"></i>
      <i class="fa fa-linkedin fa-2x"></i>
    </div>
  </article>
</div>
<br>
<div class="d-flex flex-wrap">
  <article class="cta-card">
    <img id="img1" src="https://i.pinimg.com/originals/5e/46/de/5e46de2cc3c337c1d5f385e6bb127ad3.jpg" alt="Profile image 2" class="img-fluid rounded-start">
    <div class="cta-card__text-column">
      <h4 class="card-title">FirstName LastName</h4>
      <h5 class="card-title">Title Subtitle</h5>
      <p class="card-text">
        This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer. Aute magna in aliqua voluptate exercitation in. Nulla incididunt excepteur id officia labore id mollit enim cupidatat sit. Culpa magna occaecat proident officia officia cillum cupidatat dolore. In id proident qui exercitation occaecat nisi cillum amet minim anim eu reprehenderit nisi dolore.
      </p>
      <!-- <p class="card-text">
        Et consequat culpa dolore fugiat. Labore ullamco minim sint cillum laboris dolore fugiat ipsum laboris. Cillum proident commodo proident minim duis nisi velit sit dolore. Non sint non adipisicing sint Lorem.
      </p>
      <p class="card-text">
        Est eu aliquip tempor occaecat eiusmod elit eu dolor velit ullamco reprehenderit. Nisi dolore laboris enim consectetur cupidatat dolore reprehenderit ad Lorem incididunt ad ut ea tempor. Reprehenderit tempor reprehenderit sunt ipsum amet occaecat sint ut labore do dolor.
      </p> -->
    </div>
    <div class="col rowcol2 flexrow text-center border border-warning">
      <i class="fa fa-facebook fa-2x"></i>
      <i class="fa fa-envelope-o fa-2x"></i>
      <i class="fa fa-linkedin fa-2x"></i>
    </div>
  </article>
</div>

[Events comming soon]

<!-- iterate through a list of events with Hugo templating -->