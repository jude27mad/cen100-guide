# CEN100 Guide: Don't Lose Marks

A course companion for **CEN100: Introduction to Engineering**, Fall 2026, at Toronto Metropolitan University. The guide brings deadlines, assignment requirements, checklists, course clarifications, and section/group contacts into one responsive page.

**[Open the guide](https://jude27mad.github.io/cen100-guide/)**

## What's included

- **Team, Individual, and Rules tabs** with expandable assignment cards.
- **Deadline tracking** shared by the upcoming-deadline banner, assignment date displays, work planner, and calendar exports. Repeated assignments retain their later deadlines after the first date passes.
- **Section and group selection** at the top of the page, covering all 39 sections and 52 Innovation Challenge groups in the staffing sheet.
- **Who to ask** results showing the assigned GA, lab/location, and Project Manager.
- **Checklists and separate completion records** for tracking preparation and recording submitted or completed work.
- **What should I work on?** with Next 7 days and All unfinished views.
- **Private notes and personal target dates** inside each assignment card.
- **Direct assignment links** that open the appropriate tab and expanded card.
- **Search, checklist filtering, source notes, and update history**, including a New updates indicator for unread releases.
- **Calendar exports and progress backups** for use outside the current browser.
- **Automatic light/dark appearance** based on the device setting.

## Getting started

1. Optionally choose a section and Innovation Challenge group below the main heading. Group choices are filtered by section, and selections save immediately. Use **Done** to collapse the picker or **View contacts** to open Who to ask.
2. Select **Team**, **Individual**, or **Rules**. Open an assignment card to review its requirements, checklist, source notes, and tools.
3. Open **Guide tools** for search, Hide fully checked items, the work planner, calendar exports, backups, and What's changed.
4. Returning visits restore the saved section/group selection. Use **Change** at the top or **Change section/group** in Who to ask to edit it.

## Progress and personal planning

Checklist ticks track preparation. A **Date passed** badge describes the calendar date; it does not indicate completion or a grade.

Each card's **My plan & completion** section contains separate submission/completion records, a notes field, and an optional personal target date. Assignments with multiple deadlines have separate records for each occurrence. These records are entered manually; the guide does not submit assignments or verify submission on D2L.

**What should I work on?** uses those completion records. Next 7 days includes upcoming unrecorded deadlines and personal targets from today through the following six days. All unfinished also includes past dates with no completion recorded and work with an unconfirmed date. Each result shows remaining checklist items and opens its assignment card.

Personal target dates do not change official deadlines. Notes are saved on the current device and are not shared with a team. **Clear my ticks** clears checklist ticks only; completion records, notes, and target dates remain saved.

## Sharing an assignment

Choose **Copy assignment link** inside a card. The link opens that assignment's tab and expands its card. Links do not contain saved section/group choices, checklist progress, completion records, notes, or personal target dates. If clipboard access is unavailable, the guide displays a link to copy manually.

## Calendar exports

Use **Add to calendar** inside a card or **Guide tools → Add deadlines to my calendar**. Select one assignment or all confirmed deadlines, choose whether to include only upcoming dates, and select a reminder of one day, two days, or none.

Download the `.ics` file and open it in Apple Calendar or import it into Google Calendar. Confirmed times use **America/Toronto**, including daylight-saving changes. Dates without a confirmed time are all-day entries, with reminders at 9 AM on the selected prior day.

Calendar exports exclude approximate dates, section-specific lab activity reminders, and the unscheduled final exam. Imported calendars do not update automatically. Check D2L for changes and review the calendar application's alert settings.

## Backups and local storage

Use **Guide tools → Move or back up my progress → Export my progress** to download a `.json` backup. Import it through the same panel on another device.

- Current backups include checklist ticks, completion records, private notes, and personal target dates.
- Older checklist-only backups still import.
- Importing adds checked items and completion records, and fills empty notes or target dates. Existing conflicting notes or target dates are retained and reported.
- Section/group choices and interface preferences are not included in backups.

Progress, selections, notes, targets, and preferences are stored in browser local storage. There are no accounts or automatic synchronization between browsers or devices. Clearing browser data may remove locally saved information.

## Sources and contact privacy

The guide uses Fall 2026 CEN100 documents on D2L and confirmed course-team clarifications. Source notes distinguish course-outline information, assignment summaries, and confirmed clarifications. Resolved guidance appears under **Confirmed**; unanswered questions remain under **Still open**.

Tutorial timing is identified by section where confirmed. Other sections are directed to D2L rather than assigned an assumed schedule. Reflection instructions show the selected group's Project Manager when available.

The staffing document supplies section/group mappings, names, and lab locations only. **GA and Project Manager email addresses are not published or stored in the page's source code.** For contact details, check D2L or the official Section GAs and PMs document.

This guide is an unofficial planning aid. Current official assignment instructions and course-team announcements remain the authority for requirements, submission methods, and deadlines.

## Files and hosting

| File | Purpose |
| --- | --- |
| `index.html` | Complete page, including styles, JavaScript, course data, and contact mappings. |
| `README.md` | Features, usage, data handling, and hosting documentation. |

The site uses plain HTML, CSS, and JavaScript. No installation, package manager, build step, or backend is required. Archivo is loaded through Google Fonts, with system-font fallbacks.

GitHub Pages serves the **main** branch from **/(root)** using **Deploy from a branch**. To preview locally, download `index.html` and open it in a browser.
