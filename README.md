🖼️ Image Captioning with Deep Learning | Flickr8k Dataset
This project implements an end-to-end image captioning system that combines Convolutional Neural Networks (CNNs) for image feature extraction and Recurrent Neural Networks (LSTMs) for generating natural language descriptions. The model is trained and evaluated on the Flickr8k dataset, which contains 8,000 real-world images, each annotated with five human-written captions.

🚀 Project Highlights
Utilizes EfficientNet-B7 as the visual encoder to extract robust 2560-dimensional image features.

Employs a 2-layer LSTM decoder to generate fluent and semantically relevant captions.

Implements custom preprocessing, including tokenization, vocabulary filtering, and sequence padding.

Trains the model using cross-entropy loss and the Adam optimizer with early stopping.

Evaluates captions using BLEU-1 to BLEU-4 metrics and visual inspection of generated results.

Compares traditional CNN+LSTM approach with a pretrained BLIP transformer model from Hugging Face for zero-shot captioning.

🛠️ Tech Stack
Python · PyTorch · NumPy · Pandas

Hugging Face Transformers · EfficientNet

Matplotlib · BLEU Evaluation · Jupyter Notebook

📁 Dataset
Flickr8k Dataset — 8,000 images with 5 captions each.

📊 Results
Training Loss reduced from 4.6 to ~2.1

Achieved 30–40% token-level validation accuracy

BLEU-1 Score: 0.21 | BLEU-4 Score: 0.023

📌 Future Work
Fine-tune transformer-based models on Flickr8k

Integrate beam search or top-k sampling for more diverse captions

Use larger datasets (e.g., MSCOCO) for improved generalization

