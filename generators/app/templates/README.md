<div align="center">
<h1><%= moduleName %></h1>

<p><%= description %></p>
</div>

<hr />

[![Build Status][build-badge]][build]
[![Code Coverage][coverage-badge]][coverage]
[![version][version-badge]][package]
[![downloads][downloads-badge]][npmtrends]
[![MIT License][license-badge]][license]

[![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square)](#contributors)
[![PRs Welcome][prs-badge]][prs]
[![Code of Conduct][coc-badge]][coc]

## The problem

// TODO

## This solution

// TODO

## Table of Contents

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION. It'll update automatically -->

- [Installation](#installation)
- [Usage](#usage)
- [Props](#props)
- [Control Props](#control-props)
- [Child Callback Function](#child-callback-function)
- [Examples](#examples)
- [FAQ](#faq)
- [Inspiration](#inspiration)
- [Other Solutions](#other-solutions)
- [Contributors](#contributors)
- [LICENSE](#license)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Installation

This module is distributed via [npm][npm] which is bundled with [node][node] and
should be installed as one of your project's <% if (devDep) { %>`devDependencies`<% } %><% if (!devDep) { %>`dependencies`<% } %>:

```
npm install --save<% if (devDep) { %>-dev<% } %> <%= moduleName %>
```

## Usage

// TODO

## Inspiration

// TODO

## Other Solutions

I'm not aware of any, if you are please [make a pull request][prs] and add it
here!

## Contributors

Thanks goes to these people ([emoji key][emojis]):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore -->
<table><tr><td align="center"><a href="https://www.3alves.com"><img src="https://avatars3.githubusercontent.com/u/784848?s=460&v=4" width="100px;" alt="<%= authorName %>"/><br /><sub><b><%= authorName %></b></sub></a><br /><a href="https://github.com/<%= orgName %>/<%= moduleName %>/commits?author=<%= authorID %>" title="Code">💻</a> <a href="https://github.com/<%= orgName %>/<%= moduleName %>/commits?author=<%= authorID %>" title="Documentation">📖</a> <a href="#infra-<%= authorID %>" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a> <a href="https://github.com/<%= orgName %>/<%= moduleName %>/commits?author=<%= authorID %>" title="Tests">⚠️</a></td></tr></table>

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors][all-contributors] specification.
Contributions of any kind welcome!

## LICENSE

MIT

[npm]: https://www.npmjs.com/
[node]: https://nodejs.org

[build-badge]: https://img.shields.io/travis/<%= orgName %>/<%= moduleName %>.svg?style=flat-square
[build]: https://travis-ci.org/<%= orgName %>/<%= moduleName %>
[coverage-badge]: https://img.shields.io/codecov/c/github/<%= orgName %>/<%= moduleName %>.svg?style=flat-square
[coverage]: https://codecov.io/github/<%= orgName %>/<%= moduleName %>
[version-badge]: https://img.shields.io/npm/v/<%= moduleName %>.svg?style=flat-square
[package]: https://www.npmjs.com/package/<%= moduleName %>
[downloads-badge]: https://img.shields.io/npm/dm/<%= moduleName %>.svg?style=flat-square
[npmtrends]: http://www.npmtrends.com/<%= moduleName %>
[license-badge]: https://img.shields.io/npm/l/<%= moduleName %>.svg?style=flat-square
[license]: https://github.com/<%= orgName %>/<%= moduleName %>/blob/master/LICENSE
[prs-badge]: https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square
[prs]: http://makeapullrequest.com
[donate-badge]: https://img.shields.io/badge/$-support-green.svg?style=flat-square
[coc-badge]: https://img.shields.io/badge/code%20of-conduct-ff69b4.svg?style=flat-square
[coc]: https://github.com/<%= orgName %>/<%= moduleName %>/blob/master/other/CODE_OF_CONDUCT.md
[emojis]: https://github.com/all-contributors/all-contributors#emoji-key
[all-contributors]: https://github.com/all-contributors/all-contributors
