# brew-windows bottles

Prebuilt Windows packages ("bottles") for [brew-windows](https://github.com/SamuelArther/brew-windows).
Each formula version is a release here named `<formula>-<version>`, holding its
`.x86_64_windows.bottle.tar.gz` file. `brew install` downloads them automatically and checks each one against the
SHA-256 recorded in the formula, so there's nothing to do here by hand.

Bottles are built and tested by brew-windows' GitHub Actions workflows from Homebrew's
[homebrew-core](https://github.com/Homebrew/homebrew-core) formulae. Each package keeps its own license.
