# JSON Lens

A polished, private-in-browser JSON comparison tool. Paste two documents, compare their structure, inspect exact paths, and copy a plain-text change report.

## Features

- Reports added, removed, and changed values in nested objects and arrays.
- Ignores object key order and compares arrays by index.
- Validates each document and shows parse errors independently.
- Uses text-only DOM rendering for untrusted JSON values.
- Works on desktop and mobile, with no dependencies or server calls.

## Run

Open `index.html` in a modern browser. Click **Load sample** to try it. No install or build step is needed.

## Tradeoffs

Array reordering appears as index changes because JSON arrays are ordered. Very large documents may produce long reports.

MIT licensed.
