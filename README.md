# Acme Widgets

Static marketing site for **Aster Ridge Labs** pipeline demos.

This repo intentionally ships as a **greenfield static site** — `index.html` and `styles.css` only — with **no** Dockerfile, `.dockerignore`, or GitHub Actions workflows yet. That is the starting point for the Infranitum pipeline wizard:

1. Install the Infranitum GitHub App on `aster-ridge/acme-widgets`
2. Run the container readiness scan (expects gaps)
3. Open a pull request that adds Docker scaffolding, CloudFormation, and a secure CI/CD workflow

## Run locally

Open `index.html` in a browser.

## About

Based on [DavidITScripts/autocto-stock-website](https://github.com/DavidITScripts/autocto-stock-website).
