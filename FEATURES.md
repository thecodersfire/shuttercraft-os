# Built-in features for shuttercraft-os

Purpose: photography

1. **prepare a creative project** — run shuttercraft-os-workspace. It creates ~/Documents/shuttercraft-os-workspace/ with Briefs, Working Files, Exports folders.
2. **plan a production session** — run shuttercraft-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/shuttercraft-os-session-plans/.
3. **check project and export readiness** — run shuttercraft-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/shuttercraft-os-workspace features/shuttercraft-os-plan features/shuttercraft-os-check "$HOME/.local/bin/"
