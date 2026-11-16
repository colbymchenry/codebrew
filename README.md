# codebrew

codebrew takes you from a GitHub repository to a running app on your Mac, with an AI coding agent ready to work on it. It installs each project's tools inside `~/.codebrew`, so nothing else on your Mac changes, and it never needs `sudo`.

This repository holds codebrew's releases.

## Install

Open Terminal and paste:

```
curl -fsSL https://github.com/colbymchenry/codebrew/releases/latest/download/install.sh | sh
```

Then open a new Terminal window and get a project:

```
codebrew clone owner/repo
```

For an iOS app you also need Xcode, free from the Mac App Store.

## Keep it up to date

- `codebrew self update` installs the newest release.
- `codebrew self uninstall` removes codebrew and everything it installed.
