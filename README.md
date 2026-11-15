# BrandonMarcum.net

This repository contains source Code for [My Personal Website](https://brandonmarcum.net/).

It's based on the static content framework, [Hugo](https://gohugo.io/), with a forked [Hugo PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme. The CICD pipeline is deployed via Github Actions.

## Quick Reference

Clone theme submodule

```bash
git submodule update --init --recursive # needed when you reclone your repo (submodules may not get cloned automatically and will need to be commited)
```

Subsequent Submodule Updates

```bash
git submodule update --remote
```

Blog creation example

```bash
hugo new content posts/2023/first-post.md 
```

## Licensing

Original website content and photography are copyright
Brandon Marcum. All rights reserved.

Third-party software, themes, and assets remain subject
to their respective licenses.

- PaperMod — MIT License
- Lucide Icons — ISC and MIT Licenses

Third-party license notices are available in
the `static/licenses/` directory.
