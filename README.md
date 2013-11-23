# p
Package manager wrapper

**Note: This is currently just an idea**

### Features:
- Providers
- Mapping between types (e.g. turning sys:openssl-dev into pacman:openssl, apt:libssl-dev or yum:openssl-devel)

The one problem with mapping is there needs to be standard names.

`p i apt:git`: Install git using aptitude or apt-get
`p i npm:xcp`: Install xcp using npm
`p i sys:git`: Install git using whatever system level package manager is available (also some way of mapping between different package managers)
`p r sys:git`: Uninstall git
