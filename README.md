<div id="top"></div>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://www.lonestarwesterndecor.com/">
    <img src="https://via.placeholder.com/300x200/fff/000.png" alt="Logo">
  </a>

  <h3 align="center">Project Name</h3>
  BigCommerce Storefront Theme
  <p align="center">
    <br />
    <a href="https://minnek.atlassian.net/l/cp/gAkNFePM"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://project-name-url.com/">View Demo</a>
    ·
    <a href="https://minnek.atlassian.net/jira/software/projects/{JIRA-KEY}/issues/">Report Bug</a>
    ·
    <a href="https://minnek.atlassian.net/jira/software/projects/{JIRA-KEY}/issues/">Request Feature</a>
  </p>
</div>


<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#installation">Installation and Setup Guide</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#contributing">Stack</a></li>
  </ol>
</details>


<!-- ABOUT THE PROJECT -->
## About The Project

![Project Name](https://via.placeholder.com/1200x800/fff/000.png) <!-- meta image path: meta/desktop_light.png -->

Project name description.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- INSTALLATION -->
## Installation and Setup Guide

### Cornerstone 6+ Only

* Setup Stencil CLI: `stencil init`. Enter the credentials.
* Download the BigCommerce Cornerstone 6+ theme from the store: `stencil download`
* Install these extra dependencies: `npm i -D husky @commitlint/config-conventional @commitlint/cli cypress cli-color`
* Install the theme dependencies: `npm install`

Add these script to the `package.json` file:
* `"dev": "stencil start -o"`. Start the stencil server and open the browser automatically.
* `"push": "stencil push -a -d -c 1"`. Push the theme to the live store and active it (only for stores in development mode).
* `"cy:open": "cypress open"`. Open cypress app and setup the environment.

### Code Owners

* Define who is the code owner of the project. Sometimes the code owner is the project lead or maybe the team lead of your team, this info can be find it in the jira project, learn more about [code owners](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners).

### CSS

* Add the code below to the end of the file `theme.scss`.

```scss
@import "ysw/settings";
@import "ysw/tools";
@import "ysw/generic";
@import "ysw/elements";
@import "ysw/components";
@import "ysw/layouts";
@import "ysw/utilities";
@import "ysw/vendor";
```

### Templates Structure

* All the templates for development are in `/templates/ysw`. Every folder have the explanation.

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- ROADMAP -->
## Roadmap

Project roadmap planning, accomplishments and releases.

- [ ] Project goal 1
- [ ] Project goal 2
- [ ] Project goal 3

See the [open issues](https://minnek.atlassian.net/browse/{JIRA-ID}) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- CONTRIBUTING -->
## Contributing

If you have a suggestion that would make this better, create a pull request. You can also simply open an issue with the tag "enhancement".

* Create your Feature Branch (`git checkout -b feature/JIRA-ID`)
* Commit your Changes (`git commit -m 'feat: JIRA-ID feature description'`)
* Push to the Branch (`git push origin feature/JIRA-ID`)
* Open a Pull Request (assign yourself to the PR, and add the Code Reviewer)
* Follow the project Pull Request Guidelines

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- STACK -->
## Stack

* Node.js 14
* Stencil CLI 5+
* ESLint
* Stylelint
* CommitLint (Conventional Commits)
* Cypress (E2E Test)
* Jest (Unit Test)
* Husky (Git Hooks)
* Grunt
* Editorconfig
* GitHub Actions
* GitHub Code Owners

<p align="right">(<a href="#top">back to top</a>)</p>