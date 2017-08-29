# Human Interface Guidelines (HIGs)

An interactive Human Interface Guidelines for [Auckland Museum](http://www.aucklandmuseum.com/) to promote a coherent look, feel, and visitor experience across multiple galleries and over time.

## Requirements

* [Git](https://git-scm.com/)
* [Hugo](https://gohugo.io/getting-started/installing/)

## Getting started

Clone the project from github

```bash
git clone https://github.com/AucklandMuseum/human-interface-guidelines.git
```

Check out the environments section below for next course of actions

## Environments

### Development

Run this command in your terminal to start Hugo web dev server

```bash
hugo serve -D
```

The site can now be viewed on `http://localhost:1313/human-interface-guidelines/`

> **Tips**:
> If you want to share your dev site to others within your LAN network, run this command instead `hugo server -D --bind <LAN IP> --baseURL http://<LAN IP>`

### Production

To publish the site to GitHub Pages, first you need to export content into static HTMLs

```bash
hugo
```

Use git to commit changes in `docs` folder and push to GitHub `master` branch

```bash
git add -- ./docs && git commit
git push -u origin master
```
