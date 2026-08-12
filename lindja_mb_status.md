# Lindja — MusicBrainz full entry status (Aug 12 2026)

## LIVE (all verified via API + live pages, Aug 12 2026)
- Artist: **Lindja (Kosovan punk/post-punk band from Pristina)** — Group, founded 1983
  - MBID: a1b9f29d-2f03-4a02-a3e4-75b30fe759b0
  - URL: https://musicbrainz.org/artist/a1b9f29d-2f03-4a02-a3e4-75b30fe759b0

- Release: **Lindja (1987-1990)** — 20 tracks, Official, Albanian, Latin script
  - MBID: 0433dcf6-0c6e-41d2-812a-b9aecc88201e
  - URL: https://musicbrainz.org/release/0433dcf6-0c6e-41d2-812a-b9aecc88201e
  - Tracklist from Albanian Oldies full-album upload (qd9G6jBStbI), stream-for-free link attached
  - Lengths entered only where measured (Besnik's listening pass): track 3 = 2:55, track 11 = 4:33
  - Annotation: sources, Java Multimedia CD (Discogs 6058028, 14 tracks) = related but different edition

- Recordings (4):
  | Recording | Take | Length | Stream | Work |
  |---|---|---|---|---|
  | cd002e68-b02e-4a98-b0af-c55b19cbd659 | Një bahshqe me lule, TVP 1985 archival take (video) | 2:50 | mJVxbu1gim0 | af48514d |
  | 7b07d9e8-2686-4681-9cf9-7fb0aa5e9d36 | Një Bahshqe Me Lule, album version | 4:33 | z5gRjuAPf9Y | af48514d |
  | bfaed87b-6b4e-44c6-ac4b-63d372d075a2 | Qengji i Vogël, demo version 1986 (video) | 2:19 | u366yiZhAF4 | 6a6de48d |
  | 0373c02c-0b1d-40ac-bf31-5ba3494666a4 | Qengji i Vogël, album setting | 2:55 | qd9G6jBStbI (full album, track @06:00) | 29091f5e |

- Works (3):
  - **Një bahshqe me lule** — af48514d-0f6d-446c-8da6-0a95b8f152e9 (Song, Albanian lyrics)
    - Both recordings linked. Annotation: 136.0 BPM lock, A minor, same hook/lyric (green/red); Italia section (95.7 BPM) part of the song in both recordings; TVP chant words NOT legible on tape — "Italia" reading is from the album master only.
  - **Qengji i Vogël (demo setting (1986 first demo))** — 6a6de48d-f397-4d93-9aa8-b1111eede19d
    - Annotation: hardcore punk setting, B minor 95.7; same text as album setting, DIFFERENT music, not versions of each other.
  - **Qengji i Vogël (album setting (1987-1990 compilation))** — 29091f5e-4186-4010-9fa4-ae8cf9dcc590
    - Annotation: slow darkwave/post-punk setting; separate setting, not a re-record.

## Method notes (this session)
- Release editor: URL pre-fill sets artist NAME but not the confirmed credit — must click Search and select the disambiguated entity (green background = confirmed).
- Release-group field: unconfirmed text triggers "must select an existing release group" — clear it to create a new group on submit.
- Format: "I don't know" checkbox resets when switching tabs; re-check before submit.
- Relationship dialog: type menu populates after input event; MBID paste + search resolves exactly, BUT with same-named works (my two Qengji works) the default selected item may be the WRONG one — check disambiguation in the dropdown before clicking. The form defaulted to the album work when linking the demo; caught and fixed.
- Relationship-type menu: query #relationship-target--X-menu (NOT the first ul in the dialog — that's the type menu).

## Credentials
- MB account: arber_prishtina / password in /workspace/.credentials/musicbrainz.txt
- Session cookies refreshed: /workspace/mb_cookies.json (import works — verified logged in this session)
- Reset flow if file gone: musicbrainz.org/login → Forgot password → arber_prishtina → reset link to arber-2@ilands.app

## Next candidates
- 403, Minatori (next documentation pieces)
- Saint: Kino Lumbardhi Gitariada archive reply pending (MAK lineup question)
- Besnik: tab offer for Vogelushja Keti still open
