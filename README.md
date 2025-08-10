# Learning Markdown

A practical, concise guide to learning and mastering Markdown — powered by `mdBook`.

## Overview

This project is a structured guide to understanding Markdown, its use cases, tools, and extensions like LaTeX and Pandoc.

## Table of Contents

- [ ] **What Are Markup Languages?**  
       A quick intro to markup languages and how they differ from programming languages.
- [ ] **A Brief History of Markdown**  
       Where it started and why it's become the go-to format for documentation.
- [ ] **Use Cases of Markdown**  
       From documentation and note-taking to blogging and slides.
- [ ] **Editors**  
       A look at Markdown editors — from raw to rich.
- [ ] **Markdown ‌Basics**  
       Explore syntax, tips, and lesser-known tricks.
- [ ] **Markdown Flavors**  
       Variations of Markdown like GitHub Flavored Markdown (GFM) and how they extend the original syntax.
- [ ] **Pandoc Essentials**  
       Convert Markdown to other formats (PDF, DOCX, HTML, etc.).
- [ ] **Markdown + LaTeX**  
       Learn to write math and scientific docs using LaTeX inside Markdown.

## Tech Stack

- [`mdBook`](https://rust-lang.github.io/mdBook/) — for building the book
- GitHub Actions — for automated builds and deploys

## How to Build Locally

```sh
# Install mdBook:
cargo install mdbook

# Clone the repository:
git clone --depth=1 https://github.com/slash071/mdlearn.git

# Navigate into the project and serve the book:
cd mdlearn
mdbook serve --open
```
