# iOS Podcast Player App Comparison

*Last updated: May 2026*

🔔 **Major changes since the last revision:**

- **Breaker** was acquired by Twitter in Jan 2021 and shut down — moved to the *Discontinued Apps* appendix.
- **Castro** was sold by Tiny to indie studio **Bluck Apps** in January 2024 after a public near-death scare. It is alive and being actively maintained.
- **Apple Podcasts** added full transcripts (iOS 17.4, March 2024) and AI-generated chapters + timed links (iOS 26.2, Nov 2025).
- **Overcast** added transcripts in version 2026.4 (April 2026), powered by a rack of 48 Mac minis running Apple's speech-recognition API from the 26-series OSes.
- **Pocket Casts** made its web and desktop apps free for everyone (March 2025) and shipped a major v8.0 release in November 2025.
- **Snipd**, **Castbox**, **Spotify**, **Fountain**, and **Podverse** have been added as currently-notable iOS podcast players.
- **Procast** retained in the table — it is still on the App Store but receives only occasional updates and limited press coverage.

Please help keep this updated by [leaving a comment](https://github.com/hbmartin/ios-podcast-player-comparison/issues) or by [editing this doc](https://github.com/hbmartin/ios-podcast-player-comparison/edit/main/README.md)!

## Contents

- [Chapters and Notes](#chapters-and-notes)
- [Playback and Playlists](#playback-and-playlists)
- [File Formats, Devices, and Subscriptions](#file-formats-devices-and-subscriptions)
- [Controls and Downloads](#controls-and-downloads)
- [Sync and Import / Export](#sync-and-import--export)
- [Other](#other)
- [Acronyms](#acronyms)
- [Articles and Reviews](#articles-and-reviews)
- [Appendix: Discontinued Apps](#appendix-discontinued-apps)

## Legend

- ✅ = supported
- 🚫 = not supported
- ⚠️ = partial support
- 💲 = paid (subscription / IAP) feature
- *(blank)* = could not be verified from recent reliable sources

## Chapters and Notes

|  | Chap. Mark | MP3 Chap. Mark | Choose Chaps. | Chap. Duration | Chap. Start Time | Chap. End Time | Chap. Image | Notes for DL'd | Notes w/o DL |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Overcast | ✅¹ | ✅ | ✅ | ✅ | ✅ |  | ✅ | ✅ | ✅ |
| Castro | ✅💲² | ✅ | ✅💲 | ✅ | 🚫 | 🚫 | ✅ | ✅ | ✅ |
| Downcast | ✅³ | ✅ | ✅ | ✅ | ✅ | 🚫 | ✅ | ✅ | ✅ |
| iCatcher! | ✅⁴ | ✅ | ✅ | ✅ | ✅ | 🚫 | ✅ | ✅ | ✅ |
| Pocket Casts | ✅ | 🚫 | ✅💲⁵ | ✅ | 🚫 | 🚫 | ✅ | ✅ | ✅ |
| Procast |  |  |  |  |  |  |  | ✅ | ✅ |
| Apple Podcasts | ✅⁶ | ✅ | ✅ | ✅ | ✅ | 🚫 | ✅ | ✅ | ✅ |
| RSSRadio | ✅ |  |  | 🚫 | ✅ | 🚫 | ✅ | ✅ | ✅ |
| Player FM |  |  |  |  |  |  |  |  |  |
| Snipd | ✅⁷ |  | ✅ | ✅ | ✅ |  |  | ✅ | ✅ |
| Castbox | ✅ |  |  |  |  |  |  | ✅ | ✅ |
| Spotify | ✅⁸ | ⚠️ | ✅ | ✅ | ✅ |  | 🚫 | ✅ | ✅ |
| Fountain | ✅⁹ | ✅ | ✅ | ✅ | ✅ |  | ✅ | ✅ | ✅ |
| Podverse | ✅¹⁰ | ✅ | ✅ | ✅ | ✅ |  | ✅ | ✅ | ✅ |

1. Overcast added chapter art and richer chapter handling alongside transcripts in the 2026.x line.
2. Castro Plus required for chapter selection / playback enhancements.
3. Downcast: "Chapters support for enhanced podcasts" (App Store listing).
4. iCatcher!: "Support for podcasts with chapters and chapter images (MP3 and M4A)" (App Store listing).
5. Pocket Casts Plus required for Chapter Preselection (per 9to5Google, March 2025).
6. With iOS 26.2, Apple Podcasts auto-generates chapters when creators do not provide them; per-chapter images supported when creators submit them.
7. Snipd generates AI chapters when creators do not provide them.
8. Spotify supports creator-supplied chapters on Spotify-exclusive shows; partial support for MP3-tag chapters on RSS shows.
9. Fountain supports Podcasting 2.0 chapters with per-chapter art.
10. Podverse is "Podcasting 2.0 certified" — supports chapters, transcripts and cross-app comments natively.

## Playback and Playlists

|  | Sleep Timer | Trim Silence | Play Speed | Vol. Boost | Bookmarks | Personal Playlist | Personal Smart Playlist | Predef. Smart Playlist |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Overcast | ✅ | ✅¹¹ | ✅ | ✅¹¹ | 🚫 | ✅ | ✅ |  |
| Castro | ✅ | ✅💲 | ✅ | ✅💲 | ✅💲 | ✅ | ✅ | ✅ |
| Downcast | ✅ | 🚫 | ✅ | ✅ | 🚫 | ✅ | ✅ | ✅ |
| iCatcher! | ✅ | 🚫 | ✅ | 🚫 | ✅ | ✅ | ✅ | ✅ |
| Pocket Casts | ✅ | ✅ | ✅ | ✅ | ✅💲¹² | ✅ | ✅ | ✅ |
| Procast | ✅ | 🚫 | ✅ | 🚫 |  | ✅ |  |  |
| Apple Podcasts | ✅ | 🚫 | ✅¹³ | 🚫 | 🚫 | ✅ | ⚠️ | ✅ |
| RSSRadio | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | 🚫 | ✅ |
| Player FM | ✅ | 🚫 | ✅ | 🚫 | ✅💲 | ✅💲 |  |  |
| Snipd | ✅ | 🚫 | ✅ |  | ✅¹⁴ | ✅ |  | ✅ |
| Castbox | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |  |  |
| Spotify | ✅ | 🚫 | ✅ | 🚫 | 🚫 | ✅ | 🚫 | ✅ |
| Fountain | ✅ | 🚫 | ✅¹⁵ | 🚫 |  | ✅ |  | ✅ |
| Podverse | ✅ |  |  |  | ✅💲 | ✅💲 |  | ✅ |

11. Overcast's "Voice Boost" and "Smart Speed" are signature features (Marco Arment, Overcast.fm).
12. Pocket Casts Plus required for Bookmarks (per 9to5Google).
13. Apple Podcasts in iOS 26 adds Enhance Dialogue and a wider range of playback speeds (BGR ranking, 2025).
14. Snipd's "snips" function as time-stamped bookmarks with AI transcript.
15. Fountain supports up to 3× playback speed (App Store listing).

## File Formats, Devices, and Subscriptions

|  | AirPlay | CarPlay | Siri Shortcuts | iPad | Landscape | Push new eps. | Custom Sub. Sort | Alpha. Sub. Sort | Video |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Overcast | ✅ | ✅ | ⚠️ | ✅ | 🚫 | ✅ |  |  | 🚫 |
| Castro | ✅ | ✅ | ✅ | 🚫 | 🚫 | ✅ | 🚫 | ✅ | 🚫 |
| Downcast | ✅ | ✅ | ⚠️ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| iCatcher! | ✅ | ✅¹⁶ | ✅ | ✅ | ✅ | 🚫 | ✅ | ✅ | ✅ |
| Pocket Casts | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| Procast | ⚠️ | ✅ |  | 🚫 |  | ✅ |  | ✅ | ✅ |
| Apple Podcasts | ✅ | ✅ | ✅ | ✅ | 🚫 | ✅ | ✅ | 🚫 | ✅ |
| RSSRadio | ✅ |  |  | ✅ | ✅ | ✅ | 🚫 | ✅ | ✅ |
| Player FM | ✅ | ✅¹⁷ | 🚫 | ✅💲 |  | ✅💲 |  |  | ✅ |
| Snipd | ✅ | ✅ |  | ⚠️ |  | ✅ |  | ✅ | ⚠️¹⁸ |
| Castbox | ✅ | ✅ |  | ✅ |  | ✅ |  | ✅ | ✅ |
| Spotify | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| Fountain | ✅ | ✅ |  | ✅ |  | ✅ |  |  | ✅ |
| Podverse | ✅¹⁹ | ✅ |  | ✅ |  | ✅💲 |  | ✅ | ✅ |

16. iCatcher! release notes (Dec 2024) reference CarPlay reliability fixes; support is current.
17. Player FM added CarPlay support in a Maple Media release per the iOS App Store listing.
18. Snipd primarily handles audio podcasts, but offers 2–5 min video highlights from select shows (e.g. Huberman Lab, Modern Wisdom) per snipd.com/all-features.
19. Podverse supports video and livestream playback.

## Controls and Downloads

|  | AirPod Ctrl. | Skip Intro | Skip Outro | Play DL'ing Ep. | Parallel DL's | Ep. Stream | Pass.-protected | Auto DL Opts | Disk Space Mgmt |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Overcast | ✅ | ⚠️ | ✅ | 🚫 | ✅ | ✅ | ✅ | ✅ | 🚫 |
| Castro | ✅ | ✅ | 🚫 | ✅ | ✅ | ✅ |  | ✅ | ✅ |
| Downcast | ✅ | ✅²⁰ | ✅²⁰ | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️ |
| iCatcher! | ✅ | ✅ |  | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️ |
| Pocket Casts | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | 🚫 | ✅ | ✅ |
| Procast | ✅ | 🚫 | 🚫 | ✅ |  | ⚠️ | 🚫 |  |  |
| Apple Podcasts | ✅ | 🚫 | 🚫 | ✅ | ✅ | ✅ | 🚫 | ✅ | 🚫 |
| RSSRadio | ✅ | ✅ |  | 🚫 | ✅ | ✅ | ✅²¹ | ✅ | 🚫 |
| Player FM | ✅ |  |  | ✅ |  | ✅ |  | ✅ | ✅💲²² |
| Snipd | ✅²³ | ✅²⁴ | ✅²⁴ | ✅ |  | ✅ |  | ✅ |  |
| Castbox | ✅ |  |  | ✅ | ✅ | ✅ |  | ✅ |  |
| Spotify | ✅ | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅²⁵ | ✅ | ⚠️ |
| Fountain | ✅ |  |  | ✅ |  | ✅ |  | ✅ |  |
| Podverse | ✅ |  |  | ✅ |  | ✅ |  | ✅ |  |

20. Downcast supports per-podcast intro/outro skip ranges (App Store reviews).
21. RSSRadio explicitly supports password-protected feeds, including 1Password (App Store listing).
22. Player FM Premium's "Space Saver" compresses downloaded MP3s (Buzzsprout review, official support).
23. Snipd uses AirPod triple-tap as default snip trigger — overrides standard skip-back (App Store reviews, Snipd Discord).
24. Snipd offers "Auto-skip intros and outros for specific shows based on AI-generated chapters" (snipd.com/all-features).
25. Spotify supports password-protected (paid-subscription) feeds for Patreon-linked shows and member podcasts.

## Sync and Import / Export

|  | Cross-Device Sync | Sync Tech. | Import Music Lib. | OPML Export | OPML Import | Podcast Dir. | Paged Feed |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Overcast | ✅ | Proprietary | 🚫 | ✅ | 🚫 | ✅ |  |
| Castro | ⚠️²⁶ | Proprietary | 🚫 | ✅ | ✅ | ✅ |  |
| Downcast | ✅ | iCloud | ✅ | ✅ | ✅ | ✅ | 🚫 |
| iCatcher! | ✅ | iCloud | ⚠️ | ✅ | ✅ | ✅ |  |
| Pocket Casts | ✅ | Proprietary | ✅ | ✅ | ✅ | ✅ | ✅ |
| Procast | 🚫 | — |  | 🚫 | ✅ | ✅ |  |
| Apple Podcasts | ✅ | iCloud | ✅ | 🚫 | 🚫 | ✅ |  |
| RSSRadio | ✅ | iCloud | ✅ | ✅ | ✅ | ✅ |  |
| Player FM | ✅💲 | Proprietary |  | ✅ | ✅ | ✅ |  |
| Snipd | ✅ | Proprietary |  | ✅ | ✅ | ✅ |  |
| Castbox | ✅ | Proprietary |  | ✅ | ✅ | ✅ |  |
| Spotify | ✅ | Proprietary | ✅ | 🚫 | 🚫 | ✅ |  |
| Fountain | ✅ | Proprietary |  | ✅ | ✅²⁷ | ✅ |  |
| Podverse | ✅💲 | Proprietary |  | ✅ | ✅ | ✅²⁸ |  |

26. Bluck Apps stated in January 2024 that cross-device sync is on the post-stabilization roadmap; full sync is still partial/in development as of recent releases.
27. Fountain OPML import has been reported as flaky by users (Apple App Store reviews).
28. Podverse exposes the open Podcast Index directly.

## Other

|  | Price (annual) | Multi-Platform | Transcripts | Clip Share | Per-Podcast Settings | Subscribe URL Scheme | Wikidata ID |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Overcast | $14.99/yr Premium²⁹ | Web (login) | ✅³⁰ | ✅ | ✅ | `overcast://x-callback-url/add?url=` | [Q20707973](https://www.wikidata.org/wiki/Q20707973) |
| Castro | $29.99/yr Plus³¹ | iOS only | 🚫 | ✅ | ✅ | `castro://subscribe/` | [Q100576609](https://www.wikidata.org/wiki/Q100576609) |
| Downcast | $2.99 one-time³² | Mac (separate) | 🚫 | 🚫 | ✅💲 | `downcast://` | [Q39072639](https://www.wikidata.org/wiki/Q39072639) |
| iCatcher! | $4.99 one-time³³ | iOS / watchOS | 🚫 | 🚫 | ✅ | `icatcher://` | — |
| Pocket Casts | $39.99/yr Plus, $99.99/yr Patron³⁴ | iOS / Android / Web / Mac / Windows / Wear / CarPlay³⁵ | ✅💲³⁶ | ✅ | ✅ | `pktc://subscribe/...` | [Q99620573](https://www.wikidata.org/wiki/Q99620573) |
| Procast | Free, optional tip IAPs | iOS / Android | 🚫 | ✅ (cuts) |  |  | — |
| Apple Podcasts | Free (Apple Podcasts Subscriptions sold per show) | macOS / iOS / iPadOS / web⁴⁷ | ✅³⁷ | ✅³⁸ | ✅ | `pcast://` | [Q70058728](https://www.wikidata.org/wiki/Q70058728) |
| RSSRadio | Free + $17.99/yr Premium IAP³⁹ | iOS / Apple Watch | 🚫 |  | ✅ | `rssradio://` | — |
| Player FM | $39.99/yr Premium⁴⁰ | iOS / Android / Web / Apple Watch / CarPlay | ⚠️⁴¹ |  |  |  | [Q88271444](https://www.wikidata.org/wiki/Q88271444) |
| Snipd | $6.99/mo on annual plan ($83.88/yr)⁴² | iOS / Android | ✅ (AI) | ✅ |  |  | — |
| Castbox | $34.99/yr Premium, $49.99/yr Pro⁴³ | iOS / Android / Web / CarPlay / Alexa | ⚠️ (in-audio search) | ✅ |  |  | [Q60852314](https://www.wikidata.org/wiki/Q60852314) |
| Spotify | Free, ad-supported; Premium $12.99/mo (US, Feb 2026)⁴⁴ | iOS / Android / Web / Mac / Windows / Cars / TVs / Smart speakers | ✅ (AI) | ✅ | ⚠️ |  | [Q689141](https://www.wikidata.org/wiki/Q689141) |
| Fountain | Free; Premium £2.99/mo⁴⁵ | iOS / Android / Mac (M1+) | ✅ | ✅ |  |  | — |
| Podverse | Free; Premium $18/yr⁴⁶ | iOS / Android / F-Droid / Web | ✅ | ✅ (any length) | ✅ |  | — |

29. Overcast Premium increased from $9.99/yr to $14.99/yr on November 21, 2024 — first price change in eight years (Marco Arment, Mastodon; Podcast News Daily).
30. Overcast transcripts shipped in version 2026.4 (April 8, 2026), powered by Marco Arment's rack of 48 Mac minis (AppleInsider, "A rack of 48 Mac minis now powers Overcast's podcast transcripts," April 7, 2026; 9to5Mac; MJTsai blog). Arment told *Curb Cuts* (April 10, 2026): "The breakthrough that finally made [transcripts] feasible at my scale was the new Apple speech-recognition API in the 26-series OSes last year."
31. Castro Plus is $29.99/yr under Bluck Apps ownership (TechCrunch, January 31, 2024).
32. Downcast: one-time $2.99 paid app, plus optional tip IAPs ($2.99–$11.99). No subscription required.
33. iCatcher! is a $4.99 one-time purchase from Joe Graf (joeisanerd.com), with optional tip IAPs.
34. Pocket Casts Plus: $3.99/mo or $39.99/yr; Patron: $9.99/mo or $99.99/yr (Engadget, 9to5Google, March 2025).
35. The Pocket Casts web player and Mac/Windows apps became free for all users in March 2025 (9to5Google, Engadget).
36. Pocket Casts auto-generated transcripts are a Plus/Patron feature (official site).
37. Apple Podcasts auto-transcripts launched iOS 17.4 (March 2024, four languages); back-catalog and 13-language coverage announced for late 2025 by Apple Newsroom and Podcastvideos.com.
38. Apple Podcasts clip sharing arrived in iOS 18 with timestamped link sharing.
39. RSSRadio in-app purchases listed on the App Store id386600664 include "Podcast Player – Annual USD 17.99" and one-time upgrades.
40. Player FM Premium annual is $39.99 on the App Store; there is also a "Pro" tier and an occasional StackSocial lifetime deal.
41. Player FM's support docs mention "Accessibility Mode and Transcript Feature," but transcript coverage is limited.
42. Snipd Premium: $6.99/month when billed annually = $83.88/year exactly (snipd.com/pricing, "Premium Plan… $6.99/month… Includes 1 week free trial"). Monthly-only billing is $9.99/mo. Early adopters were grandfathered at ~£3.50/mo.
43. Castbox Premium IAPs on the App Store (id1243410543): Castbox Premium Yearly $34.99; Pro Yearly $49.99; 3-Month $9.99; promo $0.99.
44. Spotify raised US Premium Individual pricing from $11.99 to $12.99/mo starting February 2026 (Spotify Newsroom, Jan 15, 2026: "Occasional updates to pricing across our markets reflect the value that Spotify delivers"; CNBC, Jan 15, 2026: "The monthly price will go from $11.99 to $12.99 starting in February").
45. Fountain Premium is £2.99/month per support.fountain.fm/article/11-premium (last updated April 18, 2024: "Subscribe to Fountain Premium for just £2.99 a month to unlock a growing list of features"); no annual plan published.
46. Podverse Premium is $18/year after a 3-month free trial (podverse.fm/membership).
47. Apple Podcasts web player launched in April 2019 (9to5Mac, *Apple launches web version of Apple Podcasts ahead of standalone Mac app*, April 9, 2019; MacStories).

## Acronyms

- **Chap.** = Chapter
- **Ctrl.** = Controls
- **DL** = Download
- **Ep.** = Episode
- **PL** = Playlist
- **Sub.** = Subscription
- **V4V** = Value-for-Value (Bitcoin/Lightning podcasting micropayments)

## Articles and Reviews

Sources used to compile this update (2024–2026):

- 9to5Mac — *Overcast launches podcast transcripts in new app update for iPhone* (April 8, 2026)
- 9to5Mac — *iOS 26.2's new Apple Podcasts feature makes the app very hard to resist* (Nov 6, 2025)
- 9to5Google — *Pocket Casts web, Mac, and Windows apps are now free to access* (March 11, 2025)
- AppleInsider — *Giant Mac mini cluster powers Overcast podcast transcripts without the cloud* (April 7, 2026)
- Apple Newsroom — *Apple introduces transcripts for Apple Podcasts* (March 2024)
- Apple Podcasters Support — *Enhance your episodes with chapters, links, and more* (Nov 2025)
- BGR — *Ranking 10 Major Podcast Apps From Worst To Best* (2025)
- CNBC — *Spotify hikes Premium prices in the US* (Jan 15, 2026)
- Engadget — *Pocket Casts makes its web player and desktop apps usable without a subscription* (March 2025)
- MacRumors — *iOS 26.2 Adds Three New Features to Podcasts App* (Nov 4, 2025)
- MJTsai blog — *Overcast Transcripts* (March 20, 2026)
- Podcast News Daily / Inside Radio — *Overcast Has First Price Hike In Eight Years* (Nov 2024)
- Podnews — *How do Apple Podcasts Transcripts work?* and *New Overcast beta adds full transcripts*
- Spotify Newsroom — *Update on Spotify Premium pricing* (Jan 15, 2026)
- TechCrunch — *Podcast app Castro now owned by indie developer Bluck Apps* (Jan 31, 2024)
- TechCrunch — *RIP? Third-party podcast app Castro appears to be dead* (Jan 8, 2024)
- TechCrunch — *Twitter acquires social podcasting app Breaker* (Jan 4, 2021)
- Transistor.fm — *Most Popular Podcast Apps for iOS and Android (2026)*
- TWiT.tv — *Which Podcast App Should You Use on iOS?* (iOS Today ep. 773, Oct 2025)
- Whop — *Top 20 best podcast apps for audio lovers in 2026*
- Latent Space — *Building Snipd: The AI Podcast App for Learning* (interview with Snipd founder Kevin)
- Make Headway — *Snipd Pricing & Features: Is the Premium AI Subscription Worth It?*
- Pocket Casts Support — *Pocket Casts Plus Pricing*
- Castro Blog — *A Fresh Start Under New Ownership* (Jan 31, 2024)
- Fountain Support — *Premium* (article 11, last updated April 18, 2024)
- Official App Store listings for each app (current versions, May 2026)
- Official websites: [overcast.fm](https://overcast.fm), [castro.fm](https://castro.fm), [downcastapp.com](https://downcastapp.com), [joeisanerd.com](https://joeisanerd.com), [pocketcasts.com](https://pocketcasts.com), [rssrad.io](https://rssrad.io), [player.fm](https://player.fm), [snipd.com](https://snipd.com), [castbox.fm](https://castbox.fm), [fountain.fm](https://fountain.fm), [podverse.fm](https://podverse.fm)
- This document started as a copy of [Podlove's Matrix](https://docs.google.com/spreadsheets/d/1c2L14UVH1xtN4iDG4awheLbMgPCQgaKEamUauWs1gps/edit) (now outdated).

## Appendix: Discontinued Apps

### Breaker (2016–2021) — Acquired by Twitter, Shut Down

Breaker was a social-first iOS podcast app founded in 2016 by Erik Berlin and Leah Culver. On **January 4, 2021**, Twitter announced it had acquired Breaker's team to build out Twitter Spaces; the Breaker app and website **shut down on January 15, 2021**. Users were given a brief window to export OPML files (TechCrunch, *Twitter acquires social podcasting app Breaker*, Jan 4, 2021; Tubefilter, Jan 5, 2021).

Breaker's brand and remaining technical assets were subsequently picked up by Los Angeles–based **Maple Media**, which folded them into a podcast-discovery-and-promotion network alongside its other acquired podcast apps Player FM and Podkicker (dot.LA, *Breaker Social Podcast App Is Acquired by LA's Maple Media*). The original Breaker iOS app has not returned.

**Status:** Discontinued. Use Apple Podcasts, Pocket Casts, Overcast or Castro as a recommended replacement (per Breaker's own farewell post).

### Procast — Still on the App Store, Limited Maintenance

Procast (Podflitzer GmbH, Munich) is technically still available on the App Store and Google Play and received minor updates in 2024, but it has been largely ignored by mainstream press since 2018, has very limited feature parity with current top-tier players, and the developer has explicitly described it as a passion project maintained "in our spare time" (podcast-app.de/support).

It is retained in the main comparison table for historical continuity but most feature rows are intentionally sparse, reflecting the lack of recent third-party reviews. **Status:** Active but minimally maintained — verify availability before recommending.