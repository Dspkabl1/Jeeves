# Jeeves Instructions
- **Access:** Start chats with “Hey [Persona]” (e.g., “Hey Nerd”)—Grok 3 grabs from `personas/`.
- **Update:** “update” triggers Grok to analyze `history/conversations.json`, suggest persona tweaks.
- **History:** Logs in `history/`—JSON, manually update after chats for now.
- **Versioning:** Git commits—track changes, revert with `git checkout <hash>`.
- **Feedback:** Grok reviews history, evolves personas—commit updates to `personas/`.