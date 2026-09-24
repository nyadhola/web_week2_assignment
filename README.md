# Week 2 Budget Tracker Upgrade

This project builds on top of the Week 1 static HTML/CSS skeleton for the **Budget Tracker** web application.

## Features Added

1. **Expense Table:** Replaced the placeholder text with a structured `<table>` featuring `<thead>`, `<tbody>`, `<th>`, and 5 rows of hardcoded expense sample data.
2. **Upgraded Form:** Wrapped form inputs inside a `<form>` element, added a `<select>` dropdown with 5 category options (*Food, Transport, Rent, Entertainment, Other*), and added a `<button type="button">` with custom `id` attributes.
3. **Multimedia Elements:** Added a logo image (`<img>`) next to the main title and embedded an informational YouTube video (`<iframe>`) on budgeting tips.
4. **Interactive UI Elements:** Added a collapsible `<details>` / `<summary>` user guide section and added `:hover` effects to table rows and `cursor: pointer` to the button.
5. **Advanced CSS Selectors Used:**
   - **Descendant Selector:** `.expense-table th`
   - **Direct Child Selector:** `.form-group > label`
   - **Position Pseudo-class:** `tr:nth-child(even)`
   - **Negation Pseudo-class:** `input:not([type="button"])`
   - **Focus Pseudo-class:** `input:focus`
