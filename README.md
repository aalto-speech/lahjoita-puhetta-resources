# Lahjoita puhetta resources
A collection of resources related to the Lahjoita puhetta speech corpus. Described in the paper [Lahjoita puhetta: a large-scale corpus of spoken Finnish with some benchmarks](https://doi.org/10.1007/s10579-022-09606-3)

## The corpus on Kielipankki
- [Download the corpus](https://www.kielipankki.fi/corpora/puhelahjat/)
- [More information about the Lahjoita puhetta campaign](https://www.kielipankki.fi/lahjoita-puhetta/)

## Hybrid HMM/DNN ASR system
Hybrid HMM/DNN ASR system built with Kaldi, and language models:
- [Training scripts](https://github.com/aalto-speech/lahjoita-puhetta-baseline-kaldi)
- [Downloadable trained models](https://zenodo.org/record/7101543)

## Hybrid, semisupervised HMM/DNN ASR system
Semisupervised HMM/DNN ASR system built with Kaldi using 100h of transcribed and 1600h of untranscribed data:
- [Training scripts](https://github.com/aalto-speech/lahjoita-puhetta-baseline-kaldi)
- [Downloadable trained model](https://zenodo.org/record/6545290#.Yn4MblTP1PY)

## AED recipe
The SpeechBrain AED recipe can be found here:
https://github.com/aalto-speech/speechbrain-lahjoita-puhetta-baseline

Even if you're not familiar with SpeechBrain, the hyperparams/Full-B-50s.yaml hyperparameter file should be relatively easy to read, if you're interested in specific hyperparameter choices.

## Wav2Vec2 fine-tuned with CTC
- [Lahjoita puhetta Wav2Vec2 recipe](https://github.com/aalto-speech/lahjoita-puhetta-baseline-wav2vec2)
- [Downloadable trained model](https://zenodo.org/record/6530799#.YnzxTFxBwUE)


## Metadata classification
- [Lahjoita puhetta metadata classification](https://github.com/aalto-speech/lahjoita-puhetta-metadata-classification)
- [Lahjoita puhetta metadata classification trained models](https://zenodo.org/record/6545342#.Yn4UPZNBxBw)
