# Ali Daher

Master's student in Computer Science at the American University of Beirut. My background is
in machine learning, NLP, and GPU/high-performance computing, and through my master's I'm
moving toward ML systems (SysML), edge / on-device ML, and ML security — how models can be
run efficiently, close to where data is produced, and safely.

## Current focus

- ML systems: efficient training and inference, especially under limited compute
- Edge and on-device machine learning
- Security for machine learning systems

## Background and past work

- Natural language processing, especially Arabic NLP and post-OCR / text correction
- Fine-tuning and evaluating language models with limited resources (LoRA / QLoRA)
- GPU computing and high-performance parallel algorithms
- Applied machine learning on structured and biomedical data

## Featured projects

- **[Arabic Post-OCR Correction — Model Benchmark](https://github.com/aad4000/arabic-ocr-correction-benchmark)**
  Benchmarked five model families (AraFix, AraT5, Qwen, AraBERT, ByT5) on correcting errors
  in OCR'd Arabic text, on a shared held-out set. A fine-tuned AraFix model reached a
  character error rate of 0.065, clearly ahead of the rest.

- **[GPU Sparse Triangular Solve](https://github.com/aad4000/GPU_Computing_Project)**
  Four CUDA kernels for the sparse triangular solve, each optimizing the last through
  level-scheduling and caching, reaching a ~132× geometric-mean speedup over the CPU
  reference — top of the class benchmark for that milestone.

- **[Fall Detection from Human Pose](https://github.com/aad4000/fall-detection)**
  Real-time fall detection from video: OpenPose extracts body keypoints and a Random Forest
  classifies fall vs. no-fall (~94% accuracy) — a lightweight, edge-friendly design.

- **[Breast Cancer Type Classification](https://github.com/aad4000/breast_cancer_class)**
  Multi-class classification on the METABRIC clinical dataset with XGBoost (GPU-trained,
  tuned) and a neural-network baseline.

- **[Molecule Toxicity Classification](https://github.com/aad4000/Molecule_Toxicity_Classification)**
  Toxicity prediction on a small, imbalanced set of molecular descriptors, focused on
  feature selection and handling class imbalance with SMOTE.

## Tools I work with

- **Languages:** Python, C, CUDA, JavaScript
- **ML / NLP:** PyTorch, Hugging Face Transformers, XGBoost, scikit-learn, TensorFlow/Keras,
  QLoRA / Unsloth
- **Infrastructure:** AWS (Bedrock, Textract, RDS, ECS), PostgreSQL / pgvector, MySQL,
  Flask, Docker

## Education

- MSc in Computer Science, American University of Beirut — in progress
- BSc in Computer Science, American University of Beirut — Dean's Honor List (Fall 2024–2025)

## Contact

- Email: aad40@mail.aub.edu
- LinkedIn: <!-- add your LinkedIn URL -->
