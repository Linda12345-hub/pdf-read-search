P05B2 — SEARCH HISTORY DROPDOWN
Baseline: P05A PASS + P05B search-history storage logic.

UI change:
- Recent Searches is hidden by default.
- Tap/focus the keyword input to open the dropdown if history exists.
- Tap an existing term to search it immediately.
- Type a new term normally if it is not in history.
- Typing or tapping outside closes the dropdown.
- Clear deletes all history and closes the dropdown.
- Up to 20 recent searches; duplicates are moved to top.
- History remains offline via localStorage.

P05A Results Position Restore and all P04 offline functionality remain unchanged.
