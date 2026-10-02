# Verus Holiday Data

Public, data-only update feed for Verus Calendar.

This repository intentionally contains no Verus application source code, artwork, signing material, credentials, or private project files. The published JSON is consumed by released Verus clients as an optional update to their built-in holiday catalog.

The app validates schema, revision, record count, date format, allowed rule IDs, and HTTPS transport before accepting an update. If this feed is unavailable or invalid, Verus continues using its last known-good or bundled catalog.
