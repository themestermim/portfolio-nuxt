# Project Agent Instructions

## Scope

These instructions apply to the entire project unless a more specific `AGENTS.md` exists in a subdirectory.

## Code readability

- Keep JavaScript, TypeScript, Vue templates, and other source code formatted for humans to read.
- Do not minify, compress, or otherwise shorten source code after writing it.
- Use line breaks and indentation wherever they improve readability, especially in long attributes, function calls, conditionals, object literals, arrays, and chained expressions.
- Keep one logical concern per line when practical; do not sacrifice clarity to reduce line count.
- Preserve readable spacing and blank lines between related sections.
- Do not use unnecessarily terse variable or function names.

## Vue and Nuxt

- Prefer Vue reactivity and template bindings over manual DOM queries and direct class manipulation.
- Keep component templates semantic and accessible.
- Add accessible labels and state attributes to interactive controls where needed.
- Follow the existing project conventions before introducing new patterns or dependencies.

## Changes and verification

- Make focused changes that address the requested task without unrelated refactors.
- Before finishing, review the diff for accidental formatting or generated/minified code.
- Run the most relevant available checks, such as lint, type-check, build, or tests, and report warnings separately from actual errors.

## Frontend styling

- For frontend styling, use the Tailwind CSS version already installed and configured in this project.
- Prefer Tailwind utility classes in Vue templates and existing project design tokens over writing raw CSS.
- Do not add a new styling framework or change the Tailwind version unless explicitly requested.
- Write custom CSS only when the required behavior cannot be expressed cleanly with the installed Tailwind utilities, or when it is needed for a reusable project-level pattern.
- Keep any necessary custom CSS focused, readable, and colocated with the relevant component or stylesheet.
