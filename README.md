# aurci [![Build Status](https://travis-ci.com/alexojegu/aurci.svg?branch=main)](https://app.travis-ci.com/alexojegu/aurci)

Use [Travis CI] for building and packaging a few packages from [AUR] and deploy them to [GitHub Releases] so it can be used
as repository in [Arch Linux].

## Setup

On GitHub:
  - Generate a personal access token with scope `public_repo`.

On Travis CI:
  - Add a `GITHUB_TOKEN` environment variable with the personal access token code as value.

[GitHub Releases]: https://github.com/alexojegu/aurutilsci/releases
[Arch Linux]: https://www.archlinux.org
[Travis CI]: https://travis-ci.com/
[AUR]: https://aur.archlinux.org
