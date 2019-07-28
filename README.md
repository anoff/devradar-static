# devradar static

[![Build Status](https://cloud.drone.io/api/badges/anoff/devradar/status.svg)](https://cloud.drone.io/anoff/devradar)

<img src="assets/logo-text.png">

This is a template repository you can use to create your own devradar instance hosted on GitHub pages.
It serves a `devradar.toml` file from a static webserver.
Follow the setup instructions to get your devradar working in a few minutes.
The content in this repositories `gh-pages` branch is generated using the [static config](https://github.com/anoff/devradar/tree/master/editor/.build/static) in the devradar main repository.

> Visit [devradar.io](https://devradar.io) for more background on the devradar

## Setup instructions

1. Fork this repository, see [GitHub guide](https://help.github.com/en/articles/fork-a-repo) for help
1. Rename the repository to `devradar`
1. Add your own skills
  1. go to [editor.devradar.io](//editor.devradar.io) and configure your devradar, see [devradar help](https://devradar.io/howto/#adding-skills)
  1. customize the `title` metadata, see [devradar help](https://devradar.io/howto/#changing-blips-and-devradar-metadata)
  1. download your devradar file from `Settings -> Download as TOML`
  1. upload your devradar file as `devradar.toml` into the `gh-pages` branch (replace existing file)
1. Set up GitHub Pages deployment from `gh-pages` branch, see [GitHub guide](https://help.github.com/en/articles/configuring-a-publishing-source-for-github-pages) for instructions
1. Configure a [custom domain](https://help.github.com/en/articles/quick-start-setting-up-a-custom-domain) if you have one
1. Check your devradar at `https://<githubname>.github.io/devradar`

## License & Attributions

Copyright 2019 Andreas Offenhaeuser <https://anoff.io>
