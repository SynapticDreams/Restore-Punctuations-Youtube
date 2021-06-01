# Restore-Punctuations

Output of Speech-to-Text(STT) Model is not punctuated, so it's increases the complexity of readability. If we want to use output text from STT Model for Analysis using Language Models like BERT, RoBERTa, XLNet, DistilBERT, etc. Then we should restore punctuations in text in order to improve the langauge model performance.

I have used youtube_transcript_api library to extract Manual/Auto-generated trascripts. For Manual Transcripts punctuations are added by default otherwise extarct auto-generated transcripts and apply punctuations model.

Download pretrained punctuator2 model from GitHub repo.


****References**
https://github.com/jdepoix/youtube-transcript-api
https://github.com/ottokart/punctuator2
