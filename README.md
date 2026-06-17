<p align="center">
  <img src="./assets/gitwig-icon.png" alt="Gitwig app icon" width="128">
</p>

# Gitwig

English | [한국어](./README.ko.md)

**A focused macOS Git client for people who live in branches.**

Gitwig brings repository history, working changes, branches, remotes, profiles, and GitHub account context into one calm desktop workspace.

Gitwig is freeware, not open source. The first public release is being prepared as `0.0.1`.

[Download](https://github.com/wookeon/gitwig/releases) | [Release Notes](./changelog) | [Issues](https://github.com/wookeon/gitwig/issues) | [Third-Party Notices](./THIRD_PARTY_NOTICES.md)

## Git, With Less Noise

Gitwig is a macOS Git desktop client for understanding repository state quickly and making changes with confidence.

As branches grow, histories get longer, and local changes pile up, Git work becomes less about typing commands and more about knowing exactly where everything is. Gitwig is built to reduce that context cost. It keeps your working changes, branch position, remote state, commit history, and file-level detail in one focused workspace.

## Who It Is For

- Developers who are comfortable with Git but want a clearer visual workspace
- macOS users who regularly move between branches, stashes, tags, submodules, and conflicts
- People who want separate author identities and accounts for personal and work projects
- Users who want more repository depth than a basic Git client without living inside an IDE

## What The First Release Includes

**See the shape of the repository.**  
Browse commit history, branch flow, merge summaries, working changes, and staged changes together. Long histories continue loading as you scroll, and important branch and commit information stays visually stable.

**Work through changes with confidence.**  
Stage and unstage files or hunks, inspect syntax-highlighted diffs, review file history and blame, add `.gitignore` rules, and resolve conflicts with continue, abort, and skip flows.

**Handle branch and remote workflows end to end.**  
Checkout, merge, rebase, cherry-pick, revert, reset, fetch, pull, push, set upstreams, and recover from rejected pushes from the desktop UI.

**Separate contexts with profiles.**  
Each Gitwig profile keeps its own commit author name and email, GitHub account state, recent repositories, and sidebar/file-tree expansion state. Personal and work contexts can stay separate inside one app.

**Practical Git workflows are included from day one.**  
The first public release includes stash operations, tag and remote-tag workflows, submodule add/update/sync/open, and conflict resolution support.

## Getting Started

1. Launch Gitwig and create a profile.
2. Connect GitHub if you need account-backed workflows. Credentials are stored in macOS Keychain.
3. Open or clone a repository.
4. Review history and working changes, then stage only what you need.
5. Commit and push.

## Download

Gitwig will be distributed through GitHub Releases.

- Download: [GitHub Releases](https://github.com/wookeon/gitwig/releases)
- First public version: `0.0.1`
- Requirement: macOS 26.0 or later

The first release has not shipped yet, so release assets may not be available.

## Feedback And Issues

Use [GitHub Issues](https://github.com/wookeon/gitwig/issues) for bug reports, feature requests, workflow improvements, and compatibility questions.

When reporting a bug, include the Gitwig version, macOS version, the Git operation involved, steps to reproduce, expected result, and actual result. Do not post repository URLs, access tokens, private commit contents, customer data, or logs that may contain secrets.

## Distribution And License

Gitwig is freeware, not open source. Trust only original builds distributed through official GitHub Releases.

- Source code is not distributed through this repository.
- The app, icon, brand, documentation, and release packages remain copyrighted.
- Included open source components remain governed by their own licenses.

See [`LICENSE`](./LICENSE) and [`THIRD_PARTY_NOTICES.md`](./THIRD_PARTY_NOTICES.md) for details.

## Privacy

Gitwig reads and operates on local repositories on your Mac. GitHub account connection uses OAuth device flow, and credentials are stored in macOS Keychain.
