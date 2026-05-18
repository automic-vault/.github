![Automic Vault](../profile.webp)

# Automic Vault

Package manager, secrets manager, and execution control plane for autonomous
agents on macOS.

[Website][website] | [Docs][docs] | [Main Repo][repo] | [Latest Release][release]

> [!IMPORTANT]
> Automic Vault is not affiliated with any cryptocurrency or token.

## Install

```sh
$ curl -fsSL https://automicvault.com/install.sh | sh -x
# ^^ downloads the DMG, lets Gatekeeper inspect it, checks our Team ID, then
#    copies the app into /Applications

+ /usr/bin/curl -sSfL https://automicvault.com/AutomicVault.dmg -o "$tmp/av.dmg"
+ /usr/sbin/spctl -a -vv --type open "$tmp/av.dmg"
+ /usr/bin/codesign -dv --verbose=4 "$app"
+ /usr/bin/ditto "$app" "/Applications/$(basename "$app")"
```

If `curl | sh` gives you hives, fair. Read it first:

```sh
curl -fsSL https://automicvault.com/install.sh | code -
```

Or download the DMG from [GitHub releases][release].

## Why This Exists

Developer machines are filling up with autonomous agents that can read files,
run tools, and use credentials intended for a human sitting at the keyboard.

Most agent security controls live inside the agent. Automic Vault puts a
boundary underneath it: the packages, secrets, and commands the agent tries to
use.

Use it when you need:

- installed tools that are harder for an agent or script to silently mutate
- secrets kept out of plaintext files, dotfiles, and model-readable context
- approval gates for high-risk operations
- local protection for credentials used by GitHub CLI, AWS CLI, MCP servers,
  package managers, and automation tools

> [!NOTE]
> Automic Vault is the local runtime layer. It is not trying to replace every
> enterprise secrets platform, MDM product, or security policy your company has
> already spent six quarters arguing about.

## What We Ship

| Project | What it is |
| --- | --- |
| [`automic-vault`][repo] | macOS app, CLI, package manager, secrets manager, and approval gate system |
| [`radioisotopes`][radioisotopes] | manifests for patched and agent-aware tool wrappers |
| [`www.automicvault.com`][website] | docs, install flow, and security notes |

## The Shape of It

```text
agent
  |
  v
approval gate  ->  human says yes/no
  |
  v
tool wrapper
  |
  v
controlled package + secret access
```

The goal is not to make agents harmless. No. The goal is to stop every local
agent session from automatically inheriting the full authority of your shell,
your `$HOME`, and every credential a CLI has ever stashed away.

## Platform

Automic Vault is macOS-first today.

> [!NOTE]
> The main project has public milestones for Linux and Windows support. Until
> those land, assume this is for macOS developers and agent workflows.

## Start Here

- [Read the main README][repo] if you want the product model.
- [Open the docs][docs] if you want to configure it.
- [Install the latest release][release] if you want to try it.

Built by [mxcl][mxcl], creator of Homebrew.

[docs]: https://automicvault.com/docs/
[mxcl]: https://mxcl.dev
[radioisotopes]: https://github.com/automic-vault/radioisotopes
[release]: https://github.com/automic-vault/automic-vault/releases/latest
[repo]: https://github.com/automic-vault/automic-vault
[website]: https://automicvault.com
