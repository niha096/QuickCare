Pill Reminder System
===

The Goal:
---
Pill Reminder is an native android application meant to aid the forgetful and busy with remembering to take their daily medications. It is designed for users who need a little help keeping track of their medication schedule and who are dedicated to keeping the schedule. It is not designed for people who wish to cheat the system or plan to not stay up-to-date with the schedule. The application allows the user to store pill objects and multiple alarms for those pills. Alarms have one time of day and can occur on multiple days of the week. The user is able to view their pills in a today view, a tomorrow view, a weekly view, and an editable view that shows every pill and every alarm.

How to get it working:
---
- Download ZIP from GitHub
- Download Android Studio and SDK Android 5.0.1 API 21 (the minimum API Level required for the application to run is API 16)
- SDK Build Tools 21.1.2
- It is not recommended for phones with resolution smaller than 480x800
- Please use at your own risk for APIs newer than API 21 and older than API 16

Use Cases and What Each Button Does:
---
In the Home page, you will see 3 buttons in the top right of the application.
######Plus sign: 
This will take you to the Add Activity where you will be able to create an alarm. The application will automatically link up all the alarms to a specific pill with the same Pill Name. If you attempt to create an alarm to a pill that does not exist, it will automatically create a pill object for you.
######Suitcase sign: 
This will take you to the Pill Box Activity where you will be able to see all the pills and alarms created. This will also be the place where you can edit and delete any pill and alarm you desire.
######Calendar sign: 
This will take you to the Schedule Activity where you can see all the pills and alarms organized by the day of week.

######List of use cases:
- Add an alarm: Press the plus sign button and go to the Add Activity. Enter information and press "Set Alarm".
- Edit an alarm: Press the suitcase sign and go to the Pill Box Activity. Select a pill and then an alarm of the pill. Enter information and press "Set Alarm".
- Delete an alarm: Press the suitcase sign button and go to the Pill Box Activity. Select a pill and then an alarm of the pill. Press the trash can icon at the top right corner.
- React to an alarm: When the dialog box pops up, press one of the three buttons to indicate "I took it", "Snooze", or "I won't take it".
- View the schedule for today and tomorrow: Swipe to the today or tomorrow tab on the home screen.
- View the schedule for the whole week: Press the calendar sign button and go to the Schedule Activity.
- View the alarms by pill: Press the suitcase sign button and go to the Pill Box Activity.
