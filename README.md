# Face Swapping and Voice Cloning

This project leverages deep learning for face swapping using autoencoders and voice cloning with StarGAN. The goal is to create realistic transformations of facial features and voices, enabling seamless swaps across different inputs in both appearance and audio.

---

## Notebooks

### 1. `Split_voices.ipynb`
This notebook is used to:
- Extract audio from video files in WAV format.
- Split audio files into multiple segments.

#### Libraries Used:
- `wave`
- `math`
- `moviepy.editor`

### 2. `voices_preprocess.ipynb`
This notebook is used to:
- preprocess audio clips 
- Split audio files into chuncks based on silent periods

#### Libraries Used:
- `pydub`
- `scipy`

### 3. `stargan2vc.ipynb`
This notebook contains starGan model used for voice cloning

#### Libraries Used:
- `torch`
- `torchaudio`

### 4. `autoencoder.ipynb`
This notebook contains autoencoder model used for face swapping

#### Libraries Used:
- `dlib`
- `keras`
- `sklearn`
- `tensorflow`
