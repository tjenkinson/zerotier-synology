Alpine-based Docker image for ZeroTier on Synology
=====

This container is originally based on [zyclonite/zerotier](https://hub.docker.com/r/zyclonite/zerotier) but is maintained officially by the ZeroTier team.

This is publised to the GitHub container registry at "[ghcr.io/tjenkinson/zerotier-synology](https://github.com/tjenkinson/zerotier-synology/pkgs/container/zerotier-synology)" using the following tags:

- `<major>.<minor>.<patch>`
- `<major>.<minor>`
- `<major>`

E.g `docker pull ghcr.io/tjenkinson/zerotier-synology:1` for the latest from `v1`.


## Versioning

The versions of the image do not match the versions of ZeroTier itself.

We respect the version bump of ZeroTier though, so a new minor version of ZeroTier would be at least a minor version here, and major would be major.
