# Bolt's Performance Journal

## 2025-10-16 - Event Delegation and DOM Caching for Dynamic Forms
**Learning:** Attaching multiple `input` and `change` event listeners to individual form controls causes redundant handlers and excess listeners. Event delegation on container elements combined with cached element arrays reduces listener overhead and avoids DOM querying on every input event.
**Action:** Use event delegation on form/container elements for calculating real-time totals.
