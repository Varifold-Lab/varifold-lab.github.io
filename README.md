# Varifold community website

The organization homepage at **https://varifold-lab.github.io/**.

Varifold is an open learning community studying formal verification, interpretability, and tokenomics, with a focus on the mathematical foundations of AI safety. We develop and share notes, tools, and open-source projects to support learning and verifiable knowledge discovery.

This repository contains the community introduction and a directory of public projects. Project documentation stays in its own repository and deploys independently:

| Project | Documentation | Repository |
| --- | --- | --- |
| LeanMFG | https://varifold-lab.github.io/LeanMFG/ | [LeanMFG](https://github.com/Varifold-Lab/LeanMFG) |
| Mathematics for AI Safety | https://varifold-lab.github.io/awesome-ai-safety/ | [awesome-ai-safety](https://github.com/Varifold-Lab/awesome-ai-safety) |
| LeanSort | Repository README | [LeanSort](https://github.com/Varifold-Lab/LeanSort) |

## Edit and preview

Edit `index.html` for content and `styles.css` for presentation. There are no build dependencies, external fonts, or analytics.

```sh
python3 -m http.server 4173 --bind 127.0.0.1
```

The course documentation link uses the organization-relative `/awesome-ai-safety/` path. It requires the course site to be served at that path for a combined local preview; the other project links point to their live sites.

## Publish

Use the repository name `Varifold-Lab/varifold-lab.github.io`. In **Settings → Pages**, set **Source** to **GitHub Actions**. The included workflow publishes only `index.html`, `styles.css`, and `404.html` on pushes to `main`.

The community description follows the organization's [public profile](https://github.com/Varifold-Lab). List public projects with descriptive links; keep draft and private research out of the public directory.
