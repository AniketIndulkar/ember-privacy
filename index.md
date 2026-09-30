---
layout: default
---

# Privacy Policy for Ember

**Last updated: 30 September 2026**

Ember (`dev.novanest.ember`) is developed and maintained by Aniket Indulkar. Ember is an offline
Pomodoro focus timer. It does not collect, sell or share personal data.

The app has no `INTERNET` permission. Android therefore prevents Ember from opening network
connections. Ember has no account or sign-in, and contains no advertising, analytics,
crash-reporting or tracking SDKs.

## Information stored on your device

Ember stores the following information in its private app storage:

- **Settings:** timer durations, cycle length, saved presets, theme, daily and weekly goals, daily
  reminder time, alert preferences and other choices you make in the app.
- **Session history:** the start time, completion time and duration of each focus session you
  complete, finish early or add by hand, plus any description, tag, focus rating and interruption
  count you enter or log for it.
- **Tags:** the names, colours, order and weekly goals of the tags you make.
- **Current timer state:** the current focus or break phase and the information needed to restore
  its countdown.

This information is used only to provide the timer, history, statistics, streaks, widgets,
notifications and settings shown in Ember. It is protected by Android's application sandbox and
is not made available to other apps by Ember.

## Device information accessed but not retained

- **Wireless charging state:** when Android starts Ember's optional charging screen saver, Ember
  checks whether the device is wirelessly charging or docked. This value is used only to decide
  whether to show the landscape timer. It is not stored.
- **Do Not Disturb state:** if you enable Silence while focusing and grant Android's notification
  policy access, Ember reads the current interruption setting so it can avoid overriding a mode
  you selected yourself and can restore the previous setting after the focus session. The value
  is held only in memory and is not included in session history.

Ember does not access contacts, precise or approximate location, photos, videos, camera,
microphone, health information, advertising identifiers or accounts. It does not access other
files, except a file you choose yourself through Android's document picker: a CSV under
**Settings → Bring sessions in → Import CSV**, or a backup under
**Settings → Backup → Restore from backup**. Ember reads that one file, to add its sessions to
your history or to replace what is on the device, and keeps no reference to it.

## Information leaving your device

Ember does not transmit information to the developer or to third parties. Information leaves the
app only through an action controlled by you or Android:

- **Android backup and device transfer:** if backup or device transfer is enabled in Android,
  Android may copy Ember's settings and session history to your Google account or another device
  under Google's terms. The running timer is excluded. Ember cannot access the backup after
  Android creates it. You can control backup from your device or Google account settings.
- **CSV export:** when you choose Settings → Your sessions → Export CSV, Android's system document
  picker lets you choose where to save a copy of your history. Once exported, that file is outside
  Ember's private storage and is controlled by you and the destination you selected.
- **Backup file:** when you choose Settings → Backup → Save backup, Android's system document
  picker lets you choose where to save one JSON file holding your sessions, tags, presets, goals
  and settings. Ember does not back up automatically and saves nowhere you did not choose. Once
  saved, that file is outside Ember's private storage and is controlled by you and the destination
  you selected.
- **Focus Year image:** when you choose Stats → Focus Year → Export image, Ember draws a picture of
  that year on the device and opens Android's share sheet so you can choose where it goes. The
  picture holds your hours, days and top tags, with tag names and a name of your own only if you
  leave those switches on. It carries no device, account, location or other identifying information,
  and Ember sends it nowhere itself. Ember keeps the last picture in its private cache so the app
  you share to can read it, and replaces it the next time; clearing Ember's cache or data removes it.
  Once you share it, it is controlled by you and the app you chose.
- **Feedback email:** when you choose Settings → About → Feedback and bugs, Ember opens your email
  app with a draft addressed to the developer. The draft includes Ember's version, your Android
  version and your device model so a report can be investigated. Nothing is sent unless you send
  the email yourself, and you can edit or remove any of it first.
- **Privacy policy:** Settings → About → Privacy → Full privacy policy shows this text inside
  Ember, with no network request. This page is the same text, for the store listing.

## Permissions

| Permission or access | Purpose |
|---|---|
| Notifications | Shows the ongoing timer and tells you when a focus or break phase ends. Requested when you first start a timer. |
| Foreground service | Keeps the ongoing timer notification available while a phase is running. |
| Alarms and reminders | Lets the end-of-phase alert arrive on time. Optional; the timer still works without it, but the alert may arrive late. |
| Do Not Disturb access | Silences allowed interruptions during a focus phase. Optional and disabled by default. |
| Vibration | Provides optional control feedback and an end-of-phase vibration. |
| Run at startup | Sets the optional daily reminder again after the device restarts, because a restart clears it. Does nothing if the reminder is off. |

## Retention and deletion

Settings, timer state and session history remain on the device until you delete them or uninstall
Ember.

- Delete session history in **Settings → Session history → Delete**. This is immediate and
  permanent within the app.
- Clear all local Ember data from Android's app settings, or uninstall Ember.
- Delete an exported CSV or a backup file from the location where you saved it.
- Android backup copies are controlled by Android and Google. Manage or delete them through your
  device or Google account settings.

Because Ember has no account or server, the developer holds no server-side copy that can be
retrieved or deleted.

## Children

Ember is a general productivity tool and is not directed specifically to children. It contains no
social features, advertising or data collection, and it handles information in the same way for
every user.

## Changes to this policy

If Ember's data practices change, this policy will be updated before a version with those changes
is released. The date at the top identifies the latest revision.

## Contact

For privacy questions, open an enquiry at
[github.com/AniketIndulkar/ember-privacy/issues/new](https://github.com/AniketIndulkar/ember-privacy/issues/new).
GitHub issues are public, so do not include personal or sensitive information.
