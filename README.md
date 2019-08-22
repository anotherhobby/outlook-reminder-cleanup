# outlook-reminder-cleanup

## Premise

People frequenly send out of office or WFH calendar events, but forget to remove reminders. At 11:45pm your alert goes off letting you know your absent minded event scheduling coworker is off the next day.

These events are relatively easy to find, in that they are usually all-day events or are events that don't block your calendar. These type of events typically should not have reminders anyway. This AppleScript runs in the background every 5 minutes, finds any of these events in your calendar, and removes the reminders.

## Setup:

1. Put the "ResetOutlookReminders.scpt" file whereve you like.
2. Update the path to the script in step 1 in line 12 of "com.anotherhobby.reset-outlook.plist"
3. Update the frequency in seconds on line 15 if you'd like it to run other than every 5 minutes


