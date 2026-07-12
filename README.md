# iOS Podcast Player App Comparison

*Last updated: July 2026*

🔔 **Major changes since the last revision:**

- New **[AI Features](#ai-features)** table comparing auto-generated transcripts, transcript search, AI chapters, summaries, highlights, in-episode chat, AI discovery, and translation across every app.
- **Podurama**, **Superphonic**, **Metacast**, and **Castamatic** added to the comparison. **Aisten** and **Neuecast** were evaluated but not added — see the [appendix](#appendix-apps-evaluated-but-not-added).
- **Pocket Casts** launched AI-generated chapters (July 2026 — Android/web/desktop first, iOS "coming very soon") and word-level highlighted transcripts (June 2026).
- **Spotify** added Premium AI Q&A for podcasts, AI-generated "Personal Podcasts" briefings, and prompted playlists for podcasts (May 2026); its 2023 voice-translation pilot appears dormant.
- **Snipd** shipped "Chat with Episodes" (November 2024) and an AI DJ highlights feed (2026).
- **Correction:** Castro (since February 2025) and iCatcher! display creator-provided Podcasting 2.0 transcripts — both were previously listed as having no transcript support. Neither generates transcripts.
- Castro's team also launched **Pod Seek** (March 2026), a separate AI podcast Q&A companion app built on Apple's foundation models.

Please help keep this updated by [leaving a comment](https://github.com/hbmartin/ios-podcast-player-comparison/issues) or by [editing this doc](https://github.com/hbmartin/ios-podcast-player-comparison/edit/main/README.md)!

## Contents

- [Chapters and Notes](#chapters-and-notes)
- [Playback and Playlists](#playback-and-playlists)
- [File Formats, Devices, and Subscriptions](#file-formats-devices-and-subscriptions)
- [Controls and Downloads](#controls-and-downloads)
- [Sync and Import / Export](#sync-and-import--export)
- [Other](#other)
- [AI Features](#ai-features)
- [Acronyms](#acronyms)
- [Articles and Reviews](#articles-and-reviews)
- [Appendix: Discontinued Apps](#appendix-discontinued-apps)
- [Appendix: Apps Evaluated but Not Added](#appendix-apps-evaluated-but-not-added)

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
| Podurama | ✅💲⁷¹ |  |  |  |  |  |  | ✅ | ✅ |
| Superphonic | ✅⁷² |  |  |  |  |  |  | ✅ | ✅ |
| Metacast | ✅⁷³ |  |  |  |  |  |  | ✅ | ✅ |
| Castamatic | ✅⁷⁵ | ✅ | ⚠️⁷⁶ |  | ✅ |  | ✅ | ✅ | ✅ |

1. Overcast added chapter art and richer chapter handling alongside transcripts in the 2026.x line.
2. Castro Plus required for chapter selection / playback enhancements.
3. Downcast: "Chapters support for enhanced podcasts" (App Store listing).
4. iCatcher!: "Support for podcasts with chapters and chapter images (MP3 and M4A)" (App Store listing).
5. Pocket Casts Plus required for Chapter Preselection (per 9to5Google, March 2025).
6. With iOS 26.2, Apple Podcasts auto-generates chapters when creators do not provide them; per-chapter images supported when creators submit them.
7. Snipd generates AI chapters when creators do not provide them.
8. Spotify supports creator-supplied chapters on Spotify-exclusive shows; partial support for MP3-tag chapters on RSS shows. Since September 2025 it also auto-generates chapters for English episodes without creator chapters (Spotify for Creators).
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
| Podurama |  | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |  |
| Superphonic | ✅ |  | ✅⁵² |  |  | ⚠️⁵² |  |  |
| Metacast | ✅ | 🚫 | ✅ |  | ✅ | ✅💲 | 🚫 | ✅ |
| Castamatic | ✅ | ✅ | ✅ | ✅ |  | ✅ | ✅ |  |

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
| Podurama |  | ✅ | ⚠️ | ✅ |  | ✅ |  |  | ✅ |
| Superphonic |  | ✅ | ✅ | ✅ |  | ✅ |  |  |  |
| Metacast |  | ⚠️⁷⁴ |  | 🚫 |  | 🚫⁷⁴ |  |  |  |
| Castamatic | ✅ | ✅ | ✅ | ✅ |  | ✅⁷⁶ |  |  |  |

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
| Podurama | ✅ |  |  |  |  | ✅ |  | ✅ | ⚠️ |
| Superphonic | ✅ |  |  |  |  | ✅ |  |  |  |
| Metacast | ✅ |  |  |  |  | ✅ | ✅💲 |  |  |
| Castamatic | ✅ | ✅ | ✅ |  |  | ✅ | ✅ | ✅ | ✅ |

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
| Podurama | ✅ | Proprietary |  |  | ✅ | ✅⁵⁰ |  |
| Superphonic | ✅ |  |  |  |  | ✅ |  |
| Metacast | ✅ | Proprietary |  | 🚫 | ⚠️⁷⁴ | ✅ |  |
| Castamatic | ✅ | iCloud | ⚠️ | ✅ | ✅ | ✅⁷⁶ |  |

26. Bluck Apps stated in January 2024 that cross-device sync is on the post-stabilization roadmap; full sync is still partial/in development as of recent releases.
27. Fountain OPML import has been reported as flaky by users (Apple App Store reviews).
28. Podverse exposes the open Podcast Index directly.

## Other

|  | Price (annual) | Multi-Platform | Transcripts | Clip Share | Per-Podcast Settings | Subscribe URL Scheme | Wikidata ID |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Overcast | $14.99/yr Premium²⁹ | Web (login) | ✅³⁰ | ✅ | ✅ | `overcast://x-callback-url/add?url=` | [Q20707973](https://www.wikidata.org/wiki/Q20707973) |
| Castro | $29.99/yr Plus³¹ | iOS only | ⚠️⁴⁸ | ✅ | ✅ | `castro://subscribe/` | [Q100576609](https://www.wikidata.org/wiki/Q100576609) |
| Downcast | $2.99 one-time³² | Mac (separate) | 🚫 | 🚫 | ✅💲 | `downcast://` | [Q39072639](https://www.wikidata.org/wiki/Q39072639) |
| iCatcher! | $4.99 one-time³³ | iOS / watchOS | ⚠️⁴⁹ | 🚫 | ✅ | `icatcher://` | — |
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
| Podurama | $49.99 one-time Premium⁵⁰ | iOS / Android / Web / Windows / macOS | ⚠️⁵¹ |  |  |  | — |
| Superphonic | Free + $3.99/mo Premium⁵² | iOS / macOS (M1+) / visionOS | ✅ (AI)⁵² |  | ✅ |  | — |
| Metacast | $19.99/yr or $1.99/mo Premium⁷³ | iOS / Android / Web (read-only) | ✅💲⁷³ | ⚠️⁷⁴ |  |  | — |
| Castamatic | Free + $14.99/yr Premium⁷⁶ | iOS / watchOS / CarPlay / macOS (M1+) | ✅ (AI)⁷⁵ | 🚫 | ✅ | `castamatic://` | — |

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
48. Castro has displayed creator-provided transcripts (Podcasting 2.0 `podcast:transcript` tag — JSON, SRT, VTT, HTML) since February 2025, but does not generate them; transcript search and audio-text sync are listed as in progress (castro.fm blog, *Transcript Tag Support*).
49. iCatcher! auto-downloads and displays Podcasting 2.0 creator-provided transcripts and chapter files (App Store release notes); it does not generate transcripts.
50. Podurama (Podurama Ltd, UK) Premium is a one-time lifetime purchase — $49.99 on the official site, regularly discounted to $39.99 in deal shops — unlocking AI summaries, auto-generated chapters, and 10 GB of private audio/video uploads; playback, cross-device sync, and playlists are free. Its podcast directory appears to use the Apple Podcasts API (Podnews).
51. Podurama shows subtitles on most video podcasts, but in-app transcripts for audio episodes are not yet available (the official FAQ lists them as planned); a separate "Transcript AI" web tool targets creators rather than listeners.
52. Superphonic (solo-built by ex-Meta/OpenAI engineer Philip Su) meters AI features on the free tier — the first few minutes of each transcript and the first five chapters per episode — with unlimited via Premium ($3.99/mo, no annual plan). Playback speed runs to 5× in 0.1× steps with per-podcast speed overrides; the queue is a single reorderable playlist with Inbox/Later triage lists rather than named playlists (docs.superphonic.fm).

## AI Features

In the *AI Transcripts* and *AI Chapters* columns, ✅ means the app generates them itself; ⚠️ means it only displays creator-provided ones (or, for Castbox, that the claim is uncorroborated — see notes).

|  | AI Transcripts | Transcript Search | AI Chapters | AI Summaries | AI Highlights | Ask AI / Chat | AI Discovery | AI Translation |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Overcast | ✅⁵³ | 🚫⁵⁴ | 🚫⁵⁴ | 🚫⁵⁴ | 🚫 | 🚫 | 🚫 | 🚫 |
| Castro | ⚠️⁴⁸ | 🚫 | 🚫 | 🚫 | 🚫 | 🚫⁵⁵ | 🚫 | 🚫 |
| Downcast | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 |
| iCatcher! | ⚠️⁴⁹ | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 |
| Pocket Casts | ✅💲⁵⁶ | ✅ | ⚠️⁵⁷ | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 |
| Procast | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 |
| Apple Podcasts | ✅⁵⁸ | ✅ | ✅⁵⁹ | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 |
| RSSRadio | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 |
| Player FM | ⚠️⁴¹ | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 |
| Snipd | ✅⁶⁰ | ✅ | ✅⁶⁰ | ✅⁶⁰ | ✅⁶¹ | ✅💲⁶¹ | ✅⁶² | ⚠️⁶² |
| Castbox | ⚠️⁶³ |  | ⚠️⁶³ | ⚠️⁶³ | 🚫 | 🚫 | ✅⁶⁴ | 🚫 |
| Spotify | ✅⁶⁵ | 🚫 | ✅⁶⁵ | 🚫 | 🚫 | ✅💲⁶⁶ | ✅⁶⁶ | ⚠️⁶⁷ |
| Fountain | ✅💲⁶⁸ | ✅ | 🚫 | ✅💲⁶⁹ | 🚫 | 🚫 | 🚫 | 🚫 |
| Podverse | ⚠️⁷⁰ |  | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 |
| Podurama | ⚠️⁵¹ | 🚫 | ✅💲⁷¹ | ✅💲⁷¹ | ✅⁷¹ | ⚠️⁷¹ | ✅⁷¹ | 🚫 |
| Superphonic | ✅⁷² |  | ✅⁷² | 🚫 | 🚫 | 🚫 |  | 🚫 |
| Metacast | ✅💲⁷³ | ✅ | ✅💲⁷³ | ✅💲⁷³ | 🚫 | 🚫⁷³ | 🚫 | 🚫 |
| Castamatic | ✅⁷⁵ | ✅ | ✅⁷⁵ | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 |

53. Overcast transcripts are free for all users since v2026.4 (April 2026), generated with Apple's 26-series speech APIs on Marco Arment's 48-Mac-mini cluster (on-device on iOS 26 for private feeds; creator-provided VTT transcripts are also ingested). An audio-fingerprinting step re-syncs transcripts when dynamic ad insertion shifts the audio (AppleInsider; 9to5Mac, April 2026).
54. Arment has named transcript search, automatic chapters, and AI summaries as potential next steps built on transcripts, but none had shipped as of July 2026 (AppleInsider; Podnews).
55. Bluck Apps promised "We're not adding an AI chatbot" when it acquired Castro (castro.fm, February 2024). AI episode Q&A instead ships in the separate companion app **Pod Seek** (March 2026, built on Apple's foundation models), which syncs with Castro. Castro also blocks AI-generated "slop" networks from its search results (castro.fm, December 2025).
56. Pocket Casts generates transcripts server-side for Plus/Patron subscribers on select shows (episodes under ~2 h) since April 2025; creator-provided transcripts display free for everyone, and transcript search works on both (Pocket Casts blog; support KB).
57. Pocket Casts AI-generated chapters launched July 7, 2026 on Android/web/desktop with iOS "coming very soon" — still pending on iOS at this revision (Pocket Casts blog).
58. Apple has generated transcripts itself since iOS 17.4 (March 2024) — 11 languages since October 2024, 125M+ back-catalog episodes — searchable within an episode (Apple Newsroom; 9to5Mac).
59. iOS 26.2 (December 2025) auto-generates chapters (labeled "Automatically created") for English episodes lacking creator chapters, with a creator opt-out, and adds "timed links" for things mentioned in-episode; iOS 26 (September 2025) added the ML-based Enhance Dialogue speech enhancement (MacRumors; Podnews; Apple Podcasts for Creators).
60. Snipd generates transcripts with speaker names in 26 languages, plus AI chapters, summaries, and key takeaways for every processed episode; the free tier caps AI processing at ~2 episodes/week (snipd.com; Snipd help center).
61. Snipd "snips" are captured via headphone triple-tap with AI transcript/summary, alongside AI-detected highlights; "Chat with Episodes" (November 2024, Premium) answers questions with quoted, timestamped citations (Snipd blog).
62. Snipd's "AI DJ" (2026) plays an AI-curated feed of episode highlights with generated narration between segments (English-only at launch); other AI extras include custom summary prompts, YouTube/audiobook import, the Snipd Wrapped year-in-review, tap-to-translate for transcript passages, and AI-note export to Notion/Readwise/Obsidian (snipd.com; founder interviews, 2026).
63. Castbox's real-time transcripts, auto-chapters, and episode summaries are claimed only in Castbox's own 2026 blog posts and are not corroborated by its release notes, help center, or third-party reviews — treat with caution (castbox.fm blog, May 2026; Transistor.fm transcript guide, 2025).
64. Castbox "in-audio search" — ML speech-indexed keyword search that jumps to the moment a word is spoken — shipped in 2018 and is still marketed, alongside ML-personalized recommendations (Castbox; App Store listing).
65. Spotify auto-generated transcripts have rolled out since 2023 (creator uploads and Podcasting 2.0 ingestion added 2025); "automatic chapters" (September 2025) are generated for English shows when creators don't supply them (Spotify for Creators; Podnews).
66. Spotify's real-time AI Q&A about the playing episode is Premium-only (US, Sweden, Ireland at launch — May 2026); Spotify also launched AI-generated "Personal Podcasts"/briefings and extended natural-language Prompted Playlists to podcasts (Spotify Newsroom; TechCrunch, May 21, 2026).
67. Spotify's September 2023 AI voice-translation pilot (OpenAI voice cloning — Lex Fridman, Steven Bartlett, et al.) never expanded beyond its pilot episodes and appears dormant (Spotify Newsroom, September 2023).
68. Fountain generates transcripts on demand via Deepgram since May 2023 — free if already unlocked by any user, ~2,000 sats (~$0.50) per audio-hour otherwise, unlimited with Premium; creator-provided transcripts also display (Fountain blog; Deepgram).
69. Fountain episode summaries arrived in v1.2 (May 2025) — 500 sats each or unlimited with Premium (Fountain blog).
70. Podverse deliberately displays only creator-provided Podcasting 2.0 transcripts and chapters; there is no AI generation anywhere in its open-source stack (podverse.fm; GitHub).
71. Podurama offers AI episode summaries and auto-generated chapters (Premium), "Trending Snippets" surfacing AI-picked top moments, and an AI chatbot for finding shows and episodes by topic — a discovery tool rather than per-episode Q&A (App Store release notes v6.4, April 2026; Cult of Mac).
72. Superphonic generates AI transcripts and chapter/topic lists for every public podcast; the free tier gets the first few minutes of each transcript and the first five chapters per episode, and Premium removes the caps (superphonic.fm; docs.superphonic.fm).
73. Metacast (founded by ex-Google/AWS PMs, launched September 2024) generates a transcript on demand for any episode — creator-provided Podcasting 2.0 transcripts are used when present (October 2025) — with within-episode transcript search and Markdown export; AI chapters (March 2025, beta) and AI summaries (May 2025) are Premium. The free tier shows roughly the first 10% of a transcript and blurs the rest; Premium dropped from $4.99 to $1.99/mo ($19.99/yr) in October 2024. Its FAQ suggests pasting transcripts into ChatGPT/Claude for Q&A rather than offering in-app chat (metacast.app blog/FAQ).
74. Metacast gaps: no dedicated CarPlay interface (now-playing metadata only), no native iPad app, and no push notifications — new episodes land in a "Podcast Inbox" with two-week expiry; OPML import is a manual, support-assisted service for Premium subscribers with no OPML export; episode sharing is transcript-text quotes with timestamped deep links rather than audio clips (metacast.app FAQ/changelog).
75. Castamatic 13 (April 2026) added on-device "Magic Transcript" (Apple's Speech framework — any downloaded episode, offline, automatic language detection) and "Magic Chapters" (a local sentence-embedding model detects topic shifts, and Apple's on-device Foundation Models write the chapter titles) — generated only when creators don't provide them, with nothing leaving the device; both are free. Its ML "Auto-Leveler" voice boost dates back to 2018 (castamatic.com blog).
76. Castamatic (indie developer Franco Solerio, since 2015) is among the most complete Podcasting 2.0 clients on iOS: Podping-based near-instant new-episode notifications, Value-for-Value boosts via Nostr Wallet Connect, live episodes, cross-app comments, and the Podcast Index as its directory. It can auto-skip chapters matching per-show keywords; Premium ($14.99/yr) only removes the house banner (castamatic.com; Podnews).

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
- Castamatic Blog — *Castamatic 13: Magic Transcript and Magic Chapters* (April 20, 2026) and *Nostr Wallet Connect* (Feb 21, 2026)
- Castro Blog — *Transcript Tag Support* (Feb 2025), *Pod Seek* (Mar 2026), and *Hiding Inception Point AI* (Dec 2025)
- Cult of Mac — *Podurama app uses AI to make podcasts better than ever* (Nov 27, 2023)
- Curb Cuts — *Transcripts, with Marco Arment* (April 10, 2026)
- Deepgram — *How Fountain delivers podcast transcripts in under 30 seconds* (customer spotlight)
- Digital Minimalist — *Neuecast is a minimalist podcast app for casual listeners* (Feb 14, 2025)
- Fountain Blog — *Fountain 0.7: Transcripts* (May 2023) and *Fountain 1.2: Episode Summaries* (May 2025)
- Geeky Gadgets — *4 New Podcast Apps You Need to Know About* (April 15, 2025)
- MacRumors — *Apple Releases iOS 26.2* (Dec 12, 2025)
- Metacast Blog — launch announcement (Sept 2024), *Episode chapters* (March 24, 2025), *v1.20: podcast summaries* (May 28, 2025), and *Creator-provided transcripts on mobile* (Oct 8, 2025)
- Pocket Casts Blog — *Generated transcripts are here* (April 29, 2025), *Highlighted Transcripts* (June 24, 2026), and *AI generated chapters are here* (July 7, 2026)
- Podnews — *New podcast apps* (directory listing for Podurama and other newcomers)
- Snipd Blog — *Chat with your episodes* (November 2024)
- Spotify Newsroom — Investor Day podcast AI features: Q&A, briefings, prompted playlists (May 21, 2026)
- Spotify for Creators — *Automated transcripts and chapters* (September 9, 2025)
- TechCrunch — *Spotify adds AI-powered Q&A and briefing generation features to podcasts* (May 21, 2026)
- Transistor.fm — *Which podcast apps support transcripts?* (2025)
- Scrum Master Toolbox Podcast — interview with Superphonic founder Philip Su (April 2026)
- Latent Space — *Building Snipd: The AI Podcast App for Learning* (interview with Snipd founder Kevin)
- Make Headway — *Snipd Pricing & Features: Is the Premium AI Subscription Worth It?*
- Pocket Casts Support — *Pocket Casts Plus Pricing*
- Castro Blog — *A Fresh Start Under New Ownership* (Jan 31, 2024)
- Fountain Support — *Premium* (article 11, last updated April 18, 2024)
- Official App Store listings for each app (current versions, May 2026)
- Official websites: [overcast.fm](https://overcast.fm), [castro.fm](https://castro.fm), [downcastapp.com](https://downcastapp.com), [joeisanerd.com](https://joeisanerd.com), [pocketcasts.com](https://pocketcasts.com), [rssrad.io](https://rssrad.io), [player.fm](https://player.fm), [snipd.com](https://snipd.com), [castbox.fm](https://castbox.fm), [fountain.fm](https://fountain.fm), [podverse.fm](https://podverse.fm), [podurama.com](https://podurama.com), [superphonic.fm](https://superphonic.fm), [metacast.app](https://metacast.app), [castamatic.com](https://castamatic.com)
- This document started as a copy of [Podlove's Matrix](https://docs.google.com/spreadsheets/d/1c2L14UVH1xtN4iDG4awheLbMgPCQgaKEamUauWs1gps/edit) (now outdated).

## Appendix: Discontinued Apps

### Breaker (2016–2021) — Acquired by Twitter, Shut Down

Breaker was a social-first iOS podcast app founded in 2016 by Erik Berlin and Leah Culver. On **January 4, 2021**, Twitter announced it had acquired Breaker's team to build out Twitter Spaces; the Breaker app and website **shut down on January 15, 2021**. Users were given a brief window to export OPML files (TechCrunch, *Twitter acquires social podcasting app Breaker*, Jan 4, 2021; Tubefilter, Jan 5, 2021).

Breaker's brand and remaining technical assets were subsequently picked up by Los Angeles–based **Maple Media**, which folded them into a podcast-discovery-and-promotion network alongside its other acquired podcast apps Player FM and Podkicker (dot.LA, *Breaker Social Podcast App Is Acquired by LA's Maple Media*). The original Breaker iOS app has not returned.

**Status:** Discontinued. Use Apple Podcasts, Pocket Casts, Overcast or Castro as a recommended replacement (per Breaker's own farewell post).

### Procast — Still on the App Store, Limited Maintenance

Procast (Podflitzer GmbH, Munich) is technically still available on the App Store and Google Play and received minor updates in 2024, but it has been largely ignored by mainstream press since 2018, has very limited feature parity with current top-tier players, and the developer has explicitly described it as a passion project maintained "in our spare time" (podcast-app.de/support).

It is retained in the main comparison table for historical continuity but most feature rows are intentionally sparse, reflecting the lack of recent third-party reviews. **Status:** Active but minimally maintained — verify availability before recommending.

## Appendix: Apps Evaluated but Not Added

Evaluated for the July 2026 revision:

### Aisten — Not Added (Transcription/Language-Learning Tool, Not a General Player)

[Aisten](https://apps.apple.com/us/app/aisten-podcast-transcription/id6453694910) (solo developer Xiang Chen / "Josscii") is an AI transcription app for language learners that happens to play podcasts: user-selectable on-device Whisper models plus cloud pre-transcription for popular shows, tap-to-define vocabulary, spaced repetition, dictation and shadowing practice, and extensive transcript translation (per-paragraph or full-episode, bring-your-own DeepL key). It ships in the App Store's *Education* category, lacks general-player table stakes (no CarPlay, no general playlists, transcription requires downloading the episode), and has essentially no podcast-press or community footprint. Actively updated through at least November 2025. Worth a look for language learners; not a fit for this comparison unless it broadens into a general player.

### Neuecast — Not Added (Deliberately Minimalist, Nothing to Compare)

[Neuecast](https://neuecast.app/) (solo developer Rishi Mody, NYC; released August 2024, v1.11 February 2026) is a genuinely nice, actively maintained minimalist player — free, ad-free, $9.99/yr Premium, ~190 US ratings averaging 4.7+ — but it deliberately omits nearly every axis this document compares: no chapters, no transcripts, no AI features, no trim silence or volume boost, no Android/web, and undocumented sync/OPML. Coverage is limited to indie blogs (Geeky Gadgets, Digital Minimalist). A defensible pick for casual listeners; revisit if its feature set grows.

### Also on the Radar

Other AI-first players surfaced during this revision, currently too new or too small for the main tables: **Podwise** (AI summaries/mind-maps, ~$8/mo), **PodSized** ("Blinkist for podcasts" with chat-with-episode), **Hypercast** (AI chapters for every episode), and **Podcatcher** (free transcription + transcript search).
