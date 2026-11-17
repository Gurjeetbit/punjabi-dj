# DholDeck Pro — Punjabi DJ, Mashup Studio & Auto-Tune

Live at **https://gurjeetbit.github.io/punjabi-dj/**

A browser DJ studio for Punjabi music. Everything runs on your device; songs are never uploaded.

**Perform** — pro deck layout: scrolling colour waveforms with beat grids, decks A/B/C with hot cues, loops, sync, key lock, pitch fader and nudge, a 3-channel mixer with gain/EQ/filter knobs, faders, VU meters and crossfader. Bottom panel: Library, Sampler pads (dhol, tumbi, chimta, algoza, tabla, sitar, 808s…), Beat Maker, Vocal & live Auto-Tune, Master FX.

**Mashup Studio** — DJ.Studio-style arrangement timeline. Pick a style (Bhangra Empire stage mix, DJ KSR-style wedding mix, quick-cut mashup, club remix, non-stop medley) or let Claude plan it (AI Mix, uses your own Anthropic API key). Every song section, dhol pattern, fill, melody, effect, shout and tempo change is a block you can move, resize, edit beat-by-beat, switch off or delete, with undo. Play / pause / seek, then render with a live progress bar to FLAC (48/96 kHz 24-bit), WAV or MP3 320.

Notes: browsers can't extract audio from YouTube or Apple Music links, so those songs need their audio file. Files: `index.html` and `lame.min.js` (MP3 encoder, [lamejs](https://github.com/zhuker/lamejs), LGPL).
