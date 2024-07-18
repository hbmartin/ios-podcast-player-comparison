# iOS Podcast Player / Client Comparison

🔔 Note: as of July 17, 2024, this is simply copied over from [Podlove's Matrix](https://docs.google.com/spreadsheets/d/1c2L14UVH1xtN4iDG4awheLbMgPCQgaKEamUauWs1gps/edit?gid=0#gid=0) and may be outdated.

Work is ongoing to update this document, you are welcome to help edit this!

See the [articles](#articles-and-references) section for links to descriptions and screenshots.

* [Chapters and Notes](#chapters-and-notes)
* [Playback and Playlists](#playback-and-playlists)
* [File Formats, Devices, and Subscriptions](#file-formats-devices-and-subscriptions)
* [Controls and Downloads](#controls-and-downloads)
* [Sync and Import / Export](#sync-and-import--export)
* [Other](#other)

✅ = supported

🚫 = not supported

⚠️ = partial support

## Chapters and Notes

|                  | Paged Feeds | Chap. Mark | MP3 Chap. Mark | Auto Chap. | Chap. Dura-tion | Chap. Start Time | Chap. End Time | Chap. Pics | Notes for DL'd | Notes w/o DL |
| ---------------- | ----------- | ---------- | -------------- | ---------- | --------------- | ---------------- | -------------- | ---------- | -------------- | ------------ |
| Overcast         |             | ✅          | ✅              | 🚫          |                 |                  |                | ✅          | ✅              |              |
| Castro           |             | ✅          | ✅              | 🚫          | ✅               |                  |                | ✅          | ✅              | ✅            |
| Downcast         | 🚫           | ✅          | ✅              | 🚫          | ✅               | ✅                | 🚫              | ✅          | ✅              | ✅            |
| iCatcher!        |             | ✅          | ✅              | 🚫          | ✅               | ✅                | 🚫              |            | ✅              | ✅            |
| Pocket Casts     | ✅           | ✅          | 🚫              |            | ✅               | 🚫                | 🚫              | ✅          | ✅              | ✅            |
| Procast          |             |            |                |            |                 |                  |                |            |                |              |
| Pod Wrangler     |             |            |                |            |                 |                  |                |            |                |              |
| Apple Podcasts   |             | ⚠️          | 🚫              | 🚫          | 🚫               | 🚫                | 🚫              | ✅          | ✅              | 🚫            |
| RSSRadio Premium |             | ✅          |                | 🚫          | 🚫               | ✅                | 🚫              | ✅          | ✅              | ✅            |
| Podcaster 7      |             | ✅          | 🚫              |            | ✅               | 🚫                | 🚫              |            | ✅              |              |
| SleekCast        | ✅           | ✅          | ✅              | 🚫          | 🚫               | 🚫                | 🚫              | ✅          | ✅              | ✅            |
| Mocast           |             |            |                |            |                 |                  |                |            |                |              |
| Podcat           |             | ✅          | ✅              |            |                 |                  |                |            |                |              |
| Instacast        | ✅           | ✅          | ✅              | ✅          | ✅               | 🚫                | 🚫              | ✅          | ✅              | ✅            |
| Podcatchr        |             | ✅          | 🚫              | ✅          | ✅               | ✅                | ✅              | ✅          | ✅              | ✅            |

## Playback and Playlists

|                  | Sleep Timer | Radio Mode | Play Speed | Gap-less Play | Vol. Boost | Book marks | Personal Playlist | Personal Smart Playlist | Predef. Smart Playlist |
| ---------------- | ----------- | ---------- | ---------- | ------------- | ---------- | ---------- | ----------------- | ----------------------- | ---------------------- |
| Overcast         | ✅           | 🚫          | ✅          | ✅             | ✅          |            | ✅                 | ✅                       |               |
| Castro           | ✅           | 🚫          | ✅          | ✅             | ✅          | 🚫          | ✅                 | ✅                       | ✅           |
| Downcast         | ✅           | 🚫          | ✅          | 🚫             | ✅          | 🚫          | ✅                 | ✅                       | ✅           |
| iCatcher!        | ✅           | 🚫          | ✅          |               | 🚫          | ✅          | ✅                 | ✅                       | ✅            |
| Pocket Casts     | ✅           | 🚫          | ✅          | ✅             | 🚫          | 🚫          | ✅                 | ✅                       | ✅           |
| Procast          |             |            |            |               |            |            |                   |                         |                        |
| Pod Wrangler     |             |            |            |               |            |            |                   |                         |                        |
| Apple Podcasts   | ✅           |            | ✅          |               | 🚫          | 🚫          | ✅                 | ⚠️                       | ✅             |
| RSSRadio Premium | 🚫           | 🚫          | ✅          |               | ✅          | ✅          | ✅                 | 🚫                       | ✅            |
| Podcaster 7      | ✅           |            | ✅          |               | 🚫          | 🚫          | ✅                 | ✅                       | ✅             |
| SleekCast        | ✅           | 🚫          | ✅          |               | 🚫          | ✅          | ✅                 | ✅                       | 🚫            |
| Mocast           |             |            |            |               |            |            |                   |                         |                        |
| Podcat           |             |            |            |               |            |            |                   |                         |                        |
| Instacast        | ✅           | 🚫          | ✅          | ✅             | 🚫          | ✅          | ✅                 | 🚫                       | ✅           |
| Podcatchr        | ✅           | 🚫          | ✅          | ✅             | 🚫          | ✅          | ✅                 | 🚫                       | ✅           |

## File Formats, Devices, and Subscriptions

|                  | Opus | AirPlay | Audio Scrub. | iPad | Land-scape | Inline Browser | Push new eps. | Custom Sub. Sort | Alpha. Sub. Sort | Ext-ended Video |
| ---------------- | ---- | ------- | ------------ | ---- | ---------- | -------------- | ------------- | ---------------- | ---------------- | --------------- |
| Overcast         |      | ✅       |              | 🚫    |            |                | ✅             |                  |              |                |
| Castro           | 🚫    | ✅       |              | 🚫    |            | ✅              | ✅             | 🚫                | ✅       | 🚫               |
| Downcast         | 🚫    | ✅       |              | ✅    | ✅          | ✅              | ✅             | ✅                | ✅      | ✅               |
| iCatcher!        | 🚫    | ✅       |              | ✅    | ✅          | ✅              | 🚫             | ✅                | ✅      | ✅               |
| Pocket Casts     | 🚫    | ✅       | 🚫            | ✅    | ✅          | ✅              | ✅             | ✅                | ✅     | ✅               |
| Procast          |      |         |              |      |            |                |               |                  |                  |                 |
| Pod Wrangler     |      |         |              |      |            |                |               |                  |                  |                 |
| Apple Podcasts   | 🚫    | ✅       |              | ✅    | 🚫          | 🚫              | 🚫             | ✅                | 🚫      |✅               |
| RSSRadio Premium | 🚫    | ✅       | ✅            | ✅    | ✅          | ✅              | ✅             | 🚫                | ✅     | ✅               |
| Podcaster 7      | 🚫    | ✅       |              |      | ✅          | ✅              |               |                  | ✅          |✅               |
| SleekCast        | 🚫    | ✅       | ✅            | 🚫    | ✅          | ✅              | ✅             | ✅                | 🚫     | ✅               |
| Mocast           |      |         |              |      |            |                |               |                  |                  |                 |
| Podcat           |      |         |              |      |            |                |               |                  |                  |                 |
| Instacast        | 🚫    | ✅       | ✅            | ✅    | ⚠️          | ✅              | ✅             | ✅                | ⚠️     | ✅               |
| Podcatchr        | 🚫    | ✅       | ✅            | 🚫    | ✅          | ✅              | ✅             | ✅                | ✅     | ✅               |

## Controls and Downloads

|                  | Touch Controls | OS Play Controls | Skip Intro | Play DL'ing Ep. | Parallel DL's | Episode stream | Pass. pro-tected | Auto. DL Opts | Disk Space Mgmt |
| ---------------- | -------------- | ---------------- | ---------- | --------------- | ------------- | -------------- | ---------------- | ------------- | --------------- |
| Overcast         |                | ✅                |            |                 |               |                |                  |               |                |
| Castro           | ✅              | ✅                |            | ✅               | ✅             | ✅              |                  | ✅             | ✅        |
| Downcast         | ✅              | ✅                | ✅          | ✅               | ✅             | ✅              | ✅                | ✅             | ⚠️     |
| iCatcher!        | ✅              | ✅                | ✅          | ✅               | ✅             | ✅              | ✅                | ✅             | ⚠️     |
| Pocket Casts     | ✅              | ✅                | ✅          | ✅               | ✅             | ✅              | 🚫                | ✅             | ✅     |
| Procast          |                |                  |            |                 |               |                |                  |               |                 |
| Pod Wrangler     |                |                  |            |                 |               |                |                  |               |                 |
| Apple Podcasts   | ✅              |                  |            | ✅               | ✅             | ✅              | 🚫                | ✅             | 🚫        |
| RSSRadio Premium | ✅              | ✅                | ✅          | 🚫               | ✅             | ✅              | ✅                | ✅             | 🚫     |
| Podcaster 7      | ✅              |                  |            | ✅               | 🚫             | ✅              |                  | ✅             | 🚫         |
| SleekCast        | ✅              | ✅                | ✅          | ✅               | ✅             | ✅              | 🚫                | ✅             | ✅     |
| Mocast           |                |                  |            |                 |               |                |                  |               |                 |
| Podcat           |                |                  |            |                 |               |                |                  |               |                 |
| Instacast        | ✅              | ✅                | 🚫          | 🚫               | ✅             | ✅              | ✅                | ✅             | ✅     |
| Podcatchr        | ✅              | ✅                | 🚫          | ✅               | ✅             | ✅              | 🚫                | ✅             | ✅     |

## Sync and Import / Export

|                  | Cross Device Sync | Sync Tech. | Import Music Lib. | OPML Export | OPML Import | Pod-cast Dir. | Atom Feed |
| ---------------- | ----------------- | ---------- | ----------------- | ----------- | ----------- | ------------- | --------- |
| Overcast         |                   |            |                   |             |             |               |           |
| Castro           | 🚫                 |            |                   | ✅           | ✅           | ✅        |           |
| Downcast         | ✅                 | iCloud     | ✅                 | ✅           | ✅           | ✅        | ✅         |
| iCatcher!        | ✅                 | iCloud     |                   | ✅           | ✅           | ✅         |           |
| Pocket Casts     | ✅                 | Prop.      | ✅                 | ✅           | ✅           | ✅        | 🚫         |
| Procast          |                   |            |                   |             |             |               |           |
| Pod Wrangler     |                   |            |                   |             |             |               |           |
| Apple Podcasts   | ✅                 | iCloud     | ✅                 | 🚫           | 🚫           | ✅       |           |
| RSSRadio Premium | ✅                 | iCloud     | ✅                 | ✅           | ✅           | ✅        |           |
| Podcaster 7      |                   |            | 🚫                 | ✅           | ✅           | ✅        |           |
| SleekCast        | ✅                 | Prop.      | 🚫                 | ✅           | ✅           | ✅        | 🚫         |
| Mocast           |                   |            |                   |             |             |               |           |
| Podcat           |                   |            |                   |             |             |               |           |
| Instacast        | ✅                 | Prop.      | ✅                 | ✅           | ✅           | ✅        | ✅         |
| Podcatchr        | ✅                 | Prop.      | 🚫                 | ✅           | ✅           | ✅        | ✅         |

## Other

|                  | Price     | Social Share | Per Podcast Settings | Add Ep. to Playlist w/o sub. | App subscription URI scheme            | Wikidata ID                                            |
| ---------------- | --------- | ------------ | -------------------- | ---------------------------- | -------------------------------------- | ------------------------------------------------------ |
| Overcast         | $10 /yr   |              |                      |                              | overcast://x-callback-url/add?url=     | [Q20707973](https://www.wikidata.org/wiki/Q20707973)   |
| Castro           | $25 /yr   | ✅            | ✅                    | ✅                            | castro://subscribe/                    | [Q100576609](https://www.wikidata.org/wiki/Q100576609) |
| Downcast         |           | ✅            | ✅                    | ✅                            | downcast://                            |                                                        |
| iCatcher!        |           | ✅            | ✅                    |                              | icatcher://                            |                                                        |
| Pocket Casts     | $40 /yr ¹ | ✅            | ✅                    | 🚫                            | pktc://subscribe/feed-url-without-http |                                                        |
| Procast          |           |              |                      |                              |                                        |                                                        |
| Pod Wrangler     |           |              |                      |                              |                                        |                                                        |
| Apple Podcasts   |           | ⚠️            | ✅                    | ✅                            | pcast://                               | [Q70058728](https://www.wikidata.org/wiki/Q70058728)   |
| RSSRadio Premium |           | ✅            | ✅                    | ⚠️                            | rssradio://                            |                                                        |
| Podcaster 7      |           | ✅            | ✅                    |                              | ?                                      |                                                        |
| SleekCast        |           | ✅            | ✅                    | 🚫                            |                                        |                                                        |
| Mocast           |           |              |                      |                              |                                        |                                                        |
| Podcat           |           |              |                      |                              | podcat://                              |                                                        |
| Instacast        |           | ✅            | ✅                    | 🚫                            | instacast://                           |                                                        |
| Podcatchr        |           | ✅            | ✅                    | 🚫                            |                                        |                                                        |

1. 50% off first year

## Acronyms

* Chap = Chapter
* DL = Download
* PL = Playlist
* Ep = Episode

## Articles and References

* https://amplify.matchmaker.fm/what-is-the-best-podcast-app/
* https://www.pcmag.com/picks/the-best-podcast-player-apps
* https://www.descript.com/blog/article/best-podcast-app
* https://www.lifewire.com/best-podcast-apps-ios-4169824
