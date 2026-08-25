---
name: "awesome-projects"
description: "Discover curated open-source projects and resources from the live awesome-projects collection."
---

# Awesome Projects

Use the live `awesome-projects` repository as a curated discovery index. Always read the current list instead of assuming fixed categories or entries.

## Workflow

1. Fetch the current English list:

   ```bash
   curl -fsSL https://raw.githubusercontent.com/ningzimu/awesome-projects/main/README.md
   ```

   If `curl` is unavailable, use:

   ```bash
   wget -qO- https://raw.githubusercontent.com/ningzimu/awesome-projects/main/README.md
   ```

2. Search the relevant sections using the user's goal, platform, inputs, constraints, budget, and preferred license.
3. Inspect each serious candidate's original repository. Verify its purpose, maintenance status, license, platform support, and installation instructions from primary sources.
4. Shortlist only candidates that materially fit. Explain the trade-offs briefly and link to the original repositories.
5. If the user asks to install or run a project, follow its official documentation and treat third-party setup scripts as untrusted until inspected.

## Boundaries

- Use `awesome-skills` for Agent Skills and `awesome-ai-ppt` for AI presentation resources.
- Do not recommend an entry solely because it appears in the list; verify the source repository first.
- Distinguish public repositories from repositories with an explicit open-source license.
- Verify volatile facts such as stars, releases, archival status, and compatibility in real time.
