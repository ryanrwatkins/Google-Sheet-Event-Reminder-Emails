# Google-Sheet-Event-Reminder-Emails
Use Google Sheet to manage your Calendar events and sent email reminders

This Google Script will send emails (e.g., reminder messages) based on dates in a Google Sheet. 
The information in the Google Sheet can also set up Google Calendar events on specific dates, as shown in this script: https://github.com/ryanrwatkins/Google-Sheet-to-Calendar.  This also imports a list of email recipients from another tab in the Sheet using this Google Sheet notation: =textjoin(", ", 1, members!B2:B) 
to put them into a comma separated format.
