# homebrew-zapinator

Homebrew tap for **NOTCH-ZAP-INATOR**: your MacBook's notch turns into a
cartoon mad scientist's lair every time the charger goes in. A bolt shoots
out, the notch bursts open, a villain line types itself out next to your
battery percentage, and it snaps shut again. Unplug and it droops. Hit 100%
and it celebrates.

```sh
brew install --cask kunalbagaria/zapinator/zapinator
```

Needs an Apple Silicon MacBook with a notch and macOS 13+. It runs in the
background, starts at login, and mutes macOS's own charging chime while it's
installed (`brew uninstall --cask zapinator` puts everything back; add
`--zap` to remove its log too).

No Homebrew? `curl -fsSL https://zapinator.kunalbagaria.com | bash`

The cask is updated by the release script in the main project.
