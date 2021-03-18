# Example of sphinx documentation for *Python3* package and publishing it with [github-pages](https://pages.github.com/)

1. Fork this repo.

2. Make sure *Github Pages* is enabled in your repo settings.

3. In this `README.md` change the url that has this next link: [online doc](file:///Users/anatorres/Desktop/ITAM/practica-1-segunda-parte-diramtz/docs/build/html/index.html) to point to your site of *Github Pages*.

4. Modify some `.rst` doc for example [src/docs/index.rst](src/docs/index.rst) to trigger gh action for building doc.

5. Go to `online doc` of step 3 after github actions succeed building doc.

**Note: if you want to create a *package* in `src` with different functions for example, then make the proper substitutions in `src` and change the `.rst` files related with correspondent files in `docs` to trigger gh action for building doc.**

