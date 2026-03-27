# gentoo-packages

This repository generates and hosts the Gentoo overlays static site.

It uses [g2](https://github.com/arran4/g2) to parse `repositories.xml` from Gentoo's API and generate a static HTML website of all overlays and packages.

A GitHub Actions workflow is used to automatically generate and deploy the site to GitHub Pages nightly, and whenever the workflow is updated. The g2 tool is run via the [g2-action](https://github.com/arran4/g2-action).
