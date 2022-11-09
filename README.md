# zsh-yarn-completion

A zsh plugin provides completion for `yarn`.

Use any plugin manager for installation.

```zsh
# antigen
antigen bundle mkobayashime/zsh-yarn-completion

# zplug
zplug "mkobayashime/zsh-yarn-completion"
```

## Requirements

[`jq`](https://stedolan.github.io/jq/) must be installed.

## Features

Provides completion of the name of all top level commands (e.g. `init`/`add`/`upgradeInteractive`).

After the top level command:

|Command|Completion|
|---|---|
|`remove`|Packages in `dependencies` or `devDependencies`|
|`run`|Yarn scripts|
|`upgrade`|Packages in `dependencies` or `devDependencies`|
