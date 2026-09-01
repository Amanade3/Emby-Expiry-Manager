# Changelog

## 1.2.0.0

**New**
- "Leaving Soon" collection sync: optionally mirrors the delete queue into a real Emby
  collection so it's browsable like any other collection in the library.
  - New Settings tab section — toggle on/off, and a customizable collection name
    (default: "Leaving Soon").
  - Fully managed membership: the collection always mirrors the queue exactly. Items are
    added the moment they're queued, and removed the moment they're un-queued or deleted
    by the scheduler. Renaming the collection starts a fresh one; the old one (if any) is
    left behind to delete manually.

**Fixed**
- Resolved a possible-null-reference warning (CS8603) on `GetThumbImage()`.

## 1.1.0.0
- Prior release (baseline for this changelog).
