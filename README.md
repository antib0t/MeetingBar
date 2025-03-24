## Features

* Show the next meeting in the system statusbar
  * Show upcoming meetings with name or icon
  * Shorten the meeting title to save space in the statusbar
  * Choose icon to show for the upcoming meeting, e.g. the MeetingBar icon or the meeting app icon
  * Show only meetings within a certain timeframe (e.g. show only meetings in the next 30 minutes)
* Show all upcoming events from today and tomorrow (optional) in the expanded system menubar
  * show or hide all-day events or show only all-day events with a meeting link
  * show or hide events without guests
  * show or hide declined events
  * show or hide meeting app icons
  * show or hide pending events
* Show events from all your macOS calendars incl. notes, location and attendees
* Open the event in macOS calendar or Fantastical 3 (if installed)
* Configure your favorite browser to use for joining meetings and new meetings
* Select for specific services like Zoom or MS Teams to open the meeting in the installed app or in the default web browser
* Attend a meeting with one click
* Join the next online meeting with a keyboard shortcut
* Create a new meeting in your favorite app with a keyboard shortcut
* Get macOS notifications for upcoming events
* Bookmark your favorite meeting, show it in the statusmenu and make it accessible with a shortcut
* Automatically launch the app at login
* Execute custom AppleScript, e.g. to pause music when joining a meeting

## Setup

1. Install either:

* From the [App Store](https://apps.apple.com/us/app/id1532419400)
* Using [Homebrew](https://brew.sh):

  ```bash
  brew install meetingbar
  ```

* Manually download the [latest version](https://github.com/leits/MeetingBar/releases/latest/download/MeetingBar.dmg)

1. Make sure your calendar is synchronized to the macOS Calendar app, or [add a calendar account](https://support.apple.com/guide/calendar/add-or-delete-calendar-accounts-icl4308d6701/mac). You can also use Google as a calendar provider.
2. Open the app and go through the onboarding.
3. Never miss your next meeting again! :tada:

If you experience problems with installation, or have any questions please check the [FAQ](../../wiki/FAQ) or [submit an issue](https://github.com/leits/MeetingBar/issues/new).

## Supported meeting services

MeetingBar supports more than 50 services, including Google Meet, Zoom, Microsoft Teams, GoToMeeting, Skype, WebEx, and Discord. [See the full list](https://github.com/leits/MeetingBar/discussions/108).

## Third-Party Integrations

* [Raycast commands](https://github.com/raycast/script-commands/tree/master/commands#meetingbar)

## Other similar apps

* NextMeeting - free, simpler
* Meeter - commercial solution, provides similar features and more regarding contacts

## Contribute

See [CONTRIBUTING.md](CONTRIBUTING.md) for more on how to contribute to MeetingBar.

## Support the project

❤️ Love this project?

Support it on [Patreon](https://www.patreon.com/meetingbar) or via in-app purchases.

## Credits

MeetingBar is **stable** and in **active development** by [leits](https://github.com/leits). Written in Swift 5.0.

MeetingBar also uses these resources:

* [KeyboardShortcuts](https://github.com/sindresorhus/KeyboardShortcuts) for managing global keyboard shortcuts
* [Defaults](https://github.com/sindresorhus/Defaults) for managing user settings
* [SwiftyStoreKit](https://github.com/bizz84/SwiftyStoreKit) for patronage via in-app purchases
