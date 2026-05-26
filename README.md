# packages

Builds and publishes Bitcraze's signed APT repository, served at
[packages.bitcraze.io](https://packages.bitcraze.io).

Applications publish their `.deb`s by attaching them to a GitHub release and
firing a `repository_dispatch` (`publish-deb`) at this repo; see
[`.github/workflows/publish-apt.yml`](.github/workflows/publish-apt.yml).
