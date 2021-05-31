<div align="center">

# asdf-mitmproxy ![Build](https://github.com/NeoHsu/asdf-mitmproxy/workflows/Build/badge.svg) ![Lint](https://github.com/NeoHsu/asdf-mitmproxy/workflows/Lint/badge.svg)

[mitmproxy](https://mitmproxy.org/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add mitmproxy
# or
asdf plugin add mitmproxy https://github.com/NeoHsu/asdf-mitmproxy.git
```

mitmproxy:

```shell
# Show all installable versions
asdf list-all mitmproxy

# Install specific version
asdf install mitmproxy latest

# Set a version globally (on your ~/.tool-versions file)
asdf global mitmproxy latest

# Now mitmproxy commands are available
mitmproxy --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/NeoHsu/asdf-mitmproxy/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Neo Hsu](https://github.com/NeoHsu/)
