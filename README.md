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
hugo new --kind post posts/2023/first-post.md
```
