# Cold Open's Homebrew tap

[Cold Open](https://theyungstump.github.io/cold-open/) is a free, open-source screenwriting app. It reads and writes Fountain and Final Draft (.fdx) files, works offline and never loses work.

## Install

```
brew tap theyungstump/tap
brew trust theyungstump/tap
brew install --cask cold-open
```

Homebrew 6 asks you to trust a tap that isn't Homebrew's own once, with `brew trust`.

Cold Open isn't notarized by Apple yet, so macOS refuses it the first time. Open System Settings > Privacy & Security, click "Open Anyway", then open Cold Open again.

The cask also puts the `coldopen` command-line tool on your path.

## Update

```
brew upgrade --cask cold-open
```

## About this tap

The cask comes from each release of [TheYungStump/cold-open](https://github.com/TheYungStump/cold-open), where it's checked with `brew style` and `brew audit`. Report problems there.
