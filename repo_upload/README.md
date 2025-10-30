# CLIP + BLIP Video Captioning

**Short:** Multimodal pipeline that extracts frames from video, obtains CLIP embeddings for frame-text alignment, and generates captions using Salesforce BLIP.

**Main features**
- Frame extraction from video files using OpenCV / ffmpeg.
- CLIP for visual-text retrieval / embedding.
- BLIP for image/video caption generation.
- Designed as a Colab demo but structured for conversion to a reusable Python package.

**How to run**
1. Install dependencies: `pip install -r requirements.txt`
2. Open `notebooks/CLIP_BLIP_Video.ipynb` and run cells sequentially (or run `src/pipeline.py` if available).
3. Place a sample video in `assets/` and update the input path variable.

**Tech stack:** PyTorch, Transformers (Hugging Face), OpenCV, ffmpeg, PIL, numpy.

**Author:** OmarGira

