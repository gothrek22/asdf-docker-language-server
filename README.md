<div align="center">

# asdf-docker-language-server [![Build](https://github.com/gothrek22/asdf-docker-language-server/actions/workflows/build.yml/badge.svg)](https://github.com/gothrek22/asdf-docker-language-server/actions/workflows/build.yml) [![Lint](https://github.com/gothrek22/asdf-docker-language-server/actions/workflows/lint.yml/badge.svg)](https://github.com/gothrek22/asdf-docker-language-server/actions/workflows/lint.yml)

[docker-language-server](https://github.com/docker/docker-language-server) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Install

Plugin:

```shell
asdf plugin add docker-language-server
# or
asdf plugin add docker-language-server https://github.com/gothrek22/asdf-docker-language-server.git
```

docker-language-server:

```shell
# Show all installable versions
asdf list-all docker-language-server

# Install specific version
asdf install docker-language-server latest

# Set a version globally (on your ~/.tool-versions file)
asdf global docker-language-server latest

# Now docker-language-server commands are available
docker-language-server --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/gothrek22/asdf-docker-language-server/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Tom Lagodzinski](https://github.com/gothrek22/)
