# Built-in features for curve-studio-os

Purpose: vector illustration

1. **prepare a creative project** — run curve-studio-os-workspace. It creates ~/Documents/curve-studio-os-workspace/ with Briefs, Working Files, Exports folders.
2. **plan a production session** — run curve-studio-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/curve-studio-os-session-plans/.
3. **check project and export readiness** — run curve-studio-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/curve-studio-os-workspace features/curve-studio-os-plan features/curve-studio-os-check "$HOME/.local/bin/"
