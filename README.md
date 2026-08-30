# Radon Test Index static site
Open index.html in a browser. No build step required.
Publish: GitHub Settings, Pages, Deploy from a branch, root or docs folder. Keep .nojekyll.

## Publish on GitHub Pages (free)

1. Create a public GitHub repository.
2. Copy the contents of this site folder to the repo root or to a docs folder.
3. Keep the .nojekyll file so GitHub does not run Jekyll.
4. Repo Settings then Pages then Build and deployment: source Deploy from a branch, branch main, folder root or docs.
5. The site will appear at your github.io project URL after a minute or two.

Relative links work on a project-pages subpath. Optional: use a gh-pages branch as the Pages source.

No custom domain is required. Do not add affiliate or checkout links.

## What is in here

| File | Role |
| --- | --- |
| index.html | Homepage |
| how-to-test.html | How to test a home |
| ia.html | Iowa directory |
| pa.html | Pennsylvania directory |
| oh.html | Ohio directory (partial) |
| mn.html | Minnesota directory |
| nd.html | North Dakota directory |
| co.html | Colorado directory |
| il.html | Illinois directory |
| about.html | Independent index, verification, sources |
| css/style.css | Layout and type |

Data lives in the parent data JSON files. Regenerating HTML is optional (python3 run_build.py from the repo root). Viewing and publishing do not need that script.
