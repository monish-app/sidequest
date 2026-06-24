# How to Update the Side Quest Site

The live site is hosted on GitHub Pages at:
**https://monish-app.github.io/sidequest/**

The source file is `index.html` in this folder. Whenever it changes, follow these steps to publish.

## The update loop

1. **Edit the site.** Claude saves the updated `index.html` into this folder (the `Side Quest App` folder).

2. **Open GitHub Desktop.** It automatically detects the change — `index.html` appears under the **Changes** tab with the edits highlighted.

3. **Write a quick note.** In the message box (bottom left), type what changed, e.g. `Added quest deck section`.

4. **Click "Commit to main."** The blue button at the bottom left.

5. **Click "Push origin."** The button at the top of the window. This sends the change to GitHub.

6. **Wait ~1 minute.** The live site updates itself. Refresh the page to see the change.

That's the whole loop: **Commit → Push → wait a minute.** No Terminal, no file uploads, no setup to redo.

## Troubleshooting

- **Change not showing on the live site?** Wait another minute, then hard-refresh your browser with **⌘ + Shift + R**. GitHub Pages and the browser sometimes hold the old version briefly.

- **GitHub Desktop shows `Side Quest V1.rtf` as a change?** Don't commit it — the concept doc is intentionally kept out of the public repo via `.gitignore`. If it reappears, the ignore rule may have been removed; ask Claude to restore it.

## Notes

- The repo is **public**, so anyone with the link can view the site and the code. Keep anything confidential out of `index.html`.
- `Side Quest V1.rtf` (the concept doc) stays on your Mac only and is never pushed.
