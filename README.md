# FragHub

**The web hub of the [Fragujemy](https://fragujemy.com) Counter-Strike network — online since 2012.**

FragHub puts everything the network knows about its servers and its players in one place, behind one account: live server state, rankings, the sanctions registry, the demo archive, news, creators, partners, player profiles and reports.

It is free to use. A newcomer can judge the network without signing up; a regular can settle a question — *am I banned, and why? which server has people on it right now? where did my rank go?* — in a few seconds.

## Why FragHub exists: what the forum can't do, and what FragHub fixes

The Fragujemy [forum](https://fragujemy.com) is where the community talks, and it still is. But a discussion board is the wrong tool for *looking things up*. Before FragHub, the facts players actually needed lived in separate places — game-server databases, plugin tables, forum threads — with nothing tying them to one person.

| Where the forum falls short | What FragHub does instead |
|---|---|
| **Facts are buried in threads.** To check a ban, a rank or a server, you search posts and hope someone updated them. | **Every fact has a page.** Live servers, rankings, sanctions and demos are read straight from what the game servers recorded, so they are current by construction, not by someone remembering to post. |
| **The data is scattered.** Bans, rankings, demos and skins sit in different systems and different schemas, per game. | **One place, three games.** CS 1.6, CS2 and CS:GO are gathered behind one set of pages, so you don't need to know which system holds what. |
| **No single identity.** A forum username is not your in-game account, so nothing connects your posts, rank, sanctions, skins and friends. | **One account for everything.** Sign in with Steam and rank, sanctions, demos, skins, reports, friends and profile all hang off the same identity. |
| **Outsiders can't judge the network.** A newcomer has to read forum history or ask on Discord to learn what the network is. | **Public pages answer the cold arrival.** Servers, ranks, bans, news and partners are readable without an account. |
| **Reports and sanctions are hard to follow.** A report is a thread; its outcome is whatever the replies say. | **Reports are cases.** Each has its own page with a dated history, followed publicly through to a decision. |
| **A forum can't configure your game.** | **Tools that act on the game.** Skinchanger, a customisable profile, friends and notifications live next to the data they use. |

FragHub does not replace the forum. Discussion, community and — for now — ban appeals stay there, and FragHub links to it throughout. The split is simple: **the forum is for conversation, FragHub is for facts and tools.**

## What's on the site

| Area | What it does |
|---|---|
| **Home** | The network at a glance: live servers, latest news, what's happening now. |
| **Servers** | Live catalogue of the network's CS 1.6, CS2 and CS:GO servers with current players and maps. |
| **Ranks** | Rankings and per-player statistics, with a page for every player. |
| **Bans** | Public sanctions registry for CS 1.6 and CS2: who, why, how long, issued by whom. |
| **Demos** | Archive of recorded matches to download and rewatch. |
| **Skinchanger** | Configure your weapon, knife, glove and agent skins, with an in-page tutorial. |
| **News · Creators · Partners** | Network announcements, streamers and content creators, partner communities. |
| **Profile & Settings** | Your public profile (customisable frames, patterns and surfaces), friends, notifications, language and layout preferences. |
| **Reports** | File a report against a player and follow the case publicly through to a decision. |
| **FAQ** | Rules, penalties and how the network works. |

Coming soon: **FragPass** and further reward features.

## Principles

1. **Finding beats browsing.** The measure of a page is how fast the one fact you came for reaches you.
2. **One identity carries everything.** Rank, sanctions, demos, skins, reports, friends and profile all hang off a single account that follows you across CS 1.6, CS2 and CS:GO.
3. **Authoritative play facts only.** The site shows what the game servers actually recorded. Progress, presence and standing are never invented in the browser.
4. **Free, in three languages.** Polish, English and Russian — nothing ships in only one.
5. **Restraint over ornament.** A composed, readable interface rather than a "gamer UI"; colour carries meaning, not glow.

## Part of a larger network

FragHub is the front door to the Fragujemy ecosystem: the [forum](https://fragujemy.com), the [shop](https://sklep.fragujemy.com), [Discord](https://dc.fragujemy.com) and [TeamSpeak](https://ts.fragujemy.com), plus the network's Twitch, Facebook, TikTok and Instagram. FragHub itself is free; the shop is where the network is supported.

## Games

CS 1.6, CS2 and CS:GO. CS 1.6 is where most of the actual play happens.

## Under the hood (briefly)

Static HTML, CSS and vanilla JavaScript pages — no front-end framework and no build step — on top of a small hand-written PHP API. Sign-in is through Steam. Staff moderate and publish content through a separate operations panel that is not part of the public experience.

## Status

Actively developed and running in production at [hub.fragujemy.com](https://hub.fragujemy.com).

## Contact

Questions and bug reports: join the network's [Discord](https://dc.fragujemy.com) or post on the [forum](https://fragujemy.com).
