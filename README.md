# Woodshed — jazz sax practice app

A single-page practice app for jazz saxophone: metronome, tuner, drones, ear training and a study library of intervals, scales and chords. Everything is in `index.html`. It has no dependencies and works offline once loaded.

## Publish on GitHub Pages

1. Create a new repository on GitHub (e.g. `woodshed`). It can be public, or private if your plan includes Pages for private repos.
2. Upload `index.html` (and this README) to the root of the repo: **Add file → Upload files → Commit**.
3. Go to **Settings → Pages**, set **Source: Deploy from a branch**, branch **main**, folder **/ (root)**, and save.
4. After a minute your app is live at `https://<your-username>.github.io/woodshed/`.

## On the iPad

- Open the URL in Safari, tap **Share → Add to Home Screen**. It then opens full-screen like an app.
- The **tuner needs microphone permission**. That works because GitHub Pages serves over HTTPS.
- If you hear nothing, check the volume. On older iPadOS versions the silent switch or Control Center mute can also block web audio.
- **Keep awake** stops the screen from locking while you practise (iPadOS 16.4+).

## Features

- **Instrument transposition:** choose alto, tenor, soprano, baritone or concert. Every note name in the app is written for your horn, and the sound is at concert pitch.
- **Metronome:** 30–320 BPM, tap tempo, subdivisions, swing feel, click on 2 & 4 only, and a gap trainer that mutes bars to test your internal time.
- **Tuner:** shows the written note for your sax plus concert pitch, a cents meter, a pitch trace for long tones, and adjustable A4.
- **Drone:** all 12 keys with root, 5th, octave and major/minor voicings and 4 sounds. It can auto-change key around the cycle of 4ths.
- **Ear training, "Play it back":** builds random melodies from a key and note pool (chromatic or any scale). You can set the length, range, largest leap and tempo, then replay, slow down, reveal and score yourself. Auto level-up adds a note after 3 correct answers in a row.
- **Ear training, "Name it":** an interval, chord-quality or scale identification quiz.
- **Study library:** 19 intervals, 22 scales and 23 chords, spelled correctly in any key, with playback and a one-tap drone. You can track your progress per key (12 squares per item), and **"What should I practise?"** picks a weak spot and suggests a routine.

Progress and settings are saved in the browser on each device (localStorage).
