AEC SOURCE — RENDER STATIC SITE PACKAGE
=======================================

CONTENTS
- index.html: AEC Source homepage with the featured article card.
- style.css: shared responsive visual design.
- articles/permit-resubmissions/index.html: complete standalone article page.
- assets/permit-package-comparison.jpg: article feature illustration.
- assets/favicon.svg: site icon.
- robots.txt: allows public crawling.

BRAND
The publication name is AEC Source. The layout and palette follow the earlier custom-coded AEC publication site design.

ARTICLE
How Can Architecture Firms Reduce Permit Resubmissions Caused by Incomplete Drawing Packages?

BACKLINK
The article contains one contextual link to:
https://www.gsourcedata.com/architectural-drafting-services/?utm_source=render&utm_campaign=guest-post

RENDER DEPLOYMENT
This is a plain static HTML/CSS site; it does not require a build step.
1. Upload these files and folders to a GitHub repository (keep index.html and style.css at repository root).
2. In Render, choose New > Static Site and connect that repository.
3. Use the branch containing these files (normally main).
4. Leave Build Command empty.
5. Set Publish Directory to .
6. Create the Static Site. Render provides an onrender.com URL after deployment.

Do not select Web Service. Do not enter a paid compute plan; static sites are free to deploy, subject to workspace usage allowances.
