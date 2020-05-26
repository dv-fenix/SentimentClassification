# Sentiment Classification
Fine-tuning a BERT model (Huggingface API) for Sentiment Classification on the SMILE: Twitter Emotion Dataset

## System Information [Trained Using Colab]
- torch : 1.5.0
- pandas : 1.0.3
- numpy : 1.18.4

## Results
- F1 Score (Weighted) : 0.853
- Accuracy Per Class (See Notebook)
- Training time : 90 seconds per Epoch (approximately)

## References
- [Huggingface API](https://huggingface.co/transformers/model_doc/bert.html#)
- Jay Alammar's [The Illustrated BERT](http://jalammar.github.io/illustrated-bert/)
- [A Gentle Visual Intro to Data Analysis in Python Using Pandas](http://jalammar.github.io/gentle-visual-intro-to-data-analysis-python-pandas/)
- [SMILE Twitter Emotion Dataset](https://doi.org/10.6084/m9.figshare.3187909.v2)
- [Classification Accuracy is Not Enough](https://machinelearningmastery.com/classification-accuracy-is-not-enough-more-performance-measures-you-can-use/)
