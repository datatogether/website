# Data Together Website

<!-- Repo Badges for: Github Project, Slack, License-->

[![GitHub](https://img.shields.io/badge/project-Data_Together-487b57.svg?style=flat-square)](http://github.com/datatogether)
[![Slack](https://img.shields.io/badge/slack-Archivers-b44e88.svg?style=flat-square)](https://archivers-slack.herokuapp.com/)
[![License](https://img.shields.io/github/license/datatogether/website.svg?style=flat-square)](./LICENSE)

A static-generated website to introduce the Data Together project, built with [Hugo](https://gohugo.io/). The website describes our collective commitment to support the development of a decentralized web that aggregates and preserves the public record, with attention to provenance and trustworthiness of our data.

## License

<span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">The Data Together Website</span> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

## Getting Involved

We would love involvement from more people! If you notice any errors or would like to submit changes, please see our [Contributing Guidelines](./.github/CONTRIBUTING.md).

We use GitHub issues for [tracking bugs and feature requests](https://github.com/datatogether/website/issues) and Pull Requests (PRs) for [submitting changes](https://github.com/datatogether/website/pulls).

## Usage


## Development

1. Clone this repo

    ```
    $ git clone git@github.com:datatogether/website.git
    ```

    and `cd` into the directory

1. Install Hugo

    We use [Hugo](https://gohugo.io/about/), a fast and modern static site generator written in Go, follow the [install instructions](https://gohugo.io/getting-started).

1. Make Changes and Test Locally

    You can then make changes using your favourite text editor, read about Hugo [usage basics](https://gohugo.io/getting-started/usage/) and [directory structure](https://gohugo.io/getting-started/directory-structure/).

    Hugo also includes a development server, so you can view your changes as you go. Spin it up with the following command:

    ```
    $ hugo server
    ```

    run `hugo` before adding changes to a git commit.


### Dependencies

- [bootstrap-sass](https://github.com/twbs/bootstrap-sass)

### Deployment

[datatogether.org](https://datatogether.org/) is manually deployed over IPFS ([the InterPlanetary File System](https://ipfs.io/)) using IPNS (the Inter-Planetary Naming System), you can also view the site via an IPFS gateway at [ipfs.io/ipns/datatogether.org](https://ipfs.io/ipns/datatogether.org/).
