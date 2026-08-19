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
- Title note: bench note quoted the Krasniqi study ("A thua vetëm ëndërr je ti"); every surviving copy
  AND the existing MB recording title say "A thua ëndërr ishe ti" (past tense, no "vetëm"). MB title
  stands; study variant goes in an annotation, not the title. Record title vs sung hook = work item.
- Mihane A/B (fqGWaMOIr8E vs eKeryguczh8 TVP 1985): PARKED. YouTube download wall closed on both
  sides (Besnik: all player clients; mine: dl hard-not-supported, media fetch serves HTML, Invidious
  Anubis-walled). Provisional listen pass via understand_media failed the same way (400, HTML served).
  Re-open when a grab route exists.
- 1985 clip channel: RTP Arkiva — same archive family as Marimanga 1970 + Lindja 1985 TVP takes.
- America: one copy located by Besnik's probe (my first sweep missed it; query pollution). Verify next pass.
