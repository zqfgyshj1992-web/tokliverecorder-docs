# Limits and file storage

This page lists what Tok Live Recorder can't do and how long files are kept, so you can decide whether it fits before a LIVE that matters.

## Free trial

| Item | Free trial |
|---|---|
| Sign-in | Required (Google or email), no card |
| Recordings per day | 3 (counter resets at midnight UTC) |
| Length per recording | Up to 30 minutes |
| Recordings at the same time | 1 |
| Auto-record when a creator goes live | Not included |
| Quality | Original stream quality, no watermark |
| Cloud file retention | 7 days |

A recording only counts once it actually starts capturing a LIVE. If a creator turns out to be offline or the link can't be recorded, it doesn't use your allowance. A LIVE that runs past the length limit doesn't fail: the recording stops cleanly at the limit and the MP4 stays valid.

## What it can't record

- **Ended LIVEs.** There is nothing left to capture once a broadcast ends.
- **Private or subscriber-only LIVEs.** Only publicly reachable streams can be recorded; the service does not try to get around access restrictions.
- **The part before you started.** Every recording begins at the moment you start it.
- **Your screen.** On-screen comments and reactions you see while watching are not in the file.

## File storage

- Cloud recordings sit in private storage that only your account can open.
- They are deleted automatically after **7 days**. Download the MP4 within that window; once downloaded, the file is yours with no expiry and no DRM.
- The desktop apps save recordings to your own computer instead of the cloud.

## Comparison with other ways to keep a LIVE

| Method | Device busy while recording? | Comments in the file? | Main limit |
|---|---|---|---|
| TikTok host replay | No | No | Host only, 30 days |
| Phone screen recording | Yes, the whole LIVE | Yes | Phone must stay on the LIVE |
| OBS Studio | Yes, the computer | Depends on capture area | Setup and testing needed |
| tiktok-live-recorder (open source) | Yes, the computer running it | No | Python 3.11+, FFmpeg, terminal |
| Tok Live Recorder | No (cloud) | No | Free trial: 30 min each, 3 a day; files kept 7 days |

Sources for the other methods: [TikTok Support](https://www.tiktok.com/support/faq_detail?id=7543897462214269496), [OBS quick start](https://obsproject.com/kb/quick-start-guide), [tiktok-live-recorder README](https://github.com/Michele0303/tiktok-live-recorder).
