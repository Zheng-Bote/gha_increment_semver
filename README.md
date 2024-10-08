<div id="top" align="center">
<h1>increment SemVer</h1>

<p>GH Action ti increment the given semantic version</p>

[Report Issue](https://github.com/Zheng-Bote/repo-template/issues) [Request Feature](https://github.com/Zheng-Bote/repo-template/pulls)

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
![GitHub Created At](https://img.shields.io/github/created-at/Zheng-Bote/repo-template)

</div>

<hr>

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**

- [Description](#description)
  - [Features](#features)
- [Status](#status)
- [Installation](#installation)
  - [Dependencies](#dependencies)
  - [folder structure](#folder-structure)
- [Usage/Examples](#usageexamples)
- [input / output Examples](#input--output-examples)
- [API Reference](#api-reference)
  - [Parameters](#parameters)
- [Documentation](#documentation)
  - [Github Page](#github-page)
- [Screenshots](#screenshots)
- [Authors and License](#authors-and-license)
  - [License](#license)
  - [Authors](#authors)
- [Code Contributors](#code-contributors)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

<hr>

## Description

![GHA](https://img.shields.io/badge/Github-Action-black?logo=githubactions)
![Node](https://img.shields.io/badge/Node-20-blue?logo=tsnode)

description of this

### Features

- \[x] works as designed
- \[ ] no bugs

<p align="right">(<a href="#top">back to top</a>)</p>

## Status

![Status](https://img.shields.io/badge/Status-works-green)
![GitHub Release Date](https://img.shields.io/github/release-date/Zheng-Bote/repo-template)

![GitHub Issues](https://img.shields.io/github/issues/Zheng-Bote/gha_increment_semver)
![GitHub Pull Requests](https://img.shields.io/github/issues-pr/Zheng-Bote/gha_increment_semver)

[![Repo - create Repo-Tree in README.md](https://github.com/Zheng-Bote/gha_increment_semver/actions/workflows/repo-create_tree_readme.yml/badge.svg)](https://github.com/Zheng-Bote/gha_increment_semver/actions/workflows/repo-create_tree_readme.yml)
[![Repo - add Actions In/Out to README](https://github.com/Zheng-Bote/gha_increment_semver/actions/workflows/repo-actions_docu.yml/badge.svg)](https://github.com/Zheng-Bote/gha_increment_semver/actions/workflows/repo-actions_docu.yml)
[![Repo - create TOC of README](https://github.com/Zheng-Bote/gha_increment_semver/actions/workflows/repo-create_doctoc.yml/badge.svg)](https://github.com/Zheng-Bote/gha_increment_semver/actions/workflows/repo-create_doctoc.yml)

<p align="right">(<a href="#top">back to top</a>)</p>

## Installation

bla bla

### Dependencies

bla bla

### folder structure

<!-- readme-tree start -->

```
.
├── .github
│   └── workflows
│       ├── repo-actions_docu.yml
│       ├── repo-create_doctoc.yml
│       ├── repo-create_tree_readme.yml
│       └── repo-increment_semver.yml
├── LICENSE
├── README.md
├── action.yml
├── entrypoint.sh
└── tree.bak

2 directories, 9 files
```

<!-- readme-tree end -->

<p align="right">(<a href="#top">back to top</a>)</p>

## Usage/Examples

```html
<mark> under constrcution </mark>
```

<p align="right">(<a href="#top">back to top</a>)</p>

## input / output Examples

| version-fragment | current-version |     | output         |
| ---------------- | --------------- | --- | -------------- |
| major            | 2.11.7          |     | 3.0.0          |
| major            | v2.11.7         |     | 3.0.0          |
| major            | 2.11.7-alpha3   |     | 3.0.0          |
| major            | 2.11.7-alpha.3  |     | 3.0.0          |
| feature          | 2.11.7          |     | 2.12.0         |
| feature          | 2.11.7-alpha3   |     | 2.12.0         |
| feature          | 2.11.7-alpha.3  |     | 2.12.0         |
| bug              | 2.11.7          |     | 2.11.8         |
| bug              | 2.11.7-alpha3   |     | 2.11.8         |
| bug              | 2.11.7-alpha.3  |     | 2.11.8         |
| alpha            | 2.11.7          |     | 2.11.7-alpha.1 |
| alpha            | 2.11.7-alpha3   |     | 2.11.7-alpha.4 |
| alpha            | 2.11.7-alpha.3  |     | 2.11.7-alpha.4 |
| beta             | 2.11.7          |     | 2.11.7-beta.1  |
| beta             | 2.11.7-alpha3   |     | 2.11.7-beta.1  |
| beta             | 2.11.7-alpha.3  |     | 2.11.7-beta.1  |
| pre              | 2.11.7          |     | 2.11.7-pre.1   |
| pre              | 2.11.7-alpha3   |     | 2.11.7-pre.1   |
| pre              | 2.11.7-alpha.3  |     | 2.11.7-pre.1   |
| rc               | 2.11.7          |     | 2.11.7-rc.1    |
| rc               | 2.11.7-alpha3   |     | 2.11.7-rc.1    |
| rc               | 2.11.7-alpha.3  |     | 2.11.7-rc.1    |

<p align="right">(<a href="#top">back to top</a>)</p>

## API Reference

### Parameters

<!-- only for actions repo -->

<!-- ## Inputs -->

<!-- ## Outputs -->

        <rz-footer></rz-footer>

<!---->

| Parameter    | Type     | Description                          |
| :----------- | :------- | :----------------------------------- |
| `name`       | `string` | _Optional_ name-of-copyright-holder  |
| `created`    | `string` | _Optional_ <YYYY>                    |
| `version`    | `string` | _Optional_ \<v0.0.0>                 |
| `link_left`  | `string` | _Optional_ link-to-contact-page      |
| `link_right` | `string` | _Optional_ link-to-legal-notice-page |

<p align="right">(<a href="#top">back to top</a>)</p>

## Documentation

```mermaid
graph TD;
    Workflow-. parameter .->Callable_Workflow;
    Callable_Workflow-- parameter -->Action;
```

### Github Page

[![GH-Page](https://img.shields.io/badge/Github-Pages-black?logo=github)](https://www.github.com/Zheng-Bote)

see also: <https://linktodocumentation>

> \[!NOTE]
> Useful information that users should know, even when skimming content.

> \[!TIP]
> Helpful advice for doing things better or more easily.

> \[!IMPORTANT]
> Key information users need to know to achieve their goal.

> \[!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> \[!CAUTION]
> Advises about risks or negative outcomes of certain actions.

<p align="right">(<a href="#top">back to top</a>)</p>

## Screenshots

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

<p align="right">(<a href="#top">back to top</a>)</p>

## Authors and License

### License

MIT License

Copyright (c) 2024 ZHENG Robert

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

        https://choosealicense.com/licenses/mit/

### Authors

- [![Zheng Robert](https://img.shields.io/badge/Github-Zheng_Robert-black?logo=github)](https://www.github.com/Zheng-Bote)

## Code Contributors

![Contributors](https://img.shields.io/github/contributors/Zheng-Bote/gha_increment_semver?color=dark-green)

[![Zheng Robert](https://img.shields.io/badge/Github-Zheng_Robert-black?logo=github)](https://www.github.com/Zheng-Bote)

<hr>

:vulcan_salute:

<p align="right">(<a href="#top">back to top</a>)</p>
