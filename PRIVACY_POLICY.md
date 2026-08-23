# ELALEM Privacy Policy

**Last updated:** 23 August 2026  
**Applies to:** the ELALEM Discord bot and its EMSALI assistant features.

This policy explains what ELALEM receives, what it keeps, what it sends to other
services, and what you can remove. It is based on how ELALEM works today, not on
features that may exist later.

ELALEM is a hobby project run by an individual and offered free of charge. It is
not a company. This document is not a legal certification. Its purpose is much
simpler: to give you a clear and honest picture of what happens to your data.

---

## 1. What ELALEM is

ELALEM is a Discord bot with music, an economy, fishing, cosmetics, community
features, moderation tools and an AI assistant called EMSALI. It also includes
things such as free-game news, profiles, achievements and a player marketplace.

ELALEM has grown a lot since the older versions of this policy, so this document
now covers the full bot rather than only its early music and game-news features.

---

## 2. What this policy covers

This policy covers data ELALEM receives, stores or sends while providing its
Discord features.

It does not cover Discord itself. Your Discord account, messages, servers and
your relationship with Discord are covered by
[Discord's Privacy Policy](https://discord.com/privacy) and
[Terms of Service](https://discord.com/terms). ELALEM can only work with the
information Discord makes available to the bot for the features you use.

It also does not replace the privacy policies of third-party services used by
ELALEM. The main services ELALEM contacts are listed in section 7.

---

## 3. Information ELALEM receives from Discord

**Identifiers.** ELALEM uses your Discord user ID to associate data with your
account. Server, channel and role IDs may also be kept when a feature needs them.
Display names and avatars may be read when ELALEM needs to show them in a reply,
but they are not kept as a separate ELALEM profile.

**Message content** is handled only when it is needed for a feature, including:

- commands you send to ELALEM;
- messages sent directly to EMSALI, mentions of EMSALI, or messages in a channel
  a server has set aside for it;
- limited message content connected to a Sentinel moderation incident, where a
  short excerpt may be kept as evidence for moderators (section 12).

ELALEM does not use ordinary server conversation as background data for unrelated
features.

**Voice.** ELALEM can join voice channels to play audio. It does not record,
transcribe or store what people say in voice chat.

---

## 4. Information you give ELALEM directly

This includes things such as search terms, playlist requests, EMSALI questions,
marketplace listing details and anything you explicitly ask EMSALI to remember.

---

## 5. Information ELALEM creates while you use it

| What | What may be stored |
| --- | --- |
| **Listening history** | Up to your 200 most recent played tracks and when they were played |
| **Taste profile** | Genre and mood scores used for recommendations and AutoDJ |
| **Economy** | Balance, inventory, reward timers and transaction records |
| **Marketplace** | Listings, completed sales and transfer history for tradeable cosmetics |
| **Fishing** | Catches, progress, equipment, location and reward records |
| **Cosmetics** | Items you own and items you have equipped |
| **Profile** | Level, experience, reputation, achievement counters and visibility settings |
| **Community Moments** | Activities you took part in during a server's week |
| **Games** | Game/session state and completed shared records where needed |
| **Server configuration** | Language, channels, roles, feature settings and moderation settings |
| **Moderation** | Warnings, cases and Sentinel incident records for a server |
| **Operational logs** | Errors and diagnostics used to keep ELALEM working |

---

## 6. EMSALI memory, and what it will not remember

EMSALI can remember some things about you between conversations, but long-term
memory is opt-in.

**Nothing becomes a memory unless you ask for it.** EMSALI does not create a
profile from guesses, impressions or things it simply notices in conversation.

**Memories must be about you.** EMSALI will not create a lasting memory about
another person just because you ask it to.

**Some information is never accepted as long-term memory.** ELALEM refuses to
store durable EMSALI memories about:

- health, diagnoses, medication, treatment or disability status;
- religious or philosophical beliefs;
- political opinions or affiliations;
- sexual orientation or sex life;
- racial or ethnic origin;
- genetic or biometric information;
- criminal history;
- financial account, card or payment details, or highly sensitive financial
  circumstances;
- exact home addresses, precise private locations, private phone numbers or
  private contact details;
- passwords, API keys, tokens or other credentials;
- government identifiers.

You can still talk to EMSALI about these subjects. ELALEM may process the message
as needed to answer you, but it will not turn that information into a lasting
EMSALI memory.

If a memory request is refused, EMSALI tells you briefly and continues the
conversation.

**Older sensitive memories covered by these rules are removed through ELALEM's
cleanup process.** The cleanup keeps only minimal information about what was
removed, such as counts and category names. It does not copy the deleted memory
text into logs or reports.

**Shared memories.** Some memories from a shared exchange may be connected to
both participants. Either person can hide that memory from their own view. If a
shared memory is removed completely, it is no longer available to either person.

**Your controls.** `+memory` lets you see what EMSALI remembers about you, remove
individual memories, remove them all, or turn memory off. Turning memory off
stops new memories from being saved and stops existing memories from being used.
The memory controls are shown privately to you.

---

## 7. Third parties, and what they receive

ELALEM sends only the information needed for the feature you asked to use. The
services below do not receive your Discord identity unless this section says
otherwise.

### AI text generation

EMSALI and some recommendation features send the text needed to produce an
answer. This can include the current conversation, relevant EMSALI memories and
recent context needed to understand the request. Discord user IDs, server IDs
and channel IDs are not included in model prompts.

For user conversations, ELALEM uses **Groq**. Groq's current Services Agreement
states that Groq is not permitted to use inputs or outputs to train or fine-tune
models. ELALEM also blocks user-content fallback to an AI provider whose terms
would allow that kind of use. If no approved provider is available, EMSALI may be
temporarily unavailable instead of sending the same message somewhere less
private.

The production Groq account is configured with **Global Zero Data Retention**.
ELALEM does not claim that this means "the provider stores nothing" in every
possible sense. The important points are that the production account uses
Groq's least-retention option and Groq's terms do not permit using ELALEM inputs
or outputs to train or fine-tune models.

### Music and metadata

YouTube, Spotify, Deezer and SoundCloud may receive search terms and track
identifiers. Musixmatch may receive track and artist names when lyrics are used.
Internet radio hosts receive the request needed to play a stream.

### Content and utility services

Tenor and Giphy may receive search terms. An image-generation provider may
receive an image prompt. A weather service may receive a place name. Joke, quote
and meme services receive the request needed for the result. Steam, Epic Games,
GOG and Twitch may be queried for public information.

Each third-party service has its own terms and privacy policy.

**ELALEM does not sell your data.** It does not share personal data with data
brokers, advertising networks or analytics companies, and ELALEM does not show
advertising. Sending a search term to a service because you asked ELALEM to find
something is not the same as selling that data.

---

## 8. How long things are kept

| Category | Behaviour |
| --- | --- |
| The conversation EMSALI is answering | Used for the reply and not saved by ELALEM as long-term conversation history |
| Text sent to an AI provider | Transient for ELALEM; provider handling is subject to its own terms and the production ZDR setting described above |
| EMSALI memories | Until you delete them or turn memory off |
| Listening history | Up to the 200 most recent tracks; older entries are removed automatically |
| Track analysis cache | About 30 days |
| Economy, fishing, cosmetics and profile | Until deleted |
| Transaction, settlement and marketplace records | Kept where needed for shared transaction integrity; see section 9 |
| Community Moments | Kept for the server-week record where needed |
| Game session state | Until the active game finishes; some completed shared records may remain as described in section 9 |
| Server configuration | Until changed, or until the server-removal process in section 11 completes |
| Moderation and Sentinel records | Kept for the server that created them, then removed with that server's data after the removal window described in section 11 |
| Operational logs | Rotated, about 14 days by default |
| Deletion request records | Reference, category results, counts and timestamps; never the content that was deleted |

Where ELALEM does not have a fixed retention period, this policy does not invent
one just to make the table look more complete.

---

## 9. What may remain, and why

**Transaction and settlement records.** A payment, trade or marketplace sale can
involve more than one person. Minimal records may be kept where they are needed
to keep balances and shared transaction history consistent.

**Shared records.** A community activity or finished match involving several
people is not necessarily deleted in full because one participant asks. Where
possible, the requesting user's direct link to the record is removed while the
shared record remains.

**Moderation and security records.** Warnings, moderation cases and Sentinel
records are managed for the server that created them. A person mentioned in such
a record cannot erase the server's moderation history through `/deletion`.
These records are also not exposed through normal personal-data export routes.

**Operational logs.** Logs are rotated automatically and are used to diagnose
problems, not to build a profile about you.

If a record cannot be deleted automatically, `/deletion` tells you instead of
pretending the request fully succeeded.

---

## 10. Your data controls

**`/deletion`** is the main place to see, export and delete data connected to
your ELALEM account.

- **Your Discord account is your identity.** You do not need to enter a Discord
  ID, email address or separate form.
- **You choose what to remove.** Categories are shown by name, and you can pick
  individual categories or everything that is eligible for self-service
  deletion.
- **Deletion needs confirmation.** Before anything is removed, ELALEM shows what
  will be deleted and what may remain.
- **The flow is private.** Slash-command deletion controls are shown only to you.
  If you use the older prefix form in a server, ELALEM tries to continue the
  process privately instead of posting your data controls in public.
- **Results are honest.** If something is retained or a step fails, the result
  says so. A partial deletion is shown as partial, not as complete.

Other feature-specific controls still exist:

- **`+memory`** lets you view, delete or disable EMSALI memory;
- **`fishprivacy`, `profileprivacy` and inventory visibility controls** change
  who can see those parts of your profile. Visibility controls do not delete the
  underlying data.

If a request cannot be finished automatically, the result may include a
reference ID and the privacy contact below. You can use that reference without
putting private information into an email.

A separate web Privacy Center does not exist today. The controls described here
are available inside Discord.

---

## 11. Removing ELALEM from a server

Removing ELALEM stops it from providing features in that server immediately.

Server-owned data is scheduled for deletion **30 days after a confirmed
removal**. This includes things such as server configuration, configured channels
and roles, music/news settings, moderation history and Sentinel state.

If ELALEM is added back during those 30 days, the pending deletion is cancelled.
This protects a server from losing its setup because the bot was removed by
mistake or only for a short time.

A temporary Discord outage does not count as a confirmed removal.

Your own global ELALEM data, such as economy progress, fishing progress,
cosmetics, profile data and EMSALI memories, is not deleted just because one
server removes the bot. That data may be used across more than one server and is
controlled through your own data controls instead.

Server administrators who want help with server data can use the support server.

---

## 12. Moderation and Sentinel

Servers can choose to use ELALEM's moderation and Sentinel features. These may
keep warnings, cases and limited incident evidence so server moderators can
review what happened.

Sentinel may keep a short, clipped excerpt from messages connected to an
incident. These records are for the server's moderation and security use. They
are not used to build EMSALI memory or advertising profiles, and they are not
shared with unrelated servers.

---

## 13. Security

ELALEM is designed to keep credentials out of logs, limit what is sent to other
services, and keep stored data within the systems used to operate the bot.

No online service can promise perfect security. Please avoid sending ELALEM
information that would seriously harm you if it were exposed. The EMSALI memory
rules in section 6 are there to reduce that risk further.

---

## 14. Age

ELALEM is used through Discord and follows Discord's minimum age requirements,
which are at least 13 and may be higher depending on where you live.

ELALEM is not intended for people below Discord's required age. If you believe
ELALEM holds data about someone who should not be using Discord under those
rules, contact the **ELALEM support server** so the situation can be reviewed.
If you cannot use the support server, you can also write to
**privacy@elalem.dev**.

---

## 15. Changes to this policy

This policy may change as ELALEM changes. The date at the top shows the latest
update. Material changes will be announced through ELALEM's support server.

---

## 16. Contact

**For normal deletion requests, use `/deletion`.** It is the fastest option and
does not require you to explain your data to anyone.

**For help, privacy questions, escalations, bug reports or anything `/deletion`
could not finish, start with the
[ELALEM support server](https://discord.gg/JDKjRhpq79).**

If you cannot use the support server, or you need an email contact for a privacy
matter, you can write to **privacy@elalem.dev**.

That address can receive privacy messages, but it is an inbound contact address
rather than a mailbox ELALEM sends replies from. A reply may therefore come
through the support server or another verified ELALEM contact.

If you contact us by email, include your Discord username or user ID so we can
find the right account. If you already have a deletion reference, include that
too.

ELALEM will never ask you to send confidential information by email. If a
message claiming to be from ELALEM asks for it, do not send it.

Related: [Terms of Service](TERMS_OF_SERVICE.md)
