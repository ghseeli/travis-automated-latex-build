The goal of this project is to make it as painless as possible to get public
GitHub repositories to automatically build LaTeX files and upload them to GitHub
pages, thereby making them accessible online both as .tex files and .pdf files
with minimal work for the maintainer.

How to Setup
---

1. Clone or fork this repo as your skeleton.
1. Enable Travis-CI to build this project.
1. Generate a GitHub token in your GitHub Developer Settings with only public repo access.
1. Add "GITHUB_TOKEN" with the token value to your Environment variables in Travis.
1. Push a commit to the repo to see if it builds!
