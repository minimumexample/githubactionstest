[![Netlify Status](https://api.netlify.com/api/v1/badges/3b633c91-2f94-4f36-874a-1a34c2ef2a5e/deploy-status)](https://app.netlify.com/sites/sleepy-brahmagupta-f91d4a/deploys)

Published book: https://sleepy-brahmagupta-f91d4a.netlify.app/

Testing:

`usethis::use_github_action("bookdown.yaml")`

Version: https://github.com/r-lib/actions/blob/92c6da7b47f0c1814c4d62d62a9c0f24291fe5de/examples/bookdown.yaml (2020-12-06)

### What I learned

**You need to rerun `renv::snapshot()` everytime you add a package to DESCRIPTION.**

`brew install pandoc-citeproc` doesn't work, it's deprecated


See instructions here:

https://github.com/r-lib/actions/tree/master/examples#build-bookdown-site

and here:

https://www.hvitfeldt.me/blog/bookdown-netlify-github-actions/

*This repo was initially generated from a bookdown template available here: https://github.com/jtr13/EDAVtemplate.*	




