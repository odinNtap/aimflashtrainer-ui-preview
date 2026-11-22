# AIM/FLASH Trainer — UI preview

Standalone interface reference with synthetic demonstration data. No Steam API, account files, game saves or Cloud writes.

Primary review size: **1920×1080, 100% zoom**. Choose VALORANT or Counter-Strike 2 on the first screen. **F8 → «Патч A · новые экраны»** opens match and calibration review states.

The 22 November update adds D–S++ ranks and the new unranked question-mark badge, ten calibration cards, ranked BO5 and unranked friend-duel views, 10/5-second preparation and 5-second round-result states, match statistics and next actions, per-game leaderboards, combined FPS/ping choices, automatic save scope, sensitivity conversion, CS2 flash presentation, and the exclusive S1 collection concept. Existing archive, help, errors, protection and playlist states remain in F8.

Match transitions are manually selected presentation states; this preview does not prove live networking, performance, production data correctness or visual parity with the Windows build. Arena art uses existing project textures, rendered here as a lightweight illustration for HUD review.

Rank artwork correction: the ORIGINAL ds_v1 metal emblems are preserved: titanium D, teal C, cobalt B, amethyst A, gold/ruby S and the original unranked question mark. Five source images were refined with embossed rank letters using imagegen; internal plus glyphs distinguish all 15 steps. Generic vector shields from 5e4762f are superseded. Images are sized for readability at 1920×1080 / DPR1: rail 48, expanded summary 56, table 64, calibration 80, profile 104, full ladder 112 px. Shared bitmaps are embedded only once in the page. No game/runtime/save changes.

Division refinement: large white +/++ on a dark, family-accented inset at the lower right of the emblem. Bitmap artwork and letters are unchanged. Symbols are 16% of icon height (7.68px at the minimum 48px context), instead of small metallic marks among the facets. Browser review: 1920×1080/DPR1, full ladder, calibration, table and compact/profile rank.

Shared rank structure: the original family bitmap silhouettes now share a deterministic SVG center with the same 240×280 letter box, position (380,330), baseline 610 and 1000×1000 viewBox. All 15 ranks and the question mark use it. The dark +/++ inset has the same position and dimensions for every family. Metals, colors, wings, crown and outer shapes remain distinct. Browser-rendered contours of all 16 icons were measured, alongside 1920×1080/DPR1 context checks. Earlier raster-letter variants are historical.

Rank finish refinement: Bahnschrift outlines replace hand-drawn block letters, with unchanged symbol bounds and positions. Thin polished rims, subtle face facets and soft highlights replace the heavy borders; +/++ use the same typeface inside softly rounded metal/enamel tabs. All 31 letter/plus bounds were compared before/after in the browser; source bitmaps and framing are unchanged. Verified contexts at 1920×1080 / DPR1.


UI-UNRANKED-RESTORE-06 · 22.11: «Без ранга» возвращён к исходному металлическому шестиугольнику с объёмным знаком ?. Без новой центральной вставки; прежние размеры/кадрирование. Остальные 15 D–S++ SVG побайтно неизменны. Только HTML-макет.


UI-RANK-FIRE-07: static painted fire variants for every +/++ rank; original base ranks and unranked unchanged. Letter/division geometry retained.


UI-RANK-SCALE-08: align base/+/++ emblem scale; external flame gutter preserves full artwork and unchanged glyph size. Checked at1920×1080.


UI-RANK-PLUS-09: moderately stronger painted flames for single-plus ranks only; geometry, base ranks and double-plus ranks unchanged.


## UI-HOME-COMPLETE-10 · 22 Nov 2026

New mode-first Home: Aim, flashes, ranked and friend duel; playlists/resume/daily and all three weekly tasks. Open “Проверить весь макет” or footer “Карта макета” for80primary screens/states. Covers VAL/CS2, queues/warmup/countdowns/outcomes/rematch, calibration, S1/S2/rewards, settings, Cloud/error states, news and sample diagnostics. Review controls and fixtures are prototype-only. No Steam or actual game saves.1920×1080/DPR1 validated;1366×768 overflow/CTA check passed. Native game, GPU/audio/input, physical two-PC and release gates remain separate.

22.11 · UI-HOME-CLEANUP-11: shared styling, separate playlist library and daily section; tasks/help/news top right. Preview controls opt-in through «Тест макета». 1920×1080 and 1366×768 checked.

22.11 · UI-HOME-POLISH-12: welcome line restored, taller recommendation/resume fills lower Home; training illustrations for Aim/VAL/CS2; capsule navigation. 1920×1080 and compact spacing verified.

22.11 · UI-HOME-MINIMAL-13: minimal mode symbols, clean game choice and capsule switcher; actual current exercise preview behind recommendation/resume. Daily step 1→2, VAL/CS2, 1920×1080 and 1366×768 checked.

22.11 · UI-NAVIGATION-PLAYLIST-14: fixed game colors, compact rail rank/back/grid; redesigned playlist composition; calibration card button; inline cancellable search with infinity warmup and navigation persistence. Synthetic preview only; 1920/1366 checked.
