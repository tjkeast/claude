# CLAUDE.md

## Standing task: Daily healthcare-payments (Australia) research

A daily research series on how healthcare is funded, priced, and paid for in
Australia. Each day a new numbered report is added under
[`research/healthcare-payments-au/`](research/healthcare-payments-au/) and indexed
in [`research/healthcare-payments-au/INDEX.md`](research/healthcare-payments-au/INDEX.md).

Each run: read `INDEX.md` and recent reports for continuity, pick the next thread
(don't repeat prior coverage), research from primary sources, write the next
numbered report, update `INDEX.md`, then commit and post the daily Slack summary.

## Daily Slack report — output conventions

When posting the daily summary to Slack, format it using these rules. (These
govern the **printed** message; report **filenames** are unchanged and keep their
zero-padded prefix, e.g. `011-2026-06-16-...md`, so they sort correctly.)

1. **Dates — human-friendly.** Write dates as `Ddd Dthe Month YYYY`, i.e. weekday
   abbreviation + ordinal day + full month + year.
   - ✅ `Tue 16th June 2026`
   - ❌ `2026-06-16`

2. **Report number — no zero-padding when printed.** Print the number without
   leading zeros.
   - ✅ `Report 11`
   - ❌ `Report 011`

3. **Cited report — a clickable Slack link, not a raw path.** Replace the old
   `Full cited report committed to the repo at: research/healthcare-payments-au/<file>.md`
   line with a Slack-formatted hyperlink whose link text is `View full report`:

   ```
   <https://github.com/tjkeast/claude/blob/main/research/healthcare-payments-au/<file>.md|View full report>
   ```

   Slack link syntax is `<URL|text>`. Example for report 11:

   ```
   <https://github.com/tjkeast/claude/blob/main/research/healthcare-payments-au/011-2026-06-16-better-access-mental-health-session-cap.md|View full report>
   ```

### Example Slack message (report 11)

> *Healthcare Payments AU — Report 11 · Tue 16th June 2026*
> Better Access and the Mental Health Rebate: …summary…
> <https://github.com/tjkeast/claude/blob/main/research/healthcare-payments-au/011-2026-06-16-better-access-mental-health-session-cap.md|View full report>

This repo is the project's memory — each run is a fresh container, so nothing
persists unless committed.
