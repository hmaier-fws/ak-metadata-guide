---
title: "How to contribute"
---

# Install [Quarto](https://quarto.org/)

The install should update your path to allow Quarto to be run from any command terminal. Details about installiung and running Quarto can be found on the [Quarto Get Started page](https://quarto.org/docs/get-started/).

Change to the project directory (if using GitHub Desktop, select "Repository - Open in Command prompt", or `Ctrl+\`)

Run the "[Quarto preview](https://quarto.org/docs/cli/preview.html)" command to start a live preview session that will render the updated pages as you edit. Some changes may not be automatically rendered by the preview, and you may need to exit (type `Ctrl-c` in the command window) and then restart the preview.

The site will be served locally by Quarto and should open a browser session at: http://localhost:xxxx/, with a default port in the range of 3000-8000 being assigned. The system console will indicate the port that is selected.

The site may need to be re-built (run "Quarto render") after edits are complete. This is usually only needed prior to deploying a site to the server.

## Publishing site

Quarto provides [several methods](https://quarto.org/docs/publishing/) to publish a website. The Alaska Region Metadata Guide [GitHub repositoty](https://github.com/USFWS/ak-metadata-guide) is configured to ignore the `/docs` directory. The site is deployed to the **gh-pages branch** using the Quarto [publish command](https://quarto.org/docs/publishing/github-pages.html#publish-command). Rendering the GitHub pages from the `/docs` directory often results in numerous conflicts if the site is edited my multiple individuals.

A site can be published as follows:

1) Go to the project directory and start Quarto
2) If using Git to manage site updates, switch to the branch you wish to publish
3) Run the command: `quarto publish gh-pages`
4) The current branch will be rendered and deployed to the `gh-pages` branch of the current repository.



# Style guide

This metadata guide should be authored using the same [style guidelines](https://usfws.github.io/ak-dm-guide/CONTRIBUTING.html) that apply to the Alaska Region Data Management Guide, unless exceptions are listed below.
