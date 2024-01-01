# Recipes

The static site generator and content behind https://recipes.whitehead-smith.com.

Built with Eleventy and deployed to Cloudflare pages using their native Github integration.
Commits pushed to `main` are automatically built and deployed.

## Adding a new recipe

Add a new markdowm file in `/src/recipes` - the filename will become the URL slug.

Make sure the frontmatter inludes a title and the `recipes` tag.
These are used to populate the list of recipes on the home page.

## Developing the site

Run `npm run serve` to run the site locally including the hot-reloader.

All CSS is loaded from `/src/css/all.css`.
