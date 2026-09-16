# hti-m365-csv-conversion

Convert Microsoft 365 User List to Clean NCE Report Output

## Live Tool

**[Open the NCE Report Builder](https://ngibb-work.github.io/hti-m365-csv-conversion/nce-365-report-builder.html)**

## How to Use

1. Export users from **M365 Admin Center → Users → Active Users → Export**
2. Open the tool at the link above
3. Drop the exported CSV file into the upload area (or click Browse for file)
4. Review the preview — licensed users will appear with their cleaned license info
5. Click **Download Excel** to save the formatted output

## What the Tool Does

- Filters out external (`#EXT#`) accounts
- Removes unlicensed users
- Strips trial, free, and add-on-only licenses (e.g. Power Automate Free, Exploratory)
- Auto-fits column widths and adds header filters to the Excel output
- Names the output file after the uploaded CSV (e.g. `ClientName_365_User_List_YYYYMMDD.xlsx`)

## Updating the Tool

When a new version of the HTML file is uploaded to this repo, GitHub Pages may take 1–2 minutes to reflect the change.

**If the tool behaves unexpectedly after an update, do a hard refresh:**
- Windows: `Ctrl + Shift + R`
- Mac: `Cmd + Shift + R`

## Adding to the Strip List

If a license type appears in the output that should be excluded (e.g. a new free or trial product), contact Nichole to have it added to the filter list.
