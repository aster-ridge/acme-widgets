# Acme Widgets — stock site

A minimal static website used as the starting point for the AutoCTO live demo.
It's intentionally plain: just `index.html` and `styles.css`. **No** infrastructure,
**no** GitHub Actions, **no** deploy pipeline — yet.

When AutoCTO runs against this repo, it adds:

- CloudFormation templates for an S3 + CloudFront deploy
- A GitHub Action that publishes the site on push to `main`
- Security and compliance scaffolding (least-privilege IAM, OIDC, etc.)

The point of the demo is to see those additions land as PRs against an
otherwise untouched website.

## Run locally

Open `index.html` in a browser. That's it.
