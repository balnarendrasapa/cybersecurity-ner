# Named-Entity-Recognition for Cybersecurity

<a href="https://colab.research.google.com/github/balnarendrasapa/cybersecurity-ner/blob/master/Fine_tune_for_Cybersecurity_NER.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

- This project is about building a NLP model that can be used for Named-Entity-Recognition in the field of Cybersecurity.
- MITRE Dataset is taken to train the model. The dataset is available in this repository as `MITRE.zip`. or Click [here](https://github.com/balnarendrasapa/cybersecurity-ner/raw/readme/MITRE.zip) to download the dataset.
- `distilbert-base-uncased` pretrained model was used in this project. This model is fine-tuned for this project's purpose.
- To open the project, Click on the above google colab badge.

## Metrics

![image](https://github.com/balnarendrasapa/cybersecurity-ner/assets/61614290/ba74fb6c-1348-4d02-951d-2a01a5a018c8)

## Huggingface

- The finetuned model is available on the huggingface. click [here](https://huggingface.co/bnsapa/cybersecurity-ner) to go there.


## Example

I typed `abcde is a computer malware`. I defined the context such that it implies `abcde` is virus and model is able to capture that.

![image](https://github.com/balnarendrasapa/cybersecurity-ner/assets/61614290/b97a37c8-a4d3-464f-a48b-a6adb21dced8)


