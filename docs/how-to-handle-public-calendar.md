# How to create and configure meetings

In OpenTelemetry we are using the CNCF's Zoom accounts. We currently own five
identical zoom accounts.

All rooms are configured the same way. Some notes on meetings configuration:

- **The host is not required** to join the meeting. Anybody can join the meeting.
- **There is no time limit on the length of the meeting**. Please make sure nobody is
  using this room for another meeting on the calendar when meeting is going long
  over time.
- **Auto-recording is enabled for all meetings**. All OpenTelemetry public meetings are recorded automatically
  and [available on Zoom cloud](https://docs.google.com/spreadsheets/d/1SYKfjYhZdm2Wh2Cl6KVQalKg_m4NhTPZqq-8SzEVO6s).

Every meeting must contain a link to the meeting notes. The meeting notes
document must be shared with write or commenting permissions. If giving edit permissions to everyone,
go into the document share settings and uncheck "Editors can change permissions and share".

Anyone can request to be added or removed as a meeting participant. Request can
be made via GitHub issue on this repository or contacting SIG maintainer via
other channels like Slack.

All meetings must include [OpenTelemetry Calendar Invites Google Group](https://groups.google.com/g/opentelemetry-calendar)
as a participant. Anybody who wants to receive up to date invites for all OpenTelemetry
meetings can join the group.

## Steps
To create or edit a meeting, you need to have access to the Public OpenTelemetry calendar (a shared Google calendar) and you must add a Zoom meeting link.

### Gaining Calendar Permissions
All SIG maintainers can get access to edit the public OpenTelemetry calendar
by submitting a request to join the [opentelemetry-calendar-contributors Google Group](https://groups.google.com/g/opentelemetry-calendar-contributors).
If your identity is not recognizable from the e-mail you are using to request joining the group, please
request to be added to this Google Group by creating an issue in this repository.

Please keep the membership of this group up to date and accurate.

### Create the meeting
The following details need to be set properly:
- Title
- Timeslot (make sure to use the correct time zone - Pacific Time - as the dates for switching DST differs between countries)
- Recurrence pattern (usually weekly or bi-weekly)
- Location (see below for the Zoom links)
- Description
  - A brief description on the scope of the meeting
  - A link to the meeting notes
    - The meeting notes should be owned by the shared Governance Committee Google account.
      Having a document created can be requested from the GC via opening an issue in this repository.
- Invited attendees: opentelemetry-calendar@googlegroups.com (see note on this Google Group above)

### Adding a Zoom link to a meeting
Open an issue in the community repository, requesting a new Zoom link.
By requesting a new Zoom link that is only associated with a single meeting series, the meeting recordings
can be associated with a meeting name.
The Zoom link will be created in one of the 5 OpenTelemetry Zoom account.
A single Zoom account should not be used for back-to-back meetings or for more than two meetings at the same time.
You can see which Zoom account any potentially conflicting meetings are using in the meeting descriptions.
(Note: posting the URLs publicly on GitHub leads to Zoom bombing by random bots).

### Update the meetings overview
All recurring meetings are listed in the [Community repo's README](../README.md#special-interest-groups), make sure to add/update the respective entry there.

## Zoom bombing prevention
All meetings are created by Zoom with randomized passcodes, which are embedded into the shared calendar links.
All members of opentelemetry-calendar-contributors@googlegroups.com have access to [this document](https://docs.google.com/document/d/1gt9ctxKGPrM_XTINqLgkSxYypdrczHkt2znjwgBU4UU/edit#)
listing the host keys for our meetings and explaining how to deal with inappropriate behavior in Zoom.
