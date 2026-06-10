# Hi, I'm Diego 💃

Senior iOS engineer at [Numan](https://www.numan.com/). Previously: [Babylon Health](https://www.babylonhealth.com), [Plum](https://withplum.com).

I live in London, UK, but am originally from Tuscany, in Italy. Find me dancing salsa and bachata after work! 💃

### Writing

Sometimes [I write about AI and software engineering](https://diegopetrucci.github.io/dev/), sometimes [I write about life](https://diegopetrucci.it/blog).

### Projects

A few things I've been building:

- [**the last harness**](https://github.com/diegopetrucci/the-last-harness) — an opinionated [pi](https://github.com/earendil-works/pi-mono)-based agent harness with primary agents, subagents, context management, safety rails, and install/update tooling.
- [**pi-assistant**](https://github.com/diegopetrucci/pi-assistant) — use a Raspberry Pi as a voice AI assistant.
- [**claudio**](https://github.com/diegopetrucci/claudio) — a Swift & Vapor reimplementation of OpenClaw.

### AI skills

Skill issue?

- [**ai-agents-skills**](https://github.com/diegopetrucci/ai-agents-skills) — the main collection of agent skills, Claude Code plugins, and Codex plugins I maintain.
  - [**agent-workflow-audit**](https://github.com/diegopetrucci/agent-workflow-audit) — audits a repo's agent workflow for wasted steps and unclear instructions.
  - [**github-librarian**](https://github.com/diegopetrucci/github-librarian) — researches GitHub code with `gh`, returning path-first findings with line evidence.
  - [**illustrations-to-explain-things**](https://github.com/diegopetrucci/illustrations-to-explain-things) — turns articles and workflows into clean, absurd Xiaohei-style explainer illustrations.
  - [**ios-agents-skills**](https://github.com/diegopetrucci/ios-agents-skills) — skills focused on iOS and Apple platform development.
  - [**odds-api-io**](https://github.com/diegopetrucci/odds-api-io) — gives agents access to sports odds via Odds-API.io.
  - [**pr-comments-triage**](https://github.com/diegopetrucci/pr-comments-triage) — checks whether PR review comments are actually valid before fixing anything.
  - [**prd-interviewer**](https://github.com/diegopetrucci/prd-interviewer) — builds a PRD through a focused, one-question-at-a-time interview.
  - [**rebase-and-fix-conflicts**](https://github.com/diegopetrucci/rebase-and-fix-conflicts) — rebases onto `main` and resolves conflicts while preserving branch intent.
  - [**remove-ai-code-slop**](https://github.com/diegopetrucci/remove-ai-code-slop) — cleans up telltale AI-generated code patterns.
  - [**sentry-cli**](https://github.com/diegopetrucci/sentry-cli) — gives agents tools to interface with Sentry's error reporting.
  - [**starting-from-scratch**](https://github.com/diegopetrucci/starting-from-scratch) — reviews a codebase's history and says what should change if you were starting again.
  - [**tfl-journey-disruption**](https://github.com/diegopetrucci/tfl-journey-disruption) — plans London journeys and warns about TfL disruptions.

### Pi extensions

I've also started publishing [**extensions for pi**](https://github.com/diegopetrucci/pi-extensions), my current agent harness of choice:
  - [**agent-workflow-audit**](https://github.com/diegopetrucci/pi-extensions/tree/main/extensions/agent-workflow-audit) — runs an isolated repo workflow audit subagent and returns a distilled report.
  - [**annotate-git-diff**](https://github.com/diegopetrucci/pi-extensions/tree/main/extensions/annotate-git-diff) — opens a native review UI for annotating git diffs and sending structured feedback back to the agent.
  - [**annotate-last-message**](https://github.com/diegopetrucci/pi-extensions/tree/main/extensions/annotate-last-message) — opens a native review UI for annotating the latest assistant reply.
  - [**brrr**](https://github.com/diegopetrucci/pi-extensions/tree/main/extensions/brrr) — sends brrr push notifications when pi is ready for input.
  - [**claude-fast**](https://github.com/diegopetrucci/pi-extensions/tree/main/extensions/claude-fast) — adds `/claude-fast` controls for supported Claude Opus Fast mode.
  - [**confirm-destructive**](https://github.com/diegopetrucci/pi-extensions/tree/main/extensions/confirm-destructive) — confirms destructive session actions like clear, switch, and fork.
  - [**context-cap**](https://github.com/diegopetrucci/pi-extensions/tree/main/extensions/context-cap) — caps effective model context windows to avoid the `dumb zone`.
  - [**context-inspector**](https://github.com/diegopetrucci/pi-extensions/tree/main/extensions/context-inspector) — generates a local dashboard showing where the current session context is going.
  - [**dirty-repo-guard**](https://github.com/diegopetrucci/pi-extensions/tree/main/extensions/dirty-repo-guard) — prompts before session actions when the current repo has uncommitted changes.
  - [**git-footer**](https://github.com/diegopetrucci/pi-extensions/tree/main/extensions/git-footer) — adds compact git status, ahead/behind, and optional PR details to pi's footer.
  - [**gnosis**](https://github.com/diegopetrucci/pi-extensions/tree/main/extensions/gnosis) — exposes the `gn` repo-local knowledge base CLI as an agent tool.
  - [**inline-bash**](https://github.com/diegopetrucci/pi-extensions/tree/main/extensions/inline-bash) — expands trusted `!{command}` snippets before the prompt reaches the agent.
  - [**illustrations-to-explain-things**](https://github.com/diegopetrucci/pi-extensions/tree/main/extensions/illustrations-to-explain-things) — generates Xiaohei-style article illustrations, shot lists, image edits, and visual metaphors.
  - [**librarian**](https://github.com/diegopetrucci/pi-extensions/tree/main/extensions/librarian) — adds a cached GitHub research scout for path-first code findings.
  - [**minimal-footer**](https://github.com/diegopetrucci/pi-extensions/tree/main/extensions/minimal-footer) — a minimal two-line footer with branch/repo, context/model, and OpenAI Codex usage.
  - [**notify**](https://github.com/diegopetrucci/pi-extensions/tree/main/extensions/notify) — terminal, desktop, bell, and sound notifications when pi is ready for input.
  - [**openai-fast**](https://github.com/diegopetrucci/pi-extensions/tree/main/extensions/openai-fast) — adds `/fast` controls for OpenAI Codex Fast mode.
  - [**oracle**](https://github.com/diegopetrucci/pi-extensions/tree/main/extensions/oracle) — a read-only oracle tool that selects the strongest reasoning model on the current provider/subscription.
  - [**permission-gate**](https://github.com/diegopetrucci/pi-extensions/tree/main/extensions/permission-gate) — confirms dangerous bash commands like `rm -rf`, `sudo`, and `chmod 777`.
  - [**quiet-tools**](https://github.com/diegopetrucci/pi-extensions/tree/main/extensions/quiet-tools) — renders collapsed built-in tool rows as compact one-line invocations.
  - [**review**](https://github.com/diegopetrucci/pi-extensions/tree/main/extensions/review) — adds interactive review flows for local changes, commits, PRs, and selected paths.
  - [**todo**](https://github.com/diegopetrucci/pi-extensions/tree/main/extensions/todo) — adds a branch-aware `todo` tool and a `/todos` viewer.
  - [**triage-comments**](https://github.com/diegopetrucci/pi-extensions/tree/main/extensions/triage-comments) — checks PR review comments for validity before implementing anything.

### Dotfiles

If you're curious about how I set my machines up:
- [**dot**](https://github.com/diegopetrucci/dot) — my public dotfiles

### Get in touch

- Twitter [@diegopetrucci](https://twitter.com/diegopetrucci)
- Mastodon [@diegopetrucci](https://mastodon.social/@diegopetrucci)
- LinkedIn [diegopetrucci](https://www.linkedin.com/in/diegopetrucci/)
