# Privacy Policy — OPTCG Tracker

**Last updated: 1 October 2026**

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

If you signed up with email and password, you can also **connect** a Google
account later, so either way signs you in. Firebase Authentication then holds
that Google account's email address alongside your own; the app shows it only
to you, on your profile, and you can disconnect it again there.

**Profile information.** A display name, an automatically generated friend code,
and an optional avatar. You choose the display name; it does not have to be your
real name.

**Friends.** Who you are friends with, and the friend requests you send and
receive. A friendship needs both people to accept it. The app uses it to let
you pick a friend as an opponent and to show how often and how recently you
have played each friend. You do not need any friends to use the app, and you
can remove a friend at any time. The app never reads your phone's contacts.

**Blocking.** You can block another player. A blocked player can no longer
send you friend requests, log matches against you, or join events you host,
and they are not told. Your list of blocked players is visible only to you,
and you can unblock anyone at any time. Blocking does not hide your profile
or matches from them; see "Who can see your data".

**Match data you enter.** For each match: the Leader cards played, who went
first, the result, the date, the match type, and any notes you add. Matches
against a registered opponent are shared with that opponent and require their
confirmation. **A match record is readable by any signed-in user** — see "Who
can see your data" below. Your notes on it are not.

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

**Aggregate statistics.** A summary of your confirmed matches is published for
the leader matrix: for each of your decks, how it did against each opposing
deck and how often you went first, broken down by kind of game, card set and
the day the games were played, plus whether each of your events was a weekly
or a tournament. It holds totals, not individual games.

The app contains **no advertising, no analytics, and no third-party tracking**.
It does not collect your location, contacts, device identifiers, or usage
telemetry, and it does not sell or share data with advertisers.

## Who can see your data

- **Your email address:** only you. It is held by Firebase Authentication and is
  never written to the app's database.
- **Your profile, aggregate stats, and deck photos:** visible to any signed-in
  user of the app. This is what makes it possible to find friends by name or
  friend code. Do not put anything private in a display name or a deck photo.
- **Your matches:** visible to any signed-in user of the app. A match record is
  the decks, who went first, the result, the date and the kind of game — the
  same sort of thing a results sheet at an event shows. **Only you and your
  opponent can create or change one**, whoever can read it.
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

You can delete your account from inside the app: open your **Profile**, scroll
to **Settings**, and tap **Delete my account**. It asks you to type "delete"
and to sign in again to prove it is you, then removes your
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
