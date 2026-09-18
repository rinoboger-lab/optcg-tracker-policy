# Privacy Policy — OPTCG Tracker

**Last updated: 12 August 2026**

OPTCG Tracker ("the app") is a hobby app for logging One Piece Card Game matches
between friends. This policy explains what the app stores, who can see it, and
how to get it deleted.

The app is operated by an individual developer, not a company. Contact:
**gango.friesss@gmail.com**

## What the app collects

**Account information.** When you create an account you provide an email address
and a password. Authentication is handled by **Firebase Authentication** (Google
LLC). The app never sees or stores your password — Firebase stores it in hashed
form. Your email address is used to sign you in, to verify your account, and to
send password-reset messages. Your email address is *not* stored in the app's
database and is not visible to other users.

**Profile information.** A display name, an automatically generated friend code,
and an optional avatar. You choose the display name; it does not have to be your
real name.

**Match data you enter.** For each match: the Leader cards played, who went
first, the result, the date, the match type, and any notes you add. Matches
against a registered opponent are shared with that opponent and require their
confirmation.

**Tournament and deck data you enter.** Tournament names, placings, and — if you
choose to attach them — photographs you take of tournament ranking screens and
of your own decklists. Images are only ever added by you, from your camera or
photo library, one at a time.

**Aggregate statistics.** Your overall win rate and game counts are computed from
your confirmed matches and stored on your profile so friends can see your record.

The app contains **no advertising, no analytics, and no third-party tracking**.
It does not collect your location, contacts, device identifiers, or usage
telemetry, and it does not sell or share data with advertisers.

## Who can see your data

- **Your email address:** only you. It is held by Firebase Authentication and is
  never written to the app's database.
- **Your profile, aggregate stats, and deck photos:** visible to any signed-in
  user of the app. This is what makes it possible to find friends by name or
  friend code. Do not put anything private in a display name or a deck photo.
- **Your matches:** visible only to the two players in that match.
- **Friend requests:** visible only to the two users involved.

These boundaries are enforced by Firestore security rules on Google's servers,
not just by the app.

## Where data is stored

Data is stored in **Google Cloud Firestore** and **Firebase Authentication**,
operated by Google LLC as the app's data processor, and is transmitted over
encrypted connections (TLS). See Google's privacy policy at
https://policies.google.com/privacy.

Card and Leader information is fetched from the public One Piece card API at
optcgapi.com. These requests contain no personal data.

## Data retention and deletion

Your data is kept until you ask for it to be deleted.

To delete your account and all associated data, email **gango.friesss@gmail.com**
from the address the account was registered with. Your profile, matches,
tournaments, and deck photos will be deleted within 30 days. Matches you played
against another user are shared records; your side of them will be removed.

## Children

The app is not directed at children under 13 and does not knowingly collect
their data.

## Changes

If this policy changes, the date at the top of this page will be updated.
