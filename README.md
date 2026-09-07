# Agent skills

Reusable coding conventions for Next.js, JavaScript, and TypeScript, extracted from [og-tools](https://github.com/DanielFryy/og-tools).

## Skills

| Skill                                                                                  | What it covers                                                                                   |
| -------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------ |
| [next-page-composition](skills/next-page-composition/SKILL.md)                         | Server-first App Router pages, metadata, colocated component files, JSX handlers, and props.     |
| [javascript-typescript-conventions](skills/javascript-typescript-conventions/SKILL.md) | Body destructuring, guard clauses, explicit multiline function bodies, and functions in objects. |

These are opinionated coding conventions. The Next.js skill adapts paths, package manager commands, and test helpers to the target project. Install both for the full convention set, or select either skill independently.

## Install

Run in the project where you want the skills:

```sh
bunx skills add DanielFryy/agent-skills --skill next-page-composition --skill javascript-typescript-conventions
```

To install only one:

```sh
bunx skills add DanielFryy/agent-skills --skill javascript-typescript-conventions
```

Add `--agent codex` to target Codex, or `--global` to install at user scope. The CLI lets you choose agents interactively when the agent option is omitted. You can also run the same commands with `npx` in projects that use npm.

## Updates

```sh
bunx skills update
```

## Discovery on skills.sh

According to the [skills.sh FAQ](https://skills.sh/docs/faq), skills are hosted on GitHub and appear in the directory through anonymous installation telemetry from the skills CLI. Publishing this repository makes the skills installable; directory visibility depends on the service indexing installation activity.
