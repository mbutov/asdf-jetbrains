# asdf-jetbrains [![Build](https://github.com/mbutov/asdf-jetbrains/actions/workflows/build.yml/badge.svg)](https://github.com/mbutov/asdf-jetbrains/actions/workflows/build.yml) [![Lint](https://github.com/mbutov/asdf-jetbrains/actions/workflows/lint.yml/badge.svg)](https://github.com/mbutov/asdf-jetbrains/actions/workflows/lint.yml)

[jetbrains](https://github.com/mbutov/asdf-jetbrains) plugin for the [asdf version manager](https://asdf-vm.com).

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `jq` - commandline JSON processor

# Install

## Plugin:

```shell
asdf plugin add jetbrains
# or
asdf plugin add jetbrains https://github.com/mbutov/asdf-jetbrains.git
```

## jetbrains:

```shell
# Show help
asdf jetbrains
```

Output:
```text
ASDF JetBrains plugin
USAGE
  asdf jetbrains list             # List jetbrains products
  asdf jetbrains add <product>    # Add ASDF plugin for JetBrains product
  asdf jetbrains remove <product> # Remove ASDF plugin for JetBrains product
EXAMPLE
  asdf jetbrains add idea         # Add ASDF plugin for JetBrains IDEA
  asdf list all idea              # List versions of JetBrains IDEA
  asdf install idea latest        # Install latest version of JetBrains IDEA
  asdf global idea latest         # Set global version of JetBrains IDEA
  idea                            # Run JetBrains IDEA
JetBrains products:
  clion      - CLion
  datagrip   - DataGrip
  dataspell  - DataSpell
  gateway    - Gateway
  goland     - GoLand
  idea       - IntelliJ IDEA Ultimate
  ideac      - IntelliJ IDEA Community Edition
  mps        - MPS
  phpstorm   - PhpStorm
  pycharm    - PyCharm Professional Edition
  pycharmc   - PyCharm Community Edition
  rider      - Rider
  rideru     - Rider for Unreal Engine
  rubymine   - RubyMine
  webstorm   - WebStorm
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/mbutov/asdf-jetbrains/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Maxim Butov](https://github.com/mbutov/)
