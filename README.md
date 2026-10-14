# Agent skills

Reusable coding conventions for JavaScript, TypeScript, React, and Next.js, extracted from [og-tools](https://github.com/DanielFryy/og-tools). The React conventions also apply to React Native and Expo.

## Skills

| Skill | What it covers |
| --- | --- |
| [javascript-typescript-conventions](skills/javascript-typescript-conventions/SKILL.md) | Blank lines, declaration order, named constants before default exports, compact objects and types, body destructuring, long string extraction, guard clauses, conditional braces, and function bodies. |
| [react-component-conventions](skills/react-component-conventions/SKILL.md) | Component files, readonly props, JSX handlers, conditional rendering, prop passing, and tests for React web, React Native, and Expo. |
| [next-page-composition](skills/next-page-composition/SKILL.md) | Server-first App Router pages, metadata, shared page/layout props, and client boundaries. |

These are opinionated coding conventions. Each skill can be used independently. For React, React Native, or Expo, install the JavaScript/TypeScript and React skills. Add the Next.js skill for Next.js App Router projects. Paths, package manager commands, styling, and test helpers adapt to the target project.

General React guidance previously included in `next-page-composition` now lives in `react-component-conventions`. Existing Next.js users should install the React skill as well to retain that guidance.

## Install

Run in the project where you want the skills. For React, React Native, or Expo:

```sh
npx skills add DanielFryy/agent-skills --skill javascript-typescript-conventions --skill react-component-conventions
```

For Next.js:

```sh
npx skills add DanielFryy/agent-skills --skill javascript-typescript-conventions --skill react-component-conventions --skill next-page-composition
```

To install only one:

```sh
npx skills add DanielFryy/agent-skills --skill javascript-typescript-conventions
```

Add `--agent codex` to target Codex, or `--global` to install at user scope. The CLI lets you choose agents interactively when the agent option is omitted.

## Updates

```sh
npx skills update
```

## Discovery on skills.sh

According to the [skills.sh FAQ](https://skills.sh/docs/faq), skills are hosted on GitHub and appear in the directory through anonymous installation telemetry from the skills CLI. Publishing this repository makes the skills installable; directory visibility depends on the service indexing installation activity.
