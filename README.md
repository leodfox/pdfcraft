# Ardoise PDF (web editor, fork of pdfcraft)

Web build of the Ardoise editor "Ardoise PDF", based on PdfCraft by Learning Machines LLC (MIT OR Apache-2.0).
Branch `ardoise` starts from upstream tag v0.6.0 (https://github.com/storytold/pdfcraft).

Changes in this fork: postMessage bridge for same-origin iframe embedding (`apps/pdfcraft-web/src/bridge.rs`),
Ardoise branding in the UI (the upstream name, wordmark and logos are not used), single web-only CI
workflow (`.github/workflows/web.yml`) that builds the wasm bundle and attaches the zip to a GitHub release.

Build the web bundle: see `packaging/web/README.md` and `packaging/web/package.sh`.

Licences: see LICENSE-APACHE, LICENSE-MIT and NOTICE. The copyright notices of the original authors are kept.
