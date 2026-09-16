# Privacy Policy — The Armory

**Last updated:** 15 September 2026  
**App:** The Armory (eso-guild-keep), a free fan-made companion for Elder Scrolls Online guilds.  
**Owner:** Ivan Rodriguez.

This is a plain-language privacy policy for a small fan app. It is not legal theater. The Armory is **not affiliated with** Bethesda Softworks, Zenimax Online Studios, ZeniMax Media, or The Elder Scrolls® Online.

**This app is not for children under 13.** We do not knowingly collect personal information from children under 13. If you believe a child under 13 created an account, contact the owner so the account can be deleted.

## Who this is for

Players 13 or older who sign in with email and password, Google, or Apple to keep guild roster, applications, DMs, and character sheets across devices.

## What we collect

| Data | Why |
|------|-----|
| **Account / email** | Sign-in (email/password, Google, or Apple). Email lives in the auth system and is copied onto your profile so officers and you can tell accounts apart. Apple may give a relay address (`privaterelay.appleid.com`) if you hide your email. |
| **Profile** | Username, display name, platform (PS5 / Xbox / PC-Mac), avatar if you upload one, accent color, XP, last login, notification prefs. |
| **Guild data** | Guilds you found or join: name, motto, about, social links, modules, roles, roster, trader hire, bans. Leaders can see applications and reports for their guild. |
| **Direct messages** | 1:1 DMs between two signed-in players. We store the text so both of you can read the thread. |
| **Applications** | When you apply to a guild: your message, platform username, and any character cards you attach. |
| **Characters** | Armory sheets you save (class, gear, skills, notes). Guild mates in a shared guild may be able to **read** roster sheets. Only you can edit yours. |
| **Push tokens** | On a phone in Expo Go (or a later native build), a device push token so we can send DMs / craft / bid alerts you opted into. Deleted on sign-out. Web does not register a push token. |
| **Reports** | If you report a message or player, we store the report for guild officers. |

We do **not** collect precise location, contacts, health, payment cards, or government IDs.

## Analytics

**None.** The Armory does not embed Google Analytics, Facebook SDK, advertising SDKs, or similar trackers. We do not sell your data. We do not use it to advertise to you.

Crash or usage metrics that Expo or the store might collect on a future standalone build are those vendors’ policies, not extra analytics we added in this app.

## Who sees what

Access is enforced by the server (row-level security), not only by the app UI.

- **You** can read your own profile, memberships, characters, DMs you are in, and applications you sent.
- **Guild members** can see the roster and (today) character sheets of people they share a guild with.
- **Leaders / officers** can review applications, kick/ban, and see guild reports, according to their role.
- **Anyone signed in** can currently search guilds and (until we tighten directory privacy) see other players’ public profile fields used for compose / invite. Treat DMs like talking to someone you have not met.

## Third parties that process data for us

| Service | Role |
|---------|------|
| **Supabase** (hosted Postgres + Auth) | Accounts, database, and realtime. Data lives on Supabase’s cloud for this project. |
| **Expo** | App runtime, and Expo’s push API when a phone token is registered. |
| **Google Sign-In / Apple** | Optional identity providers. They see the OAuth consent (and, for Apple, Hide My Email if you choose it). They do not receive your Armory DMs or character sheets. |

We do not hand your DMs or sheets to Bethesda, advertisers, or other games.

## How long we keep it

Until you delete your account, or the owner deletes the project. Signing out leaves the cloud account in place. **Delete my account** (Settings) removes the auth user and cascades related public data (see the in-app flow). Guilds you **lead** are deleted with your account if you have not transferred leadership first.

Device-only extras (raffles, research clocks, completions, progression, guild chat) live on that device’s storage and are not a full cloud copy.

## Your choices

- **Export my data** — Settings. Downloads JSON of what this signed-in client can read (profile, memberships, your characters, DMs you are in, your applications, plus device-only extras). It does **not** dump other people’s private rows, server push-outbox, or auth password hashes. A later server-side export could fill those gaps if a store or regulator requires it.
- **Delete my account** — Settings. Confirm, then we call a server function as **you** (never a secret key in the app) and sign you out.
- **Push** — OS permission plus in-app notification toggles. Sign-out drops the token we stored.
- **Email** — Used for sign-in. We do not run a marketing list.

## Contact

**Ivan Rodriguez**, owner of The Armory. Use Settings → About in the app, or the GitHub repository for this project. There is no separate support inbox in this build.

If you are in a region with a statutory privacy request (access, delete, correct), use Export / Delete in Settings first, then contact the owner if something is still missing.

## Fan disclaimer

The Elder Scrolls® Online and related marks belong to ZeniMax Media and its affiliates. The Armory is an unofficial fan companion. Skill tooltips and icons credit ESO-Hub where shown in-app.
