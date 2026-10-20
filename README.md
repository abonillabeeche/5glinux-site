# 5glinux.com

Landing page for https://5glinux.com. Hugo, no theme: `layouts/index.html`,
`assets/site.css`, project cards in `data/projects.yaml`.

"Latest from the blog" is pulled from https://blog.5glinux.com/index.xml at build
time. CI rebuilds on push, daily, on demand, and on a `blog-published`
repository_dispatch event.

Preview: `hugo server --port 1314`
