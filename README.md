# Glitches In Christmas

Final project for the Building AI course

## Summary

**Glitches In Christmas** is a creative and technical AI project exploring voice modeling and anomaly detection in AI-generated cover songs. It builds a machine learning algorithm to detect audio anomalies (or "glitches") in synthetic vocals — an important step toward identifying deepfake audio based on signal features.

---

## Background

AI-generated voice is powerful and increasingly accessible, but comes with risks of misuse (e.g., deepfakes) and technical limitations like artifacts or "glitches" in synthesized audio. As AI cover songs grow in popularity, detecting such glitches becomes critical for artists and engineers alike.

This project was inspired by:
* The rise of open-source AI voice tools (e.g., RVC)
* Artistic experimentation with AI-generated music
* A technical need for quality control in audio post-production

---

## How is it used?

This project has three parts:
1. **AI-cover album creation** using voice conversion of an original, open-licensed Christmas album.
2. **Demonstration of RVC voice modeling**, showing before-and-after samples of AI-transformed vocals.
3. **Anomaly detection** via a machine learning model to locate "glitches" in audio tracks, implemented in a Jupyter Notebook.

Users:
- Artists experimenting with AI voices
- Audio engineers seeking automated glitch detection
- Researchers in generative AI audio

Live performance and visual examples included:

<img src="images/live_performance.png" width="300">
<i>AI-generated: SD1.5 visual prompt of expressive AI opera singer performing live at a Christmas gala</i>

🎵 **Download the AI-cover album:**  
[🚨 Download the AI-Cover Album Here 🚨](https://drive.google.com/drive/folders/1-0rqw0uwNj_NsFwUVW3V5c0Ss5aeIsIx?usp=sharing)

---

## Data sources and AI methods

**Data:**
- Vocal training clips and converted vocals from the album "2024 Lopker Christmas Songs" (licensed under CC BY)
- AI-generated cover songs used as test material
- Annotated glitch segments for training/testing

**AI Techniques:**
- RVC (Retraining Voice Conversion)
- Anomaly detection with supervised ML (Jupyter notebook provided)
- Feature extraction from vocal tracks using audio signal processing (e.g., spectral flux, zero-crossing rate)

**Try it yourself:**  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mwtuni/glitches-in-christmas/blob/main/glitch_detector.ipynb)

---

## Challenges

- Real-world AI vocals often contain subtle and unpredictable glitches
- Annotation of glitch regions is time-consuming and subjective
- RVC and generative audio models are still rapidly evolving and may change format or quality

**Ethical Considerations:**
- Clear labeling of AI-generated content
- Avoiding misuse in deepfake impersonation

---

## What next?

- Expand the glitch detection model with a larger dataset and more granular labels
- Collaborate with other creators to benchmark and improve model generalizability
- Add real-time audio preview and glitch heatmaps in a visual tool
- Explore broader applications like speech synthesis quality control

---

## Acknowledgments

* AI voice modeling: RVC project contributors (open-source)
* Original album by [John Lopker – 2024 Lopker Christmas Songs](https://freemusicarchive.org/music/john-lopker/2024-lopker-christmas-songs) / [CC BY](https://creativecommons.org/licenses/by/4.0/)
* Stable Diffusion (for visuals)
* Elements of AI course by University of Helsinki & Reaktor

---

## Bonus: RVC Demonstration Samples

1. **Original Vocal** ([Listen](data/rvc_example/1-original_vocal.wav))  
2. **Training Material** ([Listen](data/rvc_example/2-training_material.wav))  
3. **Generated Vocal** ([Listen](data/rvc_example/3_generated_vocal.wav))  

---

![Christmas Album](images/2024_Lopker_Christmas_Songs.PNG)
