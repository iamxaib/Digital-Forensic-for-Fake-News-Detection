Digital Forensic for Fake News Detection

This repository presents a digital forensics framework for fake news detection and traceability. The proposed system integrates text preprocessing, semantic feature representation using Word2Vec with Gensim, deep learning classification with an LSTM network, and a lightweight blockchain layer to securely preserve and trace misinformation evidence. The framework not only classifies news articles but also ensures tamper-proof provenance tracking, supporting forensic investigations and trustworthy digital ecosystems.

Key Features

End-to-end fake news detection pipeline
Core text preprocessing and normalization
Semantic embeddings using Word2Vec (Gensim)
Tokenization and padding with Keras
LSTM-based fake news classifier
Blockchain-based evidence storage
Cryptographic hash-based integrity verification
Performance evaluation using standard metrics


Framework Workflow

The proposed framework follows these steps:
1. Data loading and cleaning
2. Text preprocessing pipeline
3. Word2Vec embedding training (Gensim)
4. Tokenization and sequence padding
5. Embedding matrix construction
6. LSTM-based classification
7. Fake news identification
8. Blockchain registration for traceability
9. Blockchain integrity verification

Dataset

The system is evaluated using the ISOT Fake News Dataset, consisting of:
Fake news articles from unreliable sources
Real news articles from Reuters
This dataset is used for supervised learning and forensic validation.

Technologies Used

Python
TensorFlow / Keras
Gensim
Pandas
NumPy
Scikit-learn
Custom blockchain implementation

Model Architecture

The fake news detection model consists of:
Embedding Layer initialized with pretrained Word2Vec vectors
LSTM Layer (128 units)
Dense Output Layer with sigmoid activation

How to Run

1. Clone the repository
git clone https://github.com/yourusername/Digital-Forensic-for-Fake-News-Detection.git
2. Install dependencies
pip install -r requirements.txt
3. Run the framework
python main.py
4. Review classification results and blockchain logs.

Blockchain Traceability

For each detected fake article, the system:
Generates a cryptographic SHA-256 hash
Stores metadata and classification results
Links blocks using previous hashes
Verifies blockchain integrity

Experimental Setup

Pretrained Word2Vec embeddings
Fixed sequence length padding
AdamW optimizer
Binary cross-entropy loss
Validation split during training

Results

The proposed framework achieves strong detection performance on the ISOT dataset while maintaining secure blockchain-backed traceability. The results demonstrate that combining semantic representation with immutable evidence storage enhances digital forensic reliability.


👤 Author

Aurangzaib Bhatti
PhD Researcher - Digital Forensics


License

This project is intended for research and educational purposes.
