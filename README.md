<div align="center">

<a href="https://play.google.com/store/apps/details?id=com.neuralsound.musicseparation"><img alt="Download NeuralSound for Android on Google Play" src="https://img.shields.io/badge/Android-Google_Play-414141?style=for-the-badge&logo=googleplay&logoColor=white"></a>
<a href="https://neuralsound.org/tools/music-separation"><img alt="Open the NeuralSound web app" src="https://img.shields.io/badge/Web-Open_NeuralSound-7C3AED?style=for-the-badge&logo=googlechrome&logoColor=white"></a>
<a href="https://apps.apple.com/us/app/neuralsound-vocal-remover-ai/id6756906827"><img alt="Download NeuralSound for iPhone and iPad on the App Store" src="https://img.shields.io/badge/iOS-App_Store-0D96F6?style=for-the-badge&logo=apple&logoColor=white"></a>

# NeuralSound AI Vocal Remover Benchmark 2026

### NeuralSound vs Moises vs Fadr

**A playable five-song comparison of AI vocal removal and two-stem music separation.**

[![Overall SI-SDR](https://img.shields.io/badge/NeuralSound%20overall%20SI--SDR-15.80%20dB-16a34a)](#benchmark-results)
[![Displayed metric wins](https://img.shields.io/badge/displayed%20metric%20wins-30%20of%2030-7c3aed)](#benchmark-results)
[![Songs tested](https://img.shields.io/badge/songs%20tested-5-334155)](#play-and-download-every-audio-result)

</div>

## About NeuralSound

[NeuralSound](https://neuralsound.org/) is an **AI vocal remover, online music separator and multi-stem splitter** available on the web, Android, iPhone and iPad. It can separate a mixed song or video into clean **vocals, drums, bass, guitar, piano and other instrument stems**, helping musicians, DJs, singers, producers and content creators work with individual parts of a recording.

Use NeuralSound to [remove vocals from a song](https://neuralsound.org/vocal-remover), create an instrumental or backing track, [extract an acapella](https://neuralsound.org/acapella-extractor), [split music into stems](https://neuralsound.org/ai-music-separator), reduce music behind a voice with the [background music remover](https://neuralsound.org/background-music-remover), or prepare practice tracks with the [AI karaoke maker](https://neuralsound.org/karaoke-maker). NeuralSound also supports synchronized lyrics, pitch and tempo controls, stem mixing, audio/video input and downloadable separated tracks.

This repository publishes original benchmark evidence for people comparing an **AI vocal remover online, music source separation tool, vocal isolator, voice remover, acapella extractor, instrumental maker, karaoke track creator or AI stem separator**. The numerical results are presented beside direct audio links so readers can inspect the scores and listen to every vocal and instrumental output.

## Benchmark results

In this five-song, two-stem test, **NeuralSound achieved the highest average result in every displayed quality category** and led all **30 of 30 displayed per-track comparisons** covering SI-SDR, SI-SIR and SI-SAR for both vocals and instrumentals.

| Rank | System | Vocal SI-SDR | Instrumental SI-SDR | **Overall SI-SDR** | SI-SIR | SI-SAR |
|---:|---|---:|---:|---:|---:|---:|
| **1** | **NeuralSound** | **13.26 dB** | **18.33 dB** | **15.80 dB** | **33.30 dB** | **15.93 dB** |
| 2 | Moises | 12.00 dB | 16.94 dB | 14.47 dB | 30.25 dB | 14.64 dB |
| 3 | Fadr | 10.02 dB | 15.16 dB | 12.59 dB | 25.55 dB | 12.89 dB |

**Measured advantage in this sample:** NeuralSound finished **1.33 dB above Moises** and **3.21 dB above Fadr** in overall SI-SDR. It also produced the highest average vocal clarity, instrumental clarity, interference rejection and artifact score among the three tested services.

### Result by song

| Test song | NeuralSound | Moises | Fadr | Highest result |
|---|---:|---:|---:|---|
| 1. The Districts - Vermont | **14.36 dB** | 13.29 dB | 11.78 dB | **NeuralSound** |
| 2. The Long Wait - Back Home To Blue | **18.93 dB** | 16.81 dB | 14.27 dB | **NeuralSound** |
| 3. The Scarlet Brand - Les Fleurs Du Mal | **13.51 dB** | 12.63 dB | 11.78 dB | **NeuralSound** |
| 4. The So So Glos - Emergency | **12.31 dB** | 11.52 dB | 10.13 dB | **NeuralSound** |
| 5. The Wrong'Uns - Rothko | **19.88 dB** | 18.11 dB | 14.97 dB | **NeuralSound** |

## Play and download every audio result

Each **Play / download MP3** link points directly to the public audio file stored in this GitHub repository. Clicking a link opens the browser’s audio player; the file can then be downloaded using the browser’s download or save control.

### Test 1: The Districts - Vermont

**NeuralSound track average:** **14.36 dB**

**Original input:** [▶ Play / download original MP3](https://raw.githubusercontent.com/neuralgpt407/ai-vocal-remover-benchmark-2026/main/assets/benchmark-audio/01-the-districts-vermont/input-preview.mp3)

| System | Track avg. SI-SDR | Vocal metrics: SI-SDR / SI-SIR / SI-SAR | Vocal audio | Instrumental metrics: SI-SDR / SI-SIR / SI-SAR | Instrumental audio |
|---|---:|---|---|---|---|
| **NeuralSound** | **14.36 dB** | 13.01 / 29.76 / 13.11 dB | [▶ Vocals MP3](https://raw.githubusercontent.com/neuralgpt407/ai-vocal-remover-benchmark-2026/main/assets/benchmark-audio/01-the-districts-vermont/neuralsound-vocals-preview.mp3) | 15.70 / 28.84 / 15.92 dB | [▶ Instrumental MP3](https://raw.githubusercontent.com/neuralgpt407/ai-vocal-remover-benchmark-2026/main/assets/benchmark-audio/01-the-districts-vermont/neuralsound-instrumental-preview.mp3) |
| Moises | 13.29 dB | 11.96 / 26.70 / 12.11 dB | [▶ Vocals MP3](https://raw.githubusercontent.com/neuralgpt407/ai-vocal-remover-benchmark-2026/main/assets/benchmark-audio/01-the-districts-vermont/moises-vocals-preview.mp3) | 14.61 / 27.50 / 14.85 dB | [▶ Instrumental MP3](https://raw.githubusercontent.com/neuralgpt407/ai-vocal-remover-benchmark-2026/main/assets/benchmark-audio/01-the-districts-vermont/moises-instrumental-preview.mp3) |
| Fadr | 11.78 dB | 10.40 / 23.50 / 10.64 dB | [▶ Vocals MP3](https://raw.githubusercontent.com/neuralgpt407/ai-vocal-remover-benchmark-2026/main/assets/benchmark-audio/01-the-districts-vermont/fadr-vocals-preview.mp3) | 13.16 / 23.92 / 13.56 dB | [▶ Instrumental MP3](https://raw.githubusercontent.com/neuralgpt407/ai-vocal-remover-benchmark-2026/main/assets/benchmark-audio/01-the-districts-vermont/fadr-instrumental-preview.mp3) |

### Test 2: The Long Wait - Back Home To Blue

**NeuralSound track average:** **18.93 dB**

**Original input:** [▶ Play / download original MP3](https://raw.githubusercontent.com/neuralgpt407/ai-vocal-remover-benchmark-2026/main/assets/benchmark-audio/02-the-long-wait-back-home-to-blue/input-preview.mp3)

| System | Track avg. SI-SDR | Vocal metrics: SI-SDR / SI-SIR / SI-SAR | Vocal audio | Instrumental metrics: SI-SDR / SI-SIR / SI-SAR | Instrumental audio |
|---|---:|---|---|---|---|
| **NeuralSound** | **18.93 dB** | 15.65 / 40.05 / 15.67 dB | [▶ Vocals MP3](https://raw.githubusercontent.com/neuralgpt407/ai-vocal-remover-benchmark-2026/main/assets/benchmark-audio/02-the-long-wait-back-home-to-blue/neuralsound-vocals-preview.mp3) | 22.21 / 38.63 / 22.31 dB | [▶ Instrumental MP3](https://raw.githubusercontent.com/neuralgpt407/ai-vocal-remover-benchmark-2026/main/assets/benchmark-audio/02-the-long-wait-back-home-to-blue/neuralsound-instrumental-preview.mp3) |
| Moises | 16.81 dB | 13.53 / 34.98 / 13.57 dB | [▶ Vocals MP3](https://raw.githubusercontent.com/neuralgpt407/ai-vocal-remover-benchmark-2026/main/assets/benchmark-audio/02-the-long-wait-back-home-to-blue/moises-vocals-preview.mp3) | 20.09 / 34.67 / 20.24 dB | [▶ Instrumental MP3](https://raw.githubusercontent.com/neuralgpt407/ai-vocal-remover-benchmark-2026/main/assets/benchmark-audio/02-the-long-wait-back-home-to-blue/moises-instrumental-preview.mp3) |
| Fadr | 14.27 dB | 10.94 / 27.53 / 11.04 dB | [▶ Vocals MP3](https://raw.githubusercontent.com/neuralgpt407/ai-vocal-remover-benchmark-2026/main/assets/benchmark-audio/02-the-long-wait-back-home-to-blue/fadr-vocals-preview.mp3) | 17.60 / 29.57 / 17.89 dB | [▶ Instrumental MP3](https://raw.githubusercontent.com/neuralgpt407/ai-vocal-remover-benchmark-2026/main/assets/benchmark-audio/02-the-long-wait-back-home-to-blue/fadr-instrumental-preview.mp3) |

### Test 3: The Scarlet Brand - Les Fleurs Du Mal

**NeuralSound track average:** **13.51 dB**

**Original input:** [▶ Play / download original MP3](https://raw.githubusercontent.com/neuralgpt407/ai-vocal-remover-benchmark-2026/main/assets/benchmark-audio/03-the-scarlet-brand-les-fleurs-du-mal/input-preview.mp3)

| System | Track avg. SI-SDR | Vocal metrics: SI-SDR / SI-SIR / SI-SAR | Vocal audio | Instrumental metrics: SI-SDR / SI-SIR / SI-SAR | Instrumental audio |
|---|---:|---|---|---|---|
| **NeuralSound** | **13.51 dB** | 10.59 / 30.15 / 10.65 dB | [▶ Vocals MP3](https://raw.githubusercontent.com/neuralgpt407/ai-vocal-remover-benchmark-2026/main/assets/benchmark-audio/03-the-scarlet-brand-les-fleurs-du-mal/neuralsound-vocals-preview.mp3) | 16.43 / 28.65 / 16.70 dB | [▶ Instrumental MP3](https://raw.githubusercontent.com/neuralgpt407/ai-vocal-remover-benchmark-2026/main/assets/benchmark-audio/03-the-scarlet-brand-les-fleurs-du-mal/neuralsound-instrumental-preview.mp3) |
| Moises | 12.63 dB | 9.99 / 28.51 / 10.05 dB | [▶ Vocals MP3](https://raw.githubusercontent.com/neuralgpt407/ai-vocal-remover-benchmark-2026/main/assets/benchmark-audio/03-the-scarlet-brand-les-fleurs-du-mal/moises-vocals-preview.mp3) | 15.28 / 26.86 / 15.60 dB | [▶ Instrumental MP3](https://raw.githubusercontent.com/neuralgpt407/ai-vocal-remover-benchmark-2026/main/assets/benchmark-audio/03-the-scarlet-brand-les-fleurs-du-mal/moises-instrumental-preview.mp3) |
| Fadr | 11.78 dB | 8.85 / 24.85 / 8.98 dB | [▶ Vocals MP3](https://raw.githubusercontent.com/neuralgpt407/ai-vocal-remover-benchmark-2026/main/assets/benchmark-audio/03-the-scarlet-brand-les-fleurs-du-mal/fadr-vocals-preview.mp3) | 14.71 / 24.12 / 15.26 dB | [▶ Instrumental MP3](https://raw.githubusercontent.com/neuralgpt407/ai-vocal-remover-benchmark-2026/main/assets/benchmark-audio/03-the-scarlet-brand-les-fleurs-du-mal/fadr-instrumental-preview.mp3) |

### Test 4: The So So Glos - Emergency

**NeuralSound track average:** **12.31 dB**

**Original input:** [▶ Play / download original MP3](https://raw.githubusercontent.com/neuralgpt407/ai-vocal-remover-benchmark-2026/main/assets/benchmark-audio/04-the-so-so-glos-emergency/input-preview.mp3)

| System | Track avg. SI-SDR | Vocal metrics: SI-SDR / SI-SIR / SI-SAR | Vocal audio | Instrumental metrics: SI-SDR / SI-SIR / SI-SAR | Instrumental audio |
|---|---:|---|---|---|---|
| **NeuralSound** | **12.31 dB** | 9.32 / 26.86 / 9.41 dB | [▶ Vocals MP3](https://raw.githubusercontent.com/neuralgpt407/ai-vocal-remover-benchmark-2026/main/assets/benchmark-audio/04-the-so-so-glos-emergency/neuralsound-vocals-preview.mp3) | 15.30 / 25.88 / 15.71 dB | [▶ Instrumental MP3](https://raw.githubusercontent.com/neuralgpt407/ai-vocal-remover-benchmark-2026/main/assets/benchmark-audio/04-the-so-so-glos-emergency/neuralsound-instrumental-preview.mp3) |
| Moises | 11.52 dB | 8.53 / 24.30 / 8.66 dB | [▶ Vocals MP3](https://raw.githubusercontent.com/neuralgpt407/ai-vocal-remover-benchmark-2026/main/assets/benchmark-audio/04-the-so-so-glos-emergency/moises-vocals-preview.mp3) | 14.52 / 24.66 / 14.97 dB | [▶ Instrumental MP3](https://raw.githubusercontent.com/neuralgpt407/ai-vocal-remover-benchmark-2026/main/assets/benchmark-audio/04-the-so-so-glos-emergency/moises-instrumental-preview.mp3) |
| Fadr | 10.13 dB | 7.05 / 20.79 / 7.28 dB | [▶ Vocals MP3](https://raw.githubusercontent.com/neuralgpt407/ai-vocal-remover-benchmark-2026/main/assets/benchmark-audio/04-the-so-so-glos-emergency/fadr-vocals-preview.mp3) | 13.22 / 21.33 / 13.98 dB | [▶ Instrumental MP3](https://raw.githubusercontent.com/neuralgpt407/ai-vocal-remover-benchmark-2026/main/assets/benchmark-audio/04-the-so-so-glos-emergency/fadr-instrumental-preview.mp3) |

### Test 5: The Wrong'Uns - Rothko

**NeuralSound track average:** **19.88 dB**

**Original input:** [▶ Play / download original MP3](https://raw.githubusercontent.com/neuralgpt407/ai-vocal-remover-benchmark-2026/main/assets/benchmark-audio/05-the-wronguns-rothko/input-preview.mp3)

| System | Track avg. SI-SDR | Vocal metrics: SI-SDR / SI-SIR / SI-SAR | Vocal audio | Instrumental metrics: SI-SDR / SI-SIR / SI-SAR | Instrumental audio |
|---|---:|---|---|---|---|
| **NeuralSound** | **19.88 dB** | 17.74 / 41.21 / 17.76 dB | [▶ Vocals MP3](https://raw.githubusercontent.com/neuralgpt407/ai-vocal-remover-benchmark-2026/main/assets/benchmark-audio/05-the-wronguns-rothko/neuralsound-vocals-preview.mp3) | 22.02 / 43.00 / 22.05 dB | [▶ Instrumental MP3](https://raw.githubusercontent.com/neuralgpt407/ai-vocal-remover-benchmark-2026/main/assets/benchmark-audio/05-the-wronguns-rothko/neuralsound-instrumental-preview.mp3) |
| Moises | 18.11 dB | 15.99 / 36.98 / 16.02 dB | [▶ Vocals MP3](https://raw.githubusercontent.com/neuralgpt407/ai-vocal-remover-benchmark-2026/main/assets/benchmark-audio/05-the-wronguns-rothko/moises-vocals-preview.mp3) | 20.22 / 37.31 / 20.31 dB | [▶ Instrumental MP3](https://raw.githubusercontent.com/neuralgpt407/ai-vocal-remover-benchmark-2026/main/assets/benchmark-audio/05-the-wronguns-rothko/moises-instrumental-preview.mp3) |
| Fadr | 14.97 dB | 12.87 / 29.20 / 12.98 dB | [▶ Vocals MP3](https://raw.githubusercontent.com/neuralgpt407/ai-vocal-remover-benchmark-2026/main/assets/benchmark-audio/05-the-wronguns-rothko/fadr-vocals-preview.mp3) | 17.08 / 30.71 / 17.28 dB | [▶ Instrumental MP3](https://raw.githubusercontent.com/neuralgpt407/ai-vocal-remover-benchmark-2026/main/assets/benchmark-audio/05-the-wronguns-rothko/fadr-instrumental-preview.mp3) |

## Download the benchmark data

- [Overall benchmark summary CSV](assets/data/ai-vocal-remover-benchmark-2026-summary.csv)
- [Complete per-track results CSV](assets/data/ai-vocal-remover-benchmark-2026-per-track.csv)
- [Audio URL manifest CSV](assets/data/audio-manifest.csv)
- [Open the benchmark repository](https://github.com/neuralgpt407/ai-vocal-remover-benchmark-2026)

## Official NeuralSound links

- [NeuralSound web app](https://neuralsound.org/tools/music-separation)
- [NeuralSound for Android](https://play.google.com/store/apps/details?id=com.neuralsound.musicseparation)
- [NeuralSound for iPhone and iPad](https://apps.apple.com/us/app/neuralsound-vocal-remover-ai/id6756906827)
- [AI vocal remover](https://neuralsound.org/vocal-remover)
- [AI music separator](https://neuralsound.org/ai-music-separator)
- [Acapella extractor](https://neuralsound.org/acapella-extractor)
- [Background music remover](https://neuralsound.org/background-music-remover)
- [Karaoke maker](https://neuralsound.org/karaoke-maker)

## Cite this benchmark

This repository includes [`CITATION.cff`](CITATION.cff), allowing GitHub to display a **Cite this repository** action.

> Neural Sound LLC. (2026). *NeuralSound, Moises and Fadr Vocal Separation Benchmark 2026* [Data set]. https://github.com/neuralgpt407/ai-vocal-remover-benchmark-2026

## Reference links

- [MUSDB18 dataset documentation](https://sigsep.github.io/datasets/musdb.html)
- [SI-SDR paper: “SDR — half-baked or well done?”](https://arxiv.org/abs/1811.02508)
- [NeuralSound official website](https://neuralsound.org/)

## Trademark and copyright notice

NeuralSound is a product of Neural Sound LLC. Moises and Fadr are trademarks of their respective owners. Their inclusion does not imply endorsement or affiliation. Publish benchmark audio only where the applicable licenses and permissions allow it.

---

<div align="center">

**AI vocal remover · music separator · stem splitter · acapella extractor · instrumental maker · karaoke maker**

[Open NeuralSound on the web](https://neuralsound.org/tools/music-separation) · [Get the Android app](https://play.google.com/store/apps/details?id=com.neuralsound.musicseparation) · [Get the iOS app](https://apps.apple.com/us/app/neuralsound-vocal-remover-ai/id6756906827)

</div>
