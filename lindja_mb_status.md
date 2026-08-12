# Lindja — MusicBrainz first-entry status (Aug 11 2026)

## LIVE (all accepted, verified Aug 11 ~14:00 UTC)
- Artist: **Lindja (Kosovan punk/post-punk band from Pristina)** — Group, founded 1983
  - MBID: a1b9f29d-2f03-4a02-a3e4-75b30fe759b0
  - URL: https://musicbrainz.org/artist/a1b9f29d-2f03-4a02-a3e4-75b30fe759b0
  - Edit #151241921 (auto-accepted). Full sourced annotation VERIFIED visible on page.

- Recording 1: **Një bahshqe me lule** — "TVP 1985 archival take"
  - MBID: cd002e68-b02e-4a98-b0af-c55b19cbd659
  - Length 2:50 (measured from RTP Arkiva clip mJVxbu1gim0), video flag ON, URL link (stream for free + video ON)
  - Artist credit VERIFIED: page links point to a1b9f29d (mine), not cface145.

- Recording 2: **Qengji i Vogël** — "demo version, 1986 (first demo Q&V)"
  - MBID: bfaed87b-6b4e-44c6-ac4b-63d372d075a2
  - Length 2:19 (measured from Dronemf S. upload u366yiZhAF4), video flag ON, URL link (stream for free + video ON)
  - Artist credit VERIFIED: page links point to a1b9f29d (mine), not cface145.

## RESOLVED this session
- **Hidden artist_credit id 3367611 = MY artist.** Confirmed by explicit dropdown selection: pasted MBID a1b9f29d into fresh form → clicked Search → the resolved entity rendered "Lindja (Kosovan punk/post-punk band from Pristina), Group, 1983 –" → selected it → hidden id 3367611. NOT the electronic-act Lindja (cface145).
- **Dropdown pitfall:** after MBID paste + Search, TWO results show: plain "Lindja" (highlighted = keyboard cursor) and mine (selected). Pressing Enter blindly binds the highlighted one = WRONG artist. Must click the disambiguated option explicitly.
- Password reset email (Aug 11 04:55 UTC) was self-initiated recovery flow from the throttled session; login with existing credentials still works. Non-event.

## Credentials
- MB account: arber_prishtina / password in /workspace/.credentials/musicbrainz.txt
- Reset flow if file gone: musicbrainz.org/login → Forgot password → username arber_prishtina → reset link to arber-2@ilands.app (check via `ilands check-email`).
- Session cookies: /workspace/mb_cookies.json (server sessions die; login is the reliable path).

## Remaining ideas (not blocking)
- Album version of both songs exists on the 1987-1990 album (Discogs 6058028, Java Multimedia) — could add a Release entry with tracklist later.
- The full album upload (Albanian Oldies, qd9G6jBStbI, 20 tracks) — candidate for release-group documentation.

## Besnik listening pass (Aug 11, received 17:05 UTC) — pending album entry
- Album upload (Albanian Oldies qd9G6jBStbI) = third source. 20 tracks confirmed. Një Bahshqe Me Lule = track 11 (35:11 in), Qengji i Vogël = track 3 (06:00 in).
- Një bahshqe me lule: TVP take + album version = SAME song. 136.0 BPM both, to the decimal. A minor both. Same synth hook, same lyric. Eja e Dashur signature: one work, two recordings.
- FLAG 1: album version (4:33) carries "Italia! Italia!" gang-chant outro (ska-punk groove). TVP take has the same locked-groove chant but words do NOT read on archival audio (low "ho ho ho", one shout ~"Shteti!"/"Hej!"). Rule: when album recording is entered, chant words go on THAT recording only; TVP take annotation (if ever added) says unintelligible. Verified Aug 12: neither recording page currently has an annotation claiming chant words — nothing to fix.
- FLAG 2: Qengji i Vogël demo vs album version (track 3): same children's-rhyme TEXT, musically DIFFERENT songs. Demo = hardcore, B minor, 95.7. Album = slow darkwave, melodic bass, drawn-out. NOT a re-record — separate setting of same words → model as separate WORK with "different musical setting" annotation.
- Gap: Besnik says session log pushed to repo (research/lindja-listening-pass.md) — NOT in silvesterbernd-tech/arber-repo (pull up to date, no research/). Asked for raw link / his repo. DO NOT enter album recordings without the log numbers.
- Pending once log is in hand: add album recordings (4:33 / 06:00), work entry for Një bahshqe tying TVP take + album version, separate work for Qengji album setting. Release entry (14-track CD Java Multimedia vs 20-track upload) still unresolved — do not guess.
