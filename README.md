# Polling-Place-Reporting
This Google Suite project helps a campaign monitor polling places during early and/or election day voting. Consisting of a Google Form, Sheets, and Data Studio, volunteers are able to submit periodic reports for the campaign to review. This helps to maintain adequate supplies, such as literature and water, as well as inform campaign staff where to deploy canvassing resources.

## Usage
Through the [Google Form](https://docs.google.com/forms/d/1uT_UXuUqUya9bviyAccjtRwz6eFIJIDiIHXuXJDtPvM/), volunteers submit periodic reports of the situtation on the ground.

![google_form](https://github.com/drussel4/Polling-Place-Reporting/blob/master/Images/form.png?raw=true)

Properly configured, the [Google Sheet](https://docs.google.com/spreadsheets/d/1iKpDGOVFw_iv-5lgxJN7iARhaLfWYZBS3HsRTJwcW4M/edit#gid=1752547724) automatically retrieves these entries to the "Form Responses 1" sheet. This data is reorganized in the "Transform" sheet and finally structured in the "Studio Read Sheet" for import to the dashboard. The "Abbrev" sheet is for lookups to truncate the polling place names.

![google_sheet](https://github.com/drussel4/Polling-Place-Reporting/blob/master/Images/sheets.png?raw=true)

Finally, the [Google Data Studio](https://datastudio.google.com/s/tAc7ZlyNs6U) dashboard visualizes the on the ground data. It refreshes every 15 minutes by default or by user prompt. The conditional formatting signals when the campaign staff may need to take action, such as when supplies run low at a polling location or when a line gets excessively long.

![google_data_studio](https://github.com/drussel4/Polling-Place-Reporting/blob/master/Images/dashboard.png?raw=true)

## License

MIT © Dave Russell
