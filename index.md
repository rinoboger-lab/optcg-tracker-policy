# Privacy Policy — OPTCG Tracker

**Last updated: 22 September 2026**

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

**Signing in with Google.** You may instead sign in with a Google account. In
that case Firebase Authentication receives your Google account's email address,
display name and profile picture link from Google, and the app uses the display
name as your initial profile name, which you can change. No password is created
or stored by the app for a Google sign-in.

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

**Simulator sittings.** If you log games on a simulator you may record the
in-game bounty you started and finished a sitting on. This is optional and you
can skip it. The log itself — every sitting, both ends, which games were in it
— is visible only to you. The **most recent bounty** is published to your
profile and is visible to any signed-in user, so friends can see where you
stand.

**Aggregate statistics.** Your overall win rate and game counts are computed from
your confirmed matches and stored on your profile so friends can see your record.
This includes, for each of your decks, how it did against each opposing deck and
how often you went first — the numbers behind the leader matrix.

The app contains **no advertising, no analytics, and no third-party tracking**.
It does not collect your location, contacts, device identifiers, or usage
telemetry, and it does not sell or share data with advertisers.

## Who can see your data

- **Your email address:** only you. It is held by Firebase Authentication and is
  never written to the app's database.
- **Your profile, aggregate stats, and deck photos:** visible to any signed-in
  user of the app. This is what makes it possible to find friends by name or
  friend code. Do not put anything private in a display name or a deck photo.
- **Your matches:** visible only to the two players in that match — and, for a
  round played at an event someone else is running in the app, to that event's
  organiser, who recorded the result.
- **Friend requests:** visible only to the two users involved.
- **Your simulator sitting log and private match notes:** visible only to you.
  Your most recent bounty is the exception: it sits on your profile, which any
  signed-in user can read.

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

You can delete your account from inside the app, under **Settings → Delete
account**. It asks you to sign in again to prove it is you, then removes your
profile, matches, tournaments, deck photos, private notes, simulator sittings
and published statistics, and finally the account itself. Matches you played
against another user are shared records; your side of them is removed.

If you would rather not do it yourself, email **gango.friesss@gmail.com** from
the address the account was registered with and it will be done within 30 days.

## Children

The app is not directed at children under 13 and does not knowingly collect
their data.

## Changes

If this policy changes, the date at the top of this page will be updated.
