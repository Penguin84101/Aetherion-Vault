# 🧭 Welcome to Aetherion Vault

This is the interactive archive of logs, characters, AI routines, crew testimony, and nonlinear lore of the IX-3 Outpost. This vault is built to help you develop, organize, and polish the narrative for eventual upload (e.g. to AO3 or as a hypertext).

> ✨ “Because gods may be rising… but we still have to keep them alive.” — Cela Tyven

---

## 🗂️ Main Sections

- 📁 [[Character_Index|Character Index]]
- 📁 [[02_Logs/Log_Index|Logs (All)]]
- 📁 [[Timeline Overview]]
- 📁 [[Glossary & Tech]]
- 📁 [[Plot Hooks + Holes]]
- 📁 [[Old Notes]]

---

## ✍️ Writing & Edit Tracker

| Date       | Work Done                                                  |
| ---------- | ---------------------------------------------------------- |
| 2025-06-26 | Installed plugins, began metadata pass, reviewed Faye/Juno |
| 2025-06-25 | Rebuilt logs structure, split AI personalities             |

> 🧠 Use the `[[Daily/DATE]]` folder if you'd like to track notes per day.

---

## 🧠 Current Focus

- ☐ Continue metadata tagging for logs
- ☑ Confirm Kaelen, Strand, and Faye timeline sequence
- ☐ Draft scene: Crew's reaction to "too-normal" quiet
- ☐ Sort out Candy’s gossip log order
- 💡 Strand’s child = “the moon” motif (protective trigger?)

---

## 📚 Reading Queue

These need attention for review or patching:

- 🔄 [[Kaelen_Internal_05|Kaelen Internal 05]] — check timeline
- ❓ [[Gossip_StormIncident|Gossip: Storm Impact]] — restructure flow
- ⏳ [[Faye_Juno_Consolidation]] — still under revision

---

## 📊 Dataview Queries (optional)

### Latest Modified Logs

```dataview
table file.name as "Log", file.mtime as "Last Modified"
from "02_Logs"
sort file.mtime desc
limit 5
