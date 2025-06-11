# AkaiSpace_AIInternshipAssignmant
 
# Video Captioning with BLIP (Vision-Language Model)

This project demonstrates an AI pipeline that generates natural language captions from videos using a Vision-Language Model. It is part of a selection process to evaluate skills in AI development, data labeling, and creative problem-solving.

---

## What It Does

- Extracts the middle frame from each input video
- Uses the [BLIP model](https://huggingface.co/Salesforce/blip-image-captioning-base) to generate an English caption describing the frame
- Outputs all generated captions into a structured `.txt` file

---

## Project Structure

MyDrive/
├── caption_videos_colab.ipynb # Main Google Colab notebook

├── captions_output_sample.txt # Captions generated for 10 videos

├── README.md # This file

└── video_samples/ # Folder to store video files (not uploaded)

---

## Tools & Libraries Used

- Python 
- Google Colab
- OpenCV (video processing)
- HuggingFace Transformers (`Salesforce/blip-image-captioning-base`)
- PyTorch (model inference)
- PIL (image handling)

