# CEN100 Guide: Don't Lose Marks

A student-created course companion for **CEN100: Introduction to Engineering**, Fall 2026, at Toronto Metropolitan University. Prepared for **Section 29, Group 9**, the guide brings project milestones, individual tasks, and submission checklists into one mobile-friendly page. Its contact lookup covers all **39 sections and 52 Innovation Challenge groups** in the official staffing sheet.

**[Open the guide](https://jude27mad.github.io/cen100-guide/)**

## Features

- Upcoming deadlines with countdowns.
- Separate **Team**, **Individual**, and **Rules** tabs.
- Expandable milestone checklists with requirements and common mark-loss pitfalls.
- Checklist progress saved locally, with an option to hide fully checked items.
- Search across assignments, checklists, rules, clarifications, and contact names.
- Calendar exports for one assignment or all confirmed deadlines, with optional reminders.
- Checklist backup export and import for moving progress between browsers or devices.
- A section/group contact lookup that remembers your selections on the current browser.
- Source notes inside milestone cards, plus a last-updated date and **What's changed?** history.
- Automatic light and dark appearance based on the device setting.
- Separate **Confirmed** and **Still open** sections for course clarifications.

## Using the guide

1. Open the guide and select **Team**, **Individual**, or **Rules**.
2. Tap a milestone to review its requirements and tick completed items. Expand its source note to see where the information comes from.
3. Open **Guide tools** for search, the completed-item filter, calendar exports, backups, and update history.
4. Under **Rules → Who to ask**, choose your CEN100 section, then one of its applicable Innovation Challenge groups. The lookup shows your GA, lab/location, and Project Manager.
5. Use **Clear my ticks** to reset checklist progress in the current browser.

### Saved choices and privacy

Checklist ticks, section/group selections, and the completed-item filter are stored in browser local storage. They stay on that browser and do not automatically sync between devices or team members. No account is required. Clearing browser data may remove these settings.

This is a public site. The staffing PDF is used only for section/group mappings, names, and lab locations. **Do not publish GA or Project Manager email addresses anywhere in the repository**, including HTML, JavaScript, comments, metadata, or hidden data. There are no email links in the lookup. For contact details, check D2L or the official **Section GAs and PMs** document.

### Calendar exports

Open **Guide tools → Add deadlines to my calendar**, or use **Add to calendar** inside an assignment card. Choose the deadlines, whether to include only upcoming dates, and a reminder of one day, two days, or none. Download the `.ics` file and open it in Apple Calendar or import it into Google Calendar.

Confirmed times use **America/Toronto**, including daylight-saving changes. Dates without a confirmed time are all-day entries, with reminders at 9 AM on the selected prior day. Approximate dates and the unscheduled final exam are excluded. Calendar copies do not update automatically; check D2L for changes, review your calendar's alert settings, and avoid importing the same deadlines repeatedly.

### Checklist backups

Open **Guide tools → Move or back up my checklist ticks** and choose **Export my ticks**. On another device, open the guide and import the downloaded `.json` file.

Importing adds checked items and preserves existing ticks. Backups contain checklist progress only; section/group choices and filter settings are not included.

## Course information

This is an unofficial planning aid based on Fall 2026 CEN100 documents on D2L and confirmed course-team clarifications. Check D2L and current instructor, GA, or Project Manager instructions for authoritative requirements and deadlines. Follow the submission method listed for each assignment. The guide identifies unresolved items in **Still open**.

Source notes distinguish course-outline information, confirmed clarifications, and assignment summaries. Contact mappings come from **Section GAs and PMs - Fall2026.pdf**. Some tutorial-specific information remains tailored to Section 29, Group 9.

## Files and hosting

| File | Purpose |
| --- | --- |
| `index.html` | Complete guide, including its styles, JavaScript, and contact mappings. |
| `README.md` | Project overview, usage notes, and privacy requirements. |

The page runs directly in a browser with no installation, package manager, or build step. It uses the Archivo font from Google Fonts, with system-font fallbacks.

GitHub Pages serves the site from the **`main` branch**, **`/(root)` folder**, using **Deploy from a branch**. To preview locally, download `index.html` and open it in a browser.

## Maintaining the guide

- Preserve the existing layout, styling, and interactions when adding features.
- Verify course changes against official documents or confirmed course-team clarifications. Remove contradictory wording and keep unresolved questions in **Still open**.
- Keep assignment dates and calendar entries consistent, and update the last-updated date, change history, and source notes when relevant.
- Keep existing checklist keys stable so saved progress and backups continue to work.
- Check new content for staff email addresses before publishing.
