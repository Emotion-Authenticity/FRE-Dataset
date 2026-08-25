# FRE Dataset

## Overview

The **Fake and Real Emotions (FRE)** dataset was created to address persistent issues related to dataset size, lack of diversity, and cross-cultural variability in existing emotion authenticity datasets. It covers 6 basic emotions: **happiness, sadness, surprise, anger, disgust, and fear**.

---

## Dataset Criteria

| Attribute | Details |
|---|---|
| Number of Participants | 37 (30 male, 7 female) |
| Age Distribution | 20–30 years old |
| Language Used | English |
| Experiment Duration | 30–40 minutes |

---

## Dataset Characteristics

| Characteristic | Description |
|---|---|
| Emotions | Happy, Sad, Surprise, Anger, Disgust, Fear |
| Type of Data | Video recordings |
| Data Format | High-resolution .mp4 files at 100 frames per second |
| Video Length | 30–40 seconds |
| Total Number of Videos | 444 |
| Total Number of "Real" Videos | 222 |
| Total Number of "Fake" Videos | 222 |

---

## Collection Protocol

The dataset was collected using custom crowdsourcing to enhance ecological validity beyond typical laboratory-controlled experiments. Participants recorded videos using their personal laptop computers equipped with built-in HD cameras in self-selected environments (home, office, or car settings).

This naturalistic recording protocol:
- Minimizes demand characteristics and laboratory artifacts such as standardized lighting and unfamiliar settings
- Captures emotion patterns across heterogeneous recording conditions (variable lighting, camera angles, backgrounds)
- Better represents real-world emotional deception detection scenarios such as online interviews and security footage

---

## Experiment Design

Each participant was informed of the target emotion, then watched a set of pre-chosen videos designed to induce that emotion, based on the research by Paukner et al. Before each video, participants were required to display a neutral expression, which was recorded.

- **Real video**: captured the participant's genuine emotional response to the inducing video
- **Fake video**: captured the participant faking the same emotion from a neutral starting expression

Each participant produced **12 videos** in total:

| Type | Emotions |
|---|---|
| Real | Happy, Sad, Angry, Disgust, Surprise, Fear |
| Fake | Happy, Sad, Angry, Disgust, Surprise, Fear |

To avoid anticipation bias, **6 different videos** were available per emotion in case a recording needed to be redone.

---

## Video Matrix

The table below shows the experimental design. Each cell represents a separate video recording, starting from a neutral expression. `Real` = genuine emotional response, `Fake` = posed expression, `x` = emotion not targeted in that session.

| Emotion | Happy Video | Sad Video | Anger Video | Surprise Video | Disgust Video | Fear Video | No Video |
|---|---|---|---|---|---|---|---|
| Happy    | Real | x | x | x | x | x | Fake |
| Sad      | x | Real | x | x | x | x | Fake |
| Angry    | x | x | Real | x | x | x | Fake |
| Surprise | x | x | x | Real | x | x | Fake |
| Disgust  | x | x | x | x | Real | x | Fake |
| Fear     | x | x | x | x | x | Real | Fake |

---

## Stimulus Videos

All videos used to induce emotions were sourced from [YouTube](https://www.youtube.com) and [Vimeo](https://vimeo.com) under a **Creative Commons CC-BY license** based on the videos stated by [1] that induce emotions.

<details>
<summary><strong>Happy</strong></summary>

| Link | Creator |
|---|---|
| https://www.youtube.com/watch?v=Z9NQatne0xg | @MatthewWeathers |
| https://www.youtube.com/watch?v=nidx2C8xAEA | @Danny-Gonzalez |
| https://www.youtube.com/watch?v=oI0quoebaQ0 | @Bitwit |
| https://vimeo.com/40630317 | rozibaby |
| https://www.youtube.com/watch?v=5_e_CdA8xGE | @simplemansimpledan |
| https://www.youtube.com/watch?v=wDLzqIyUbf4 | @Savingthrowshow |
</details>

<details>
<summary><strong>Sad</strong></summary>

| Link | Creator |
|---|---|
| https://www.youtube.com/watch?v=Y1vOrptaEm4 | @muhammadhashimirshad1208 |
| https://www.youtube.com/watch?v=Ir2bekewg-8 | @FireKillsCampaign |
| https://www.youtube.com/watch?v=_oevXkJY-fE | @SustainableHuman |
| https://www.youtube.com/watch?v=qnEJMV4QjlE | @doctorswithoutborders |
| https://www.youtube.com/watch?v=bu4X02OUcpM | @mindlessimagination2770 |
| https://www.youtube.com/watch?v=SP2sOCbxVWc | @USNavy |
</details>

<details>
<summary><strong>Surprise</strong></summary>

| Link | Creator |
|---|---|
| https://www.youtube.com/watch?v=xVGfB0FSmrM | @thebigcrew8858 |
| https://www.youtube.com/watch?v=pzM0Yxdjeak | @tariqadnan5124 |
| https://www.youtube.com/watch?v=bpSIkPrl6vQ | @Fruchtpudding |
| https://www.youtube.com/watch?v=jUTnTVnyXhs | @madformagic |
| https://www.youtube.com/watch?v=1sIzTvKH18E | @richmond9517 |
| https://www.youtube.com/watch?v=YCm6Rxy1H78 | @BibliotecaCastillayLeón |
</details>

<details>
<summary><strong>Anger</strong></summary>

| Link | Creator |
|---|---|
| https://www.youtube.com/watch?v=O_PLtuMECe8 | @AdemoFreeman |
| https://www.youtube.com/watch?v=2pWij13kNJo | @producertony2001 |
| https://www.youtube.com/watch?v=pQK4261GXyg | @animalequality |
| https://www.youtube.com/watch?v=F04UqJYIhxg | @za1608 |
| https://www.youtube.com/watch?v=SGSrGmHsT8s | @sanjayseth719 |
| https://www.youtube.com/watch?v=6lfUGhHMj2o | @doyouknowme5497 |
</details>

<details>
<summary><strong>Disgust</strong></summary>

| Link | Creator |
|---|---|
| https://www.youtube.com/watch?v=q7Obb3lLDAk | @under_a_microscope8648 |
| https://www.youtube.com/watch?v=VLTQmRF2am4 | @oracleofdelphi555 |
| https://www.youtube.com/watch?v=nxr35cku_bQ | @GammelFood |
| https://www.youtube.com/watch?v=bILHr2xfIKo | @GammelFood |
| https://www.youtube.com/watch?v=XCcfbfdhd2Y | @99pups |
| https://www.youtube.com/watch?v=tWPPZKQj1uE | @CinesimMedia |
</details>

<details>
<summary><strong>Fear</strong></summary>

| Link | Creator |
|---|---|
| https://www.youtube.com/watch?v=Tu3q4W0-TvM | @ABristolBoy |
| https://www.youtube.com/watch?v=LYKyhQoJhI0 | @vanguardstudiosvfx |
| https://www.youtube.com/watch?v=QuwJfXisFmc | @partofthesolution9063 |
| https://www.youtube.com/watch?v=8LYplnecFog | @JuanAlcazar |
| https://www.youtube.com/watch?v=IJFp8dmJxPk | @JuanAlcazar |
| https://www.youtube.com/watch?v=PUX5FzpBbcQ | @BBCEarthScience |
</details>

---

## Preprocessing

Each video was processed as follows:
1. Split into individual frames (`.jpg`)
2. Frames cropped to contain only the participant's face
3. Resized to **255×256 pixels**
4. Quality reviewed — videos with significant artifacts or disruptions were excluded

---

## FAU Extraction

Facial Action Unit (FAU) intensity values (`_r`) and FAU presence values (`_c`) for 17 FAUs per frame were extracted from all video frames using [OpenFace](https://github.com/TadasBaltrusaitis/OpenFace) [2]. 

---

## Ethics Statement

- All participants provided **written informed consent** before participation.
- All video recordings are stored on **password-protected institutional servers**.
- Participant identities are **not disclosed** in any published materials.
- Participants were informed of their **right to withdraw data** at any time without consequence.
- Due to the consent limitations, the raw video could not be shared; sonly the .CSV files are available for use.

## References
[1] Israel, L., Paukner, P., Schiestel, L., Diepold, K., & Schönbrodt, F. D. (2021, September 27). The OpenLAV video database for affect induction: Analyzing the uniformity of video stimuli effects. https://doi.org/10.31234/osf.io/vhmbq
[2] OpenFace 2.0: Facial Behavior Analysis Toolkit Tadas Baltrušaitis, Amir Zadeh, Yao Chong Lim, and Louis-Philippe Morency, IEEE International Conference on Automatic Face and Gesture Recognition, 2018
