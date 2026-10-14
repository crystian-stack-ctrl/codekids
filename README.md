# CodeKids — Complete Learning Platform

A beginner-friendly coding platform for learners, including step-by-step lessons, progress tracking, games, project ideas, a multi-file web Code Studio, live preview, browser-based Python support, and a virtual command-line terminal.

## Publish to GitHub Pages
1. Download and unzip this project.
2. Open your existing `codekids` repository on GitHub.
3. Choose **Add file → Upload files**.
4. Upload `index.html` and `README.md` from this folder, replacing the existing files when prompted.
5. Commit directly to the `main` branch.
6. Wait for GitHub Pages to finish deploying, then refresh your site.

Keep GitHub Pages set to deploy from `main` and the `/ (root)` folder.

## Terminal learning lab
The terminal simulates a small virtual filesystem. It supports common learning commands including `pwd`, `ls`, `cd`, `tree`, `mkdir`, `touch`, `cat`, `less`, `head`, `tail`, `echo`, `printf`, `grep`, `find`, `wc`, `rm`, `rmdir`, `cp`, `mv`, `history`, `clear`, `whoami`, `hostname`, `uname`, `date`, `env`, `which`, `help`, `man`, `about`, and `run`. It also supports basic `>` and `>>` output redirection.

**Important:** This is an educational simulation, not a real shell. It cannot run every Windows/Linux/macOS command, install packages, use `sudo`, or access/modify files on the learner's computer. That is deliberate: a browser page should not pretend to provide unrestricted local terminal access. Commands and files are stored in browser local storage on that device.

## Code Studio
Code Studio provides a local browser workspace for HTML/CSS/JavaScript with live preview and local browser storage. Python execution uses Pyodide from a CDN and needs an internet connection when the runtime loads. Browser storage is per browser/device; it is not cloud synchronization.

## Privacy and safety
Learner progress and workspace files are stored locally in the browser. Clearing site data can remove this local information. Do not enter passwords or private information into learning exercises.

## 50-stage learning path
The learning path now contains 50 sequential stages spanning Python fundamentals, data structures, functions, file handling, terminal navigation commands, HTML, CSS, JavaScript, Git, and a final project. Progress is stored in the learner’s browser. The terminal lessons explain real command concepts; the website simulator does not execute arbitrary commands on the learner’s computer.


## Codey Chatbot
The Codey Chatbot is a child-friendly, rule-based helper for beginner coding concepts and common maths questions. It works locally in the browser and does not send chat messages to a server. It is not connected to a live AI model and cannot answer every possible question; unknown questions receive suggestions for supported topics. Never ask learners to share passwords, home addresses, phone numbers, or other private information.

To publish: upload `index.html` and `README.md` to the root of your existing GitHub Pages repository, replacing the previous versions, and commit to the `main` branch. Keep a backup of your previous files. After Pages deploys, hard-refresh the website with Ctrl+Shift+R.
