# EMA-Reminder

I am giving students reminders of the events they need to attend at the university each day, such as lectures and lab classes. I also provide weekly overviews of how well they have done at attending different sorts of events over the last week. The aim is to support students with ADHD and overseas students who often find it challenging to manage their time when they first attend university.

The core of this application is the integration between Power Automation and Twilio. Their powerful features bring strong feasibility and scalability to our products. Power Automation connects directly to users' Outlook calendars, fetching details of upcoming events to trigger timely reminders. These reminders, sent as text messages through Twilio, ensure users are well-prepared and can plan their activities effectively. Moreover, the system extends its functionality by soliciting user feedback post event, which Twilio channels back to Power Automation. This feedback is meticulously recorded in an Excel spreadsheet, laying the foundation for a comprehensive analysis of the user's attendance and time management patterns. 

## Prototype: SMS reminder

Here is the reminder for all of the next day events:

<img src="https://github.com/kk19041/EMA-Reminder/blob/main/sms_tomorrow.jpg" alt="sms_tomorrow" style="zoom:25%;" />

The reminder for upcoming event in user's calendar, also asked the attendance after the event finish:

<img src="https://github.com/kk19041/EMA-Reminder/blob/main/sms_reminder.jpg" alt="sms_reminder" style="zoom: 25%;" />

Here is the weekly summary of the user's attendance：

<img src="https://github.com/kk19041/EMA-Reminder/blob/main/sms_weekly.jpg" alt="sms_weekly" style="zoom:25%;" />





