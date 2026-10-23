---
title: Install
description: Install the user-agreements skill in Claude Code as a plugin from its marketplace, with the skills command line tool, or by copying its folder.
---

# Install

The skill runs in Claude Code. You can add it as a plugin, with the `skills` command line tool, or by copying its
folder. The plugin route is the only one that updates itself.

## As a Claude Code plugin

In a terminal (PowerShell, bash or zsh):

```
claude plugin marketplace add nghorbani/user-agreements-skill
claude plugin install user-agreements@user-agreements-skill
```

Or inside a Claude Code session:

```
/plugin marketplace add nghorbani/user-agreements-skill
/plugin install user-agreements@user-agreements-skill
```

Restart Claude Code afterwards. The skill starts when a request matches what it does, for example "draft terms of
service for our app" or "check our cancellation flow against German law". If it does not start, name it in your
request: "Use the user-agreements skill to draft our subscription terms."

To update, then restart:

```
claude plugin marketplace update user-agreements-skill
claude plugin update user-agreements@user-agreements-skill
```

To remove:

```
claude plugin uninstall user-agreements@user-agreements-skill
claude plugin marketplace remove user-agreements-skill
```

## With the skills command line tool

This route needs Node.js for `npx`.

```
npx skills add nghorbani/user-agreements-skill -a claude-code
```

That installs the skill into the current project (`.claude/skills/user-agreements`). Add `-g` to install it for your
user account instead (`~/.claude/skills/user-agreements`).

## By copying the folder

The skill is a folder of Markdown files: `SKILL.md` with its references and templates. Copy
`plugins/user-agreements/skills/user-agreements` from the repository into your skills folder.

=== "PowerShell"

    ```powershell
    git clone https://github.com/nghorbani/user-agreements-skill.git
    New-Item -ItemType Directory -Force "$env:USERPROFILE\.claude\skills" | Out-Null
    Copy-Item -Recurse user-agreements-skill\plugins\user-agreements\skills\user-agreements "$env:USERPROFILE\.claude\skills\user-agreements"
    ```

=== "bash"

    ```bash
    git clone https://github.com/nghorbani/user-agreements-skill.git
    mkdir -p ~/.claude/skills
    cp -r user-agreements-skill/plugins/user-agreements/skills/user-agreements ~/.claude/skills/
    ```

## What gets installed

Markdown files only. The skill contains no scripts, makes no network calls of its own and runs nothing when you
install it.
