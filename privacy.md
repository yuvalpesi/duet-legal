---
title: Azygote Privacy Policy
permalink: /privacy/
---

# Azygote Privacy Policy

Last updated: 29 October 2026

Azygote is a pregnancy organization and family-planning app. The app's technical
project and service identifiers use the name `PregnancyTogether`. Azygote is not a
medical service and does not provide diagnosis, treatment, or emergency care.

## Information handled by the app

The app may handle names, pregnancy dates and context, appointments, checkups,
preparation tasks, notes, uploaded documents, birth-planning information,
postpartum entries, journal notes and photos, baby-name shortlists and votes,
practical support requests, and optional health measurements. Users choose what to
enter or import.

If the pregnant user explicitly connects Apple Health, the app can read the
latest available weight, blood-pressure, blood-glucose, heart-rate,
resting-heart-rate, oxygen-saturation, body-temperature, and respiratory-rate
samples that the user permits. The app does not write information to Apple
Health.

## Where information is stored

- Medical and pregnancy records stay in protected storage on the current
  iPhone: Apple Health imports, Health Tracking entries, pregnancy dates and
  context, appointments, checkups, medical documents, journal notes/photos,
  birth plans, postpartum records, check-ins and support requests. These are
  excluded from CloudKit synchronization and automatic device backups.
- Optional partner collaboration is limited to a name shortlist, votes/actions,
  participant identifiers and display names. Name notes remain local. Only this
  limited planning projection is stored in the user’s private/shared CloudKit
  workspace; the app does not send medical records or document assets there.
- Older iCloud records are first copied, including available file/photo assets,
  to protected recovery storage on the iPhone. Normal supported records are
  also recovered into local app stores before remote cleanup. Recovery export
  is available under Privacy and information management. Cleanup waits for
  successful local persistence and can remain pending while offline or if a
  participant lacks permission. Older installed app versions can create old
  records again; update both partners’ devices before relying on the new scope.
- The app no longer automatically connects or copies documents to cloud
  folders. Previously exported files remain controlled by their provider.
- Calendar integration can write medical appointments only to an on-device
  calendar, not iCloud, Exchange or other cloud calendars. Copies created by
  older versions are not automatically moved or deleted.
- Widgets use protected local snapshots excluded from automatic backups. An
  installed paired Apple Watch can receive a summary directly through Apple’s
  device connectivity service; its app snapshot is stored in a protected file
  excluded from automatic backups rather than UserDefaults.
- Local files use iOS Data Protection. The limited planning record uses
  CloudKit encrypted fields. Password-protected portable backups and report
  exports are created only when the user requests them; the app does not
  automatically upload these files.

## Sharing and purposes

Information is used only to provide app functionality requested by the user,
including organizing pregnancy tasks and sharing a workspace with an invited
partner. The app does not sell personal information, display advertising, use
health information for advertising, or track users across other companies'
apps and websites.

An invited partner receives access only after accepting Apple’s CloudKit share.
Only the name shortlist and its limited planning metadata are automatically
shared in this release. Medical/pregnancy records, journal content, support
requests and check-ins do not automatically appear on the partner’s device.
The report or recovery-export action opens the system share sheet; the user
chooses the destination and recipients. This does not enable ongoing medical
synchronization. Exported files can contain sensitive records, so choose their
destination carefully.

## Retention, deletion, and user control

Information remains until the user deletes individual items, deletes all data
from the Privacy and Data Management screen, removes the app, or explicitly deletes the applicable cloud data. Removing a
participant ends shared planning access; it does not erase personal medical
records from either iPhone. Full deletion removes protected local
records, documents, recovered cloud records, temporary exports, reminders,
backups, and owned CloudKit
workspace data. Cloud deletion may remain pending until the device reconnects.

Disconnecting a Files folder, changing the connected folder, or deleting Azygote
data does not delete copies in that external folder. Users must remove those
copies and manage access through Files or the selected provider. Likewise,
recipients retain documents and reports previously exported through the share
sheet.

Apple Health permissions can be changed at any time in iOS Settings. Automatic
foreground import can also be disabled inside Azygote.

## Security

The app uses protected local files, restricted storage paths, file type and size
validation, private notification previews by default, an optional Face ID app
lock, and authenticated encryption for password-protected portable backups.
No system can guarantee absolute security, so users should protect their Apple
Account, device passcode, backup password, and sharing invitations.

## Children

Azygote is intended for adults organizing a pregnancy. It is not
directed to children and does not knowingly collect information from children.

## Changes and contact

Material policy changes will update the date at the top of this page. Privacy
or support questions can be sent to yuvalpesi@gmail.com. Do not send medical
documents or urgent medical information by email.
