# Camp Bed Planner

A dashboard to plan the beds of a staff accommodation camp: does it fit, until when, how many beds are short, and what each decision changes.

**Open the tool: https://sulianbh.github.io/camp-beds/**

Nothing to install. The tool works in Edge, Chrome and Safari, on a computer or a phone.

## Getting started

1. **The camp.** Enter the number of beds, those out of service, the possible extra beds, the safety margin and the reserved beds.
2. **The rotations.** Check each rotation: days on site, days off site, arrival dates of the crews.
3. **The staff.** Fill in the list, paste it from Excel, or read it straight from the team’s Excel file (“Paste from Excel”, “Choose an Excel or CSV file”, then “Replace the list”). Columns: Name, Entity, Rotation, Crew, Joins later, Leaves for good (the two dates stay blank for most people: they follow their crew’s rotation).
4. **The overview** updates with every entry; the scenarios put a figure on the effect of each decision.

When it opens, the tool shows an example. To start from scratch: **Help** button, “Start with my data” (while the example is untouched), or **File** menu, “Clear everything and start from scratch”. Click a night on the chart to see the camp that night.

## Keeping and sharing your data

The data you enter is saved automatically in your browser: it is still there when you reopen the page, and nothing is sent anywhere.

- To keep a copy, use it on another computer or pass it on: **File** menu, “Save my data to a file”.
- A colleague opens it with “Open a data file”.
- The day-by-day calendar and the staff list can be exported as CSV, for Excel.

## Offline, or without access to this site

The whole tool fits in a single file. Download `index.html` (the “Download raw file” button on its GitHub page) and open it in a browser: it works offline, exactly the same.

## What the tool counts

Each night, the demand is the sum of the reserved beds and the people on site. A person whose bed is reused while they are away only counts on the nights they are there; a person who keeps their bed counts every night. A bed is never used by two people on the same night. The calculation covers one full cycle of all the rotations and every date entered, up to six years.

The tool is for sizing and organising; it does not hold the room-by-room allocation plan.

Barlow and Barlow Semi Condensed fonts, © The Barlow Project Authors, SIL Open Font License 1.1 (the licence text is included in the page).
