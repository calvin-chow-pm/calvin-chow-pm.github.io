# calvin-chow-pm.github.io

User site for [calvin-chow-pm.github.io](https://calvin-chow-pm.github.io/).

`index.html` redirects the bare root to the product cover:

https://calvin-chow-pm.github.io/agentic-product-workflow/

`404.html` sends unknown paths on this user site to the same cover. Both pages use a zero-second meta refresh, `location.replace`, a canonical link, and a visible fallback link.

Project sites stay in their own repositories and are not published from here:

- [/agentic-product-workflow/](https://calvin-chow-pm.github.io/agentic-product-workflow/)
- [/pm-ai-second-brain/](https://calvin-chow-pm.github.io/pm-ai-second-brain/)

This repo has no files or directories at those paths, so those sites keep serving from their own repos.

`.nojekyll` turns off Jekyll so these HTML files are published as-is.
