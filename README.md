# Homebrew tap for [zap](https://github.com/elbywan/zap)

```bash
brew install elbywan/zap/zap
```

Use the fully qualified name: an unrelated cask named `zap` exists in homebrew-cask, and the bare `brew install zap` would resolve to that one.

Homebrew asks you to confirm the tap the first time (or `brew trust elbywan/zap` up front, needed non-interactively).

`Formula/zap.rb` is generated from the latest [zap release](https://github.com/elbywan/zap/releases) by [the update workflow](.github/workflows/update-formula.yml), which runs hourly and on demand — do not edit it by hand.

The formula installs the published binaries, for Apple silicon macOS and x86_64 Linux.
