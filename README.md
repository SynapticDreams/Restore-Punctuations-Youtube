# Restore-Punctuations

Output of Speech-to-Text(STT) Model is not punctuated, so it's increases the complexity of readability and if we want to use output text from STT Model for Analysis using Language Models like BERT, RoBERTa, XLNet, DistilBERT, etc. Then we should restore punctuations in text in order to improve the langauge model performances.

I have used youtube_transcript_api library to extract Manual/Auto-generated trascripts. For Manual Transcripts punctuations are added by default otherwise extarct auto-generated transcripts and apply punctuations model.

Download pretrained punctuator2 model from GitHub repo.


## Usage:

<a href="https://colab.research.google.com/github/SynapticDreams/Restore-Punctuations-Youtube/blob/main/transcripts_punctuator2.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

****References**
https://github.com/jdepoix/youtube-transcript-api
https://github.com/ottokart/punctuator2
