# CodeKids

A browser-based coding learning platform with staged lessons, saved learner progress, projects, games, achievements, a safe simulated Builder Terminal, and the integrated Code Studio.

## Code Studio
- File explorer for local project files.
- HTML/CSS/JavaScript editor with a sandboxed live preview.
- Saves workspace files in the browser on the learner's device.
- Download project files to keep a copy.
- Optional Python playground powered by Pyodide in a Web Worker. The first Python run needs an internet connection to load the runtime from its CDN.

## Publish with GitHub Pages
Upload `index.html` and `README.md` to the root of the existing repository and commit to the `main` branch. Keep GitHub Pages configured to deploy from `main` and `/(root)`.

## Important safety notes
The CodeKids terminal remains a simulated educational terminal and does not run operating-system commands. Web projects run in a sandboxed iframe. Python runs in a browser worker through Pyodide; it is not a server-side execution service and should not be treated as a hardened environment for untrusted production workloads.

## Storage
Learning progress and workspace files are saved in the browser's local storage on the current device/browser. Learners should download their project files to back them up or move them to another device.
