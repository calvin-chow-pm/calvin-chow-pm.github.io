# calvin-chow-pm.github.io

User site for [calvin-chow-pm.github.io](https://calvin-chow-pm.github.io/).

The site root is the product cover. Clean paths:

- [/](https://calvin-chow-pm.github.io/) — cover
- [/workflow/](https://calvin-chow-pm.github.io/workflow/) — seven-step walkthrough (step hashes such as `#5` stay on this page)
- [/system/](https://calvin-chow-pm.github.io/system/) — monitoring and evaluation
- [/prototype/](https://calvin-chow-pm.github.io/prototype/) — certification prototype
- [/app/](https://calvin-chow-pm.github.io/app/) — candidate workspace used in the walkthrough preview
- [/baseline/](https://calvin-chow-pm.github.io/baseline/) — baseline workspace
- [/walkthrough/](https://calvin-chow-pm.github.io/walkthrough/) — recorded playback

`404.html` sends unknown paths on this user site to the cover. It uses a zero-second meta refresh, `location.replace`, a canonical link, and a visible fallback link.

Project sites stay in their own repositories and are not published from paths in this repo:

- [/agentic-product-workflow/](https://calvin-chow-pm.github.io/agentic-product-workflow/) — redirects to the pages above
- [/pm-ai-second-brain/](https://calvin-chow-pm.github.io/pm-ai-second-brain/) — unchanged

This repo has no files or directories at those paths, so those sites keep serving from their own repos.

`.nojekyll` turns off Jekyll so these HTML files are published as-is.
