## 2026-10-16 - Form Field Labeling & Target Area Enhancement

**Learning:** Static/printable HTML forms often miss `for`/`id` associations and use unassociated `<span>` tags next to checkboxes. This degrades screen reader accessibility and creates small click targets.
**Action:** Wrap checkboxes in `<label>` elements with flex layouts and explicitly connect `<label for="...">` with `<input id="...">` to improve accessibility and clickability simultaneously.
