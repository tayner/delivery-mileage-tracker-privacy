# Privacy Policy: Delivery Mileage Tracker

Effective date: 2026-11-13

Delivery Mileage Tracker ("the app") helps delivery drivers log shifts, miles and expenses and estimate a mileage
deduction. This policy explains what the app does with your information. The short version: your records stay on
your phone, and we do not run any server that receives them.

## Who we are and how to reach us
Questions about this policy: taynerjhony46@gmail.com

## What the app stores, and where
Your shifts, miles, tips and pay, expenses, driver name, vehicle description and settings are stored only on your
device, in the app's own local database. The app has no accounts, no sign-in and no cloud sync. We do not collect
your name, email address, phone number or any other identifier, and the app contains no advertising, no analytics
and no crash-reporting tools.

## Location (Auto shifts only)
- **When it is used.** Precise location (GPS) is used only while an Auto shift is active, from the moment you tap
  "Start Auto Shift (GPS)" until you end the shift. It is not used when no shift is active, and Manual shifts never
  use location. Manual entry needs no location permission.
- **What is recorded.** GPS fixes (latitude, longitude, accuracy and time) are used to add up the miles driven.
  Fixes that are too inaccurate, tiny movements and impossible jumps are discarded. Only the total miles for the
  shift are used afterwards, in your totals, your estimated deduction and your exports.
- **Where it goes.** Location data stays on your device. The app does not send it to us or to any third party, does
  not use it for advertising and does not sell it. The app has no map and no map SDK, so your routes are never shown
  on a map or shared with a map provider.
- **Background use.** During an active Auto shift the app can keep counting miles while you use another app, such as
  navigation. On Android this runs as a foreground service with a visible notification, and you may be asked to allow
  location "all the time". On iOS the app keeps using location in the background while the shift is active, and the
  system shows its location indicator. If you decline, Auto tracking works only while the app is open.
- **Platform location services.** On Android, location comes from Google Play services (Fused Location Provider).
  On iOS it comes from Apple's Core Location. These system services are provided and governed by Google and Apple;
  the app itself does not send your location to anyone.
- **Your control.** You can turn location permission off at any time in your device settings. Auto tracking then
  stops, and the miles already recorded stay saved. Deleting an Auto shift in History deletes its recorded GPS points
  too.

## Drive detection (optional, off by default)
- **What it does.** Drive detection is part of the optional Pro subscription. If you have Pro and turn on "Suggest starting a shift when I drive" in Settings, your phone's motion detection
  (Google's Activity Recognition on Android, Apple's Core Motion on iOS) tells the app when it thinks you are driving.
  The app then shows a "Start a shift?" notification, at most once per drive and not again for a couple of hours
  after you ignore or dismiss it. It never shows it while a shift is active.
- **What is recorded.** Nothing. The app does not save your motion or activity data, and it does not record any
  location because of this feature. It only remembers when it last showed the notification, to limit how often it
  asks. Only if you tap the notification does an Auto shift start, and then the Location section above applies.
- **Where it goes.** Detection runs on your device through the system service. The app does not send it to us or to
  anyone else.
- **Your control.** The switch is off until you turn it on. You can turn it off at any time in Settings, or revoke
  the motion/activity permission in your device settings.
- **Permissions.** Android: "Physical activity" (and notifications on Android 13+). iOS: "Motion & Fitness" (and
  notifications). On iOS, detection works while the app is running; it may not notice a drive that starts while the
  app is fully closed.

## Notifications
The app can send local notifications: a reminder about a shift you may have forgotten to end, and, if you turned it
on, the "Start a shift?" suggestion. They are created on your device and no server is involved. You can switch
notifications off in your device settings.

## Backups and moving to a new phone
- The app does not back up your records to the cloud. On Android, Google cloud backup is turned off for the app. On
  iOS, the app's database is excluded from iCloud and device backups.
- Android's direct phone-to-phone transfer (by cable or local connection) can carry the data to a new phone.
- Settings has "Back up data" and "Restore data". They write and read one file that you choose a location for, on
  your device or in a storage service you pick. The file is created by you, and the app does not upload it anywhere.
  If you store it in a cloud service yourself, that service's own policy applies to the file.

## Purchases
Pro subscriptions are sold and billed by Google Play (Android) or the Apple App Store (iOS). The store processes
your payment under its own privacy policy. The app never sees your card or payment details, and only receives
whether you have an active subscription.

## Exports and sharing
PDF and CSV reports are created on your device and shared only when you use the system share sheet. Where they go
then is up to you and the app you choose.

## Estimated deduction is not tax advice
Where the app shows an estimated deduction, it is calculated from the IRS standard mileage rate and your recorded
miles. It is an estimate only and is not tax advice. Talk to a qualified tax professional about your own situation.

## Children
The app is not directed to children under 13, and we do not knowingly collect any information from anyone,
including children.

## Deleting your data
Delete single shifts and expenses in History. To delete everything, uninstall the app or clear its storage
(Android: Settings > Apps > Delivery Mileage Tracker > Storage > Clear data). Because nothing is stored on a server,
there is no account to close and nothing else for us to delete. Backup files you created yourself are yours to delete.

## Changes to this policy
If the app's data practices change, for example if a crash-reporting tool or a server feature is ever added, this
policy will be updated before that version is released, and the effective date above will change.
