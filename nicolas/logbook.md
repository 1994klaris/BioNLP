## 12/04
- Searched for tools used on coreference resolution i biomedical texts.
- Read paper https://www.aclweb.org/anthology/W18-2324.pdf to search for possible alternatives.
- Checked how to use of huggingface's neuralcoref
    - https://medium.com/huggingface/state-of-the-art-neural-coreference-resolution-for-chatbots-3302365dcf30
    - https://github.com/huggingface/neuralcoref
    - https://github.com/huggingface/neuralcoref/blob/master/neuralcoref/train/training.md
## 13/04
- Installed neuralcoref and pytorch
- Downloaded CRAFT corpora

## 22/04
- Setting up paper draft on overleaf.
- Checking how to train a new model with neuralcoref
    - https://medium.com/huggingface/how-to-train-a-neural-coreference-model-neuralcoref-2-7bb30c1abdfe
    - https://github.com/huggingface/neuralcoref/blob/master/neuralcoref/train/training.md
- Checking how to use craft with the format requirements for neuralcoref

## 29/04
- Fixing compile error and updating report.
- Installing Clojure Boot and checking how to convert the CRAFT corpus to CoNLL with it.
- Converting CRAFT corpus into CoNLL format and separating each file into its group by their ids.

## 05/05
- Solving problems with neuralcoref, installed from source.
- Problems parsing conll files, checking options on how to handle and adapt CRAFT to fit the expected format.
- Checking and comparing the CRAFT files with the instructions and with Ontonotes.

## 09/05
- Start adapting the conllparser.py file to handle .conll files instead of .*_conll.

## 10/05
- Adapted conllparser.py to handle the CRAFT corpus in .conll format.
- Realizing there's problems with tags spanning multiple utterances, and adapting the code to ignore those tags.
- Creating environment for training in Google Colab.