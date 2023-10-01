# Empowering the Fact-Checkers: Claim Span Detection with Large Language Models
We fine-tuned encoder and encoder-decoder large language models to automatically extract spans of text representing claims in Twitter posts.

The models we tested include the following:
- Encoder models: DaBERTa, BERT, DistilBERT, BERT+LSTM
- Encoder-Decoder Models: T5, BART

BERT, DaBERTa, and DistilBERT achieved state-of-the-art performance for this task and this dataset.

The encoder-decoder models performed reasonably well, but they were inferior to the encoder models due to the suboptimal text-to-text restructuring of the claim span detection task.

See report.pdf for a detailed discussion of the task, methods, results, and Analysis.

### data
Contains the original data for the task, as well as modified datasets that were used along the way.

### latex-files
Contains the latex files used to write report.pdf.

### intro-video
Contains a video that introduces and describes the claim span detection task.

### preprocess, T5, LSTM, GPT-2, BERT, BART
Contains the implementation files used to fine-tune the large-language models to perform automatic claim span detection.
