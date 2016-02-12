# Deventropy Website

[www.deventropy.org](http://www.deventropy.org) pages

## Editing / Building the site

The site source is maintained as a Maven project with `pom` packaging and on the `site-src` branch. To edit the files
modify the `src/site/*` files on that branch.

To build / deploy the site run `mvn site` (or use a script that stages the site) and deploy the site to the `master`
branch of this repository.
