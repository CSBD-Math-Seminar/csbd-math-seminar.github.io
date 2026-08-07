# Website for the CSBD Math seminar

This is the repository for the website of the CSBD Math Seminar, which can be found at https://csbd-math-seminar.github.io/.

## Structure of the repository

The content of the website is controlled by `index.html`. The design is controlled by `styles.css`. The file `.github/workflows/deploy.yml` is a technical file that tells GitHub how to deploy the site when we make updates.

## Format of abstracts
An abstract for a talk has the following form. Note that the website supports $\LaTeX$ via [MathJax](https://www.mathjax.org/).

```html
<article class="talk-card">
  <div class="talk-date">Jan 01</div>
  <div class="talk-content">
    <p class="talk-speaker">Name of the speaker <span>Affiliation</span></p>
    <h3>Title of the talk</h3>
    <details>
      <summary>Abstract</summary>
      <p>This talk is about $x$, $y$ and $z$, and the equation $$x^n+y^n=z^n.$$</p>
    </details>
  </div>
</article>
```

## How to make changes

The files can be edited directly in the browser through GitHub:

1. Go to the relevant file.
2. Click on "Edit this file" (the pen symbol).
3. Make your changes.
4. Click on "Commit changes..." (the green button).
5. Write a short commit message explaining what you changed and click in the commit button.

There that there will be a short wait time while Github deploys your changes (go to "Actions" in the top menu to follow this process).