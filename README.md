# CDS6344-SOCIAL-MEDIA-COMPUTING
project for sentiment analysis of English song lyrics using traditional ML and BERT-based models.

## Dataset
This project uses the English Song Lyrics Dataset from Kaggle: https://www.kaggle.com/datasets/deepshah16/song-lyrics-dataset

## Word Embedding
This project uses pre-trained GloVe vectors for word embeddings.
Download link: https://nlp.stanford.edu/data/glove.6B.zip  
Please download and extract `glove.6B.50d.txt`, then place it into the `glove_files/` folder before running the notebook.

## Future Work
To improve and extend this project, several future directions are proposed:
- **Expand the dataset**: Include lyrics from female artists, multilingual songs, and various music genres to increase model robustness and generalizability.
- **Experiment with advanced or ensemble models**: Explore larger architectures such as RoBERTa-large or XLNet, or hybrid models combining BiLSTM with transformers (e.g., BERT + BiLSTM) to enhance accuracy and stability.
- **Enhance emotion granularity**: Go beyond basic positive/neutral/negative categories by introducing sub-classes such as joyful, melancholic, or angry, or apply multi-label emotion tagging.
- **Improve sentiment labeling**: Incorporate hybrid labeling strategies that blend rule-based methods like VADER with machine learning classification to create more accurate sentiment tags.
This foundation opens up exciting possibilities for more nuanced analysis of musical sentiment using modern NLP techniques.
