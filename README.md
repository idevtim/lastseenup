# Last Seen Up

**Know when it's down. Sleep through the rest.**

Last Seen Up watches your sites, servers and scheduled jobs around the clock,
double-checks every failure before it wakes anyone, and sends the alert straight
to your phone.

[lastseenup.com](https://lastseenup.com)

---

## What it watches

| Check | What it asks |
|---|---|
| **HTTP** | Loads your page or API and checks the status code, headers and content you expect |
| **TCP** | Opens a connection to a port |
| **Ping** | Sends an ICMP ping to the host |
| **DNS** | Looks up your records and compares them to what they should be |
| **SSL** | Checks the certificate your site is serving and how many days it has left |
| **Domain** | Checks the domain registration itself, straight from the registry |
| **Heartbeat** | Nothing. Your job checks in with us, and silence is the alarm |

A website is a single monitor: point it at a URL and the certificate and the
domain registration behind it are watched too, with warnings weeks before either
expires. Heartbeats invert the direction — your cron job, queue worker or backup
script calls a URL when it finishes, and we page you when it stops calling.

## What happens when something breaks

**A failure is confirmed before anyone is woken.** A single failed check does not
open an incident: the failure has to repeat, and where checks run from more than
one region, enough regions have to agree. Recovery is the other way round —
every reporting region has to agree the monitor is healthy before an incident
closes, so a flaky recovery cannot resolve something that is about to break
again.

**Alerts escalate until somebody answers.** A push notification arrives first,
delivered as Time Sensitive so it breaks through Focus. If nobody acknowledges,
the alert repeats, then climbs to a phone call. Acknowledging stops the ladder
from any device — including straight from the notification, without unlocking
your phone or opening the app.

**Noise is treated as a bug.** A monitor that keeps bouncing is collapsed into a
single flapping notification rather than twenty. A slow site is reported as
degraded and does not page. Work planned inside a maintenance window still
appears in the incident history, but does not wake anyone.

## On your phone

A native iPhone, iPad and Apple Watch app:

- **Live Activities** count an outage up on the lock screen, and end on the
  number that matters: "Back up after 41m".
- **Home and lock screen widgets**, plus watch complications, showing the worst
  monitor or the ones you pick.
- **Acknowledge and snooze from the notification itself**, with the app closed.
- **Siri and Shortcuts** for pausing, resuming and asking what the status is.
- On the watch: your monitors at a glance, incident alerts with Acknowledge and
  Snooze, and a complication on the face. Creating and editing monitors stays on
  the phone, where a tap is less likely to be a sleeve.

The widgets say when the app itself has lost contact with the service, because a
widget showing green when nothing has been heard for hours is worse than one
saying so.

## On the web

The dashboard is for the morning after: availability over 7 or 30 days, latency
history, incident timelines showing exactly when each failure was seen,
confirmed, notified, acknowledged and resolved, and renewal deadlines for every
certificate and domain you have.

Teams get roles — owner, admin and member — and a member can be given access to
specific monitors rather than everything. Escalation policies decide who is told,
through which channel, and how long each rung waits.

## Plans

A free tier, and Pro. Subscriptions can be bought on the web or through the iOS
app; you are billed once either way. Full pricing is on
[lastseenup.com](https://lastseenup.com).

## Documentation & Support

- **Documentation** - [GitHub Wiki](https://github.com/idevtim/lastseenup/wiki)
- **Bug Reports** - [GitHub Issues](https://github.com/idevtim/lastseenup/issues)
- **Feature Requests** - [GitHub Discussions](https://github.com/idevtim/lastseenup/discussions)

Security reports go to [support@lastseenup.com](mailto:support@lastseenup.com)
directly, not to a public issue.

## Contact

**Email:** support@lastseenup.com
**Website:** https://lastseenup.com

## Legal

- [Privacy policy](https://lastseenup.com/privacy)
- [Terms of service](https://lastseenup.com/terms)
- [Cookie policy](https://lastseenup.com/cookies)

Last Seen Up is a **hosted service**. This repository is the public home for the
project — issues, release notes and documentation. It contains no application
source: Last Seen Up is proprietary, the source is not distributed, and there is
no self-hosted edition.

---

**© 2026 Last Seen Up** • Built for the people who get woken up
