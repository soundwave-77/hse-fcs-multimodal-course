## Week 01 - Multimodality Basics

### Lecture 1: Introduction to Multimodal Neural Networks

Lecture gives a high-level introduction to multimodal neural networks: what "modality" means in psychology and machine learning, which data types are commonly used, and why combining them improves generalization and model unification.

### Seminar 1: Audio Preprocessing & CLIP Warm-up

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/AlbinaBurlova/hse-fcs-multimodal-course/blob/main/w01_mm_basics/sem1_introduction_to_multimodal.ipynb
)

Seminar notebook is a short warm-up with audio and vision–language tools: a WAV file is loaded from Google Drive, resampled to 16 kHz and trimmed with `librosa`, then a CLIP demo on cat images from Unsplash uses `CLIPModel` / `CLIPProcessor` to compute image–caption similarities and inspect simple zero-shot predictions.

### References and materials

- Visual Storytelling (VIST) Dataset — <https://visionandlanguage.net/VIST/>  
- Visual Question Answering (VQA) Dataset — <https://visualqa.org>  
- LAION-5B Dataset — <https://laion.ai/blog/laion-5b/>  
- VGG-Sound Dataset — <https://www.robots.ox.ac.uk/~vgg/data/vggsound/>  
- RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song) — <https://zenodo.org/records/1188976>  
- Audio-Visual Identity Database (AVID) — <https://www.avid.wiki/Main_Page>  
- RECOLA Database — <https://diuf.unifr.ch/main/diva/recola/>  
- IEMOCAP Dataset — <https://sail.usc.edu/iemocap/>  
- MMMU Benchmark — <https://mmmu-benchmark.github.io>  
- Recent survey on multimodal benchmarks — <https://arxiv.org/abs/2408.08632>  
- Radford et al., *Learning Transferable Visual Models From Natural Language Supervision (CLIP)* — <https://arxiv.org/abs/2103.00020>  
- Hugging Face Transformers — CLIPModel & CLIPProcessor docs: <https://huggingface.co/docs/transformers/model_doc/clip>  
- librosa documentation — <https://librosa.org/doc/latest/>  
- PySoundFile (soundfile) documentation — <https://pysoundfile.readthedocs.io/>
