# homebrew-tap

Homebrew formula for [MLVM](https://github.com/yao-jz/mlvm), a deterministic RISC-V virtual
machine for machine learning.

```bash
brew install yao-jz/tap/mlvm
mlvm demo "Once upon a time"
```

`Formula/mlvm.rb` installs the prebuilt release binary for macOS and Linux, on arm64 and
amd64. MLVM's release workflow regenerates it from each release's checksums, so please open
issues and changes in [yao-jz/mlvm](https://github.com/yao-jz/mlvm).
