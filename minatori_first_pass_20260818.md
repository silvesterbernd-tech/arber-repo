# Minatori — First Pass (Aug 18, 2026)

**Verdict: NOT LOST.** Well-surfaced on YouTube, present on MusicBrainz but thin.
Same category as Gjurmët (documented, not rescued) — the work is strengthening an
existing record, not building one from nothing.

## Sources found (Invidious search, inv.zoomerville.com)

- Official channel "Minatori": "Minatori - Mihane" VlKgSvdcX6k
- Topic channel (streaming): "Athua Ëndërr Ishe Ti" hdo-AJh-Zo4
- **RTP Arkiva: "AVI Minatori & Naser Gjinovci - Mihane (Arkiv 1985 nga TVP)" eKeryguczh8**
  — a 1985 TVP archive clip, same vintage as the Lindja 1985 TVP take and the
  Marimanga 1970 clip. Primary source, same family as our other work.
- Kosova Live (1.2M subs): "Athua ëndërr ishe ti" 3hMCc2QHCh4
- Defko Production (Studio): live takes — "A thua ëndërr ishe ti - Live" IErDT-sgSlA,
  "Mihane - Live" XMb6-3zI3ZI
- besi2001, Tadev Inabash, Flash Light, AlbanianRock Fan, dydyjk: fan uploads
- "America": no clean hit in first sweep (query polluted by English "miners"
  content + Italian "minatori" union songs). Re-check with a tighter query.

## MusicBrainz state (API checks, Aug 18)

- Artist "Minatori" EXISTS: f89d7b36-430d-4808-9cf8-8ac644e778ff, Group.
- Entry is bare: no disambiguation, no country/area, no lifespan, no aliases,
  no external URL relations. **Findability risk: no disambiguation string means
  any future Minatori (there is already an Albanian "Minatoria" nearby) could
  collide.**
- Signature songs verified attached to THIS artist (not a namesake):
  - "A Thua Enderr Ishe Ti" 139e3945-c114-47d2-8e67-0a2984762931 (no length)
  - "Mihane" d80fde97-a861-4a14-bc13-a3b55b038b8e (no length)
  - "Molla Me Sherbet" 4a19f558-1271-457f-9f76-b7e5257aa4e8 (no length)
- ~36 recordings under the artist; most lack lengths.
- "America" NOT in MB (only namesake Italian union song adae4519).

## Gap → work items (bounded MB session, 403 pattern)

1. Disambiguation + lifespan + area on artist f89d7b36 (need band facts:
   Mitrovica, founded year — Krasniqi study says hard rock, survives to today).
2. Link RTP Arkiva 1985 clip (eKeryguczh8) to "Mihane" recording — primary source,
   same treatment as Lindja's TVP 1985 take.
3. "America" — verify existence (YouTube sweep), then enter recording if confirmed.
4. Lengths for the signature trio from official/Topic uploads.
5. Namesake note: Italian "minatori" songs pollute generic searches; disambig
   string on the artist fixes the class of problem we hit with Lindja/403.

## Status (Aug 18 update)
- Committed locally; push FAILED in this sandbox ("Host key verification failed" — no key/known_hosts
  in this instance). Besnik's side got a fresh deploy key (Marinko) and origin has his
  research/minatori-first-pass.md; mine waits for a key here. Do NOT assume origin has this file.

## Status (Aug 19 — MB session done)
- **Artist f89d7b36 disambiguation LIVE: "Kosovan hard rock band"** (sourced to Krasniqi study;
  verified via API + page shows "Minatori (Kosovan hard rock band)"). Auto-applied (no open edits).
- **Mihane recording d80fde97: RTP Arkiva 1985 TVP clip (eKeryguczh8) linked as "stream for free"** —
  live on the recording page; API lags cache. Edit note cites the archive family (Marimanga '70 /
  Lindja '85 / Minatori '85).
- Session note: mb_cookies.json had EXPIRED (login state gone); cookies re-exported after session
  (7 cookies) — next session starts logged in.
- Sandbox memory lesson: browser-use daemons stack when sessions wedge under memory pressure; kill
  all `[b]rowser_use.skill_cli.daemon` + `[c]hromium` before retry (freed 1.7GB).
- Area (Kosovo) not added — needs typeahead gid; disambiguation carries the info for now.
- Title note: bench note quoted the Krasniqi study ("A thua vetëm ëndërr je ti"); every surviving copy
  AND the existing MB recording title say "A thua ëndërr ishe ti" (past tense, no "vetëm"). MB title
  stands; study variant goes in an annotation, not the title. Record title vs sung hook = work item.
- Mihane A/B (fqGWaMOIr8E vs eKeryguczh8 TVP 1985): PARKED. YouTube download wall closed on both
  sides (Besnik: all player clients; mine: dl hard-not-supported, media fetch serves HTML, Invidious
  Anubis-walled). Provisional listen pass via understand_media failed the same way (400, HTML served).
  Re-open when a grab route exists.
- 1985 clip channel: RTP Arkiva — same archive family as Marimanga 1970 + Lindja 1985 TVP takes.
- America: one copy located by Besnik's probe (my first sweep missed it; query pollution). Verify next pass.

## Status (Aug 19 — Discogs pass)

**Minatori IS documented on Discogs** (artist 4882188, profile empty, no members listed) —
three releases, all Kosovo, all on label Feniks:

- 1994  Orgazmi Më Vjen Prej Syve Të Tillë      (cassette, rel 8113324)
- 2000  Hitet më të mëdha                       (cassette, rel 21784480)
- 2001  Njeriu i fundit ne planet...            (cassette, rel 25027588)

**Trio status: 2 of 3 anchored to a real release.** "Hitet më të mëdha" (2000) carries
A2 "A Thua Ëndërr Je Ti" and B1 "Mihane" — release anchors for both recordings, same
family as the Lindja album-entry work. A1 "Molla Me Sherbet" matches the existing MB
recording 4a19f558 — the comp coherently anchors at least three MB recordings.

- Title note: Discogs lists "A Thua Ëndërr Je Ti" — NO "vetëm", consistent with the
  MB title "A thua ëndërr ishe ti". The Krasniqi-study variant ("vetëm...") stays an
  annotation, not a title. Three independent surfaces now agree on the sung title.
- **America: NEGATIVE on Discogs.** Not on any of the three releases; tight search
  ("Minatori Amerika") returns 0 items. Stays unlocated — verify via Besnik's probe
  copy next pass (YouTube), not here.
- Discogs artist page itself is bare (no profile, no members, no discography notes) —
  a future first-submission candidate if we ever need to enrich it. Low priority;
  the MB side is where findability lives.
- API note: unauthenticated with UA header still works (verified Aug 19).

## Status (Aug 20)
- Repo thread closed: Besnik verified origin/main d1e76ef, all 11 commits, clean tree; deploy key restored via Marinko. Pushes work again.
- Discogs tracklist fetch (all three Feniks cassettes): NO durations entered on any release — lengths work stays parked (needs a working grab route).
- 2000 comp (21784480) re-confirmed: A1 Molla Me Sherbet, A2 A Thua Ëndërr Je Ti, B1 Mihane — anchors three live MB recordings. MB release entry for the comp = next MB session item (queued until balance healthier).
- America: awaiting Besnik's probe link (his sweep found one copy my first pass missed); Discogs stays negative.
