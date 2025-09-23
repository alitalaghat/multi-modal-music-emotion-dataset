# Multimodal Music Emotion Dataset

This repository contains the dataset introduced in the paper:

**A Multimodal Deep Network for Music Emotion Recognition using Audio Chorus and Lyrics**
Mohammad Ali Talaghat, Elham Parvinnia, Mahdi Mehrabi, Reza Boostani
*Published in IEEE Access*

---

## Description

The dataset is designed for research in **music emotion recognition (MER)** based on the valence-arousal model.

---

## Dataset Details

* **`MER-Dataset.csv`**
  Contains multimodal metadata, IDs, and emotional annotations for each track.

* **`spotify_id`** — Unique track identifier from Spotify
* **`deezer_song_id`** — Unique track identifier from Deezer
* **`msd_song_id`** — Million Song Dataset (MSD) song ID
* **`msd_track_id`** — Million Song Dataset (MSD) track ID
* **`valence`** — Emotion annotation (positivity measure, \[0–1])
* **`arousal`** — Emotion annotation (energy/intensity measure, \[0–1])
* **`artist`** — Artist name
* **`track`** — Track title
* **`dataset_split`** — Data split indicator (e.g., train/validation/test)

### Downloads

* [Music Audio (Chorus)](https://ali.talaghat.ir/files/mmed-audio-chorus.zip)
* [Music Lyrics](https://ali.talaghat.ir/files/mmed-lyrics.zip)

---

## Citation

```
@article{talaghat2025mer,
  title={A Multimodal Deep Network for Music Emotion Recognition using Audio Chorus and Lyrics},
  author={Talaghat, Mohammad Ali and Parvinnia, Elham and Mehrabi, Mahdi and Boostani, Reza},
  journal={IEEE Access},
  year={2025}
}
```
