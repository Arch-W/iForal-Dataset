# iForal - Dataset

![Chars Badge](https://img.shields.io/endpoint?url=https://gist.githubusercontent.com/Arch-W/94e2fc8cbb4a71eeacfbb46672d6ff7f/raw/chars.json)
![Lines Badge](https://img.shields.io/endpoint?url=https://gist.githubusercontent.com/Arch-W/94e2fc8cbb4a71eeacfbb46672d6ff7f/raw/lines.json)
![Regions Badge](https://img.shields.io/endpoint?url=https://gist.githubusercontent.com/Arch-W/94e2fc8cbb4a71eeacfbb46672d6ff7f/raw/regions.json)


This dataset was designed for training machine learning models in the context of the [iForal project](https://iforal.hypotheses.org/), which focuses on transcribing medieval Portuguese texts, specifically forais (charters).
It includes images of medieval manuscripts, along with corresponding line-level transcription labels, to facilitate the development of models capable of recognizing and transcribing historical handwriting.

The dataset is ideal for OCR/HTR tasks and segmentation tasks within the domain of medieval document transcription.
It serves as a critical resource for advancing automated transcription tools for medieval texts, making historical archives more accessible.

The dataset is in PAGE XML format and was produced using the [eScriptorium](https://gitlab.com/scripta/escriptorium) platform.

This dataset includes 67 forais, but examples of newly added forais can be found [here](https://deti-iforal.ua.pt/documents).


## User Warning:

Please note that while the transcriptions provided in this dataset were made by specialists in the field of medieval Portuguese texts, the creation of the dataset—including the segmentation of lines and the assignment of transcriptions to the correct segments—was carried out mainly by a non-specialist in this type of document.

Even so, during the dataset construction process, some transcription errors were identified by the non-specialist and corrected.
However, user discretion is advised, especially when working with highly damaged or degraded documents, as some line-level segmentations may need further refinement.


## Contributions 

New contributions to this dataset, whether in the form of corrections or newly added forais, are welcome.
