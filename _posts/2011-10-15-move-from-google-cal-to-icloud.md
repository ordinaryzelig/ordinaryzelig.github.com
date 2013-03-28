---
layout: post
title: Move from Google Cal to iCloud
categories: dev_blog
format: markdown
---

Before iCloud, the only syncing solution I had was to use Google Calendar.
It worked, but it felt a bit hackish.
Now that iCloud is out, there's a pure Apple solution that is integrated into all my Apple devices.
It's not perfect, but I definitely like it better than what I had before.

<img src="/images/google_calendar_to_calendar_app.png" />

One complaint I had with using Google in iCal was that it looked uuuuugly.
Each calendar had its own folder with 1 calendar in it.
No more.
Here's how you get MOST of your calendars off of Google and into iCloud.
(I say "MOST" because I haven't figured out a smart bomb solution for subscribed Google calendars.
But we'll get to that.)

This process will not affect your google calendars.
They'll still be there at google when we're all done What you'll actually be doing is copying it to iCloud.
Either way, be sure and have backup solutions for all data mentioned here.

## 'Normal' calendars

This section refers to 'normal' calendars that were created in Google in YOUR account, not subscriptions of any kind.
If you open up google calendar in your browser, 'normal' calendars are the ones listed under `My calendars`.

1. Open up iCal (this process requires OSX Lion). You'll see the ugly `DELEGATES` section.
1. Right click one of the calendars (for starters, pick one that is not very busy).
1. Click `Export...` and choose a place for the export to go where it's easy to find (we'll be using it in just a second).
1. In the menu, click `File`, `New Calendar`, `iCloud`.
1. Give it a name (doesn't have to be the same as the calendar you're about to import).
1. In the menu, click `File`, `Import`, `Import....`
1. Find the calendar you just exported. Click `Import`.
1. In the pop-up, select the new iCloud calendar you just created. Click `OK`.
1. Go to iCloud.com to check that the import worked.
1. Repeat for the rest of your 'normal' DELEGATE calendars.

## Subscription calendars (not from Google)

This is where it gets just a tad tricky. These steps only apply to calendars subscribed from websites, NOT from google.

1. In the left column, under the `Other calendars` list, click on the little arrow to the right of one of the calendar's name.
1. Click `Calendar settings`.
1. Look for `URL:` and you'll see a link to the right (e.g. `webcal://something.com/cal.ics`). Copy it. (If you don't see `URL`, you'll probably see `Calendar Address:` further down the page. If there is a green ical link, right click and copy the URL. When available, you should always use the webcal/.ics URL rather than the green iCal link. The blue `HTML` and orange `XML` links will not work.)
1. In the iCal menu, click `Calendar`, `Subscribe...`.
1. Paste the URL, click `Subscribe`.
1. Fill in the information: name, color, options, etc.
1. Click `OK`.
1. The calendar will appear in the `Subscriptions` section at the bottom of you calendar list. Give it a few seconds for it to fetch the events.
1. Repeat for the rest of your non-google subscriptions.

Right now, iCloud.com doesn't support subscription calendars.
The good news is that your iPhone and iPad WILL show subscriptions.

## Shared subscription calendars

If it's your friend's google calendar, you'll need to ask them to give you the ical URL.
This can be found in that calendar's settings to the right of `Calendar Address:`.
Again, you're looking for the green ical link to copy.
Your friend will need to make the calendar public.
If they're not OK with that, then this won't work.

## Other calendars

For any other calendar types that don't have the URL or green ical calendar address link, if it's a popular calendar like a sports team, you'll probably find a similar calendar somewhere other than Google calendar.
It's just a matter of finding it.
For example, I found my Oklahoma Sooners' sports calendars hidden on their website.
I went to the [football schedule website](http://www.soonersports.com/sports/m-footbl/sched/okla-m-footbl-sched.html), clicked on [Printable Schedules](http://www.soonersports.com/ot/printable_schedules.html), et voilà: a list of calendar subscription URLs!

After you've successfully gotten all your google calendars into iCloud, you can remove your google account from iCal (and the calendar part of your google accounts on your devices).
In iCal, go to iCal menu, Preferences, Accounts tab. Remove Google.
Alternatively, you can do this in System Preferences, 'Internet & Wireless', 'Mail, Contacts, & Calendars'.
Click on Google, uncheck Calendars.

Now sit back and admire how much cleaner your calendar list looks.

## Bonus

From iCal, you can change the colors of your calendars.
You can also reorder the normal, non-subscription calendars.
These changes are even synced to iCloud!
