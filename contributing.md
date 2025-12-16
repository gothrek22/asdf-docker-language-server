# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test docker-language-server https://github.com/gothrek22/asdf-docker-language-server.git "docker-language-server --help"
```

Tests are automatically run in GitHub Actions on push and PR.
