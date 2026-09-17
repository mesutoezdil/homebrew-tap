# homebrew-tap

Homebrew formulae for [accel](https://github.com/mesutoezdil/accel), the terminal monitor for GPUs, NPUs, and other AI accelerators.

```sh
brew install mesutoezdil/tap/accel
```

`Formula/accel.rb` is rendered by `scripts/update.sh` from the newest accel release and refreshed by a workflow every 6 hours. It points at a stable release when one exists and at the newest `main` pre-release until then.
