P05B3 — SEARCH HISTORY DROPDOWN FIXED

Source:
- Built directly from the exact P05 package files supplied by the user after P05B2 was found to contain the old visible Recent row.

Locked behavior retained:
- P04 OFFLINE PWA functionality.
- P05A Results Position Restore.
- Search history storage: max 20, newest first, duplicate moved to top, localStorage/offline.

Fixed UI:
- No permanent Recent row.
- Search history is anchored inside/below the keyword input.
- Tap/focus keyword input: dropdown opens if history exists.
- Tap a saved keyword: fills it and searches immediately.
- Type a new keyword normally; dropdown closes while typing.
- Tap outside: dropdown closes.
- Clear deletes history and closes dropdown.

Cache version:
pdf-read-search-p05b3-v1
