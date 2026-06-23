# PBP to Possessions

Static browser app for converting NBA play-by-play spreadsheets into possession-level spreadsheets.

Live site: <https://dustinvali.github.io/pbptoposs/>

## Use

1. Open the live site.
2. Drop in an NBA play-by-play `.xlsx` workbook.
3. Download the generated possession workbook.

The output uses `offense` values of `team_a` and `team_b`. The `Team Map` sheet maps those labels to the actual teams for each source sheet.

Default label rule: `team_a` is the home team and `team_b` is the away team.
