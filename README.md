# climate-change-misinformation
A proof-of-concept for using transformers with a textual entailment task to determine the validity of claims made about climate change.

## contents

* 0-process-data.ipynb: Convert the HuggingFace Climate FEVER dataset to correct format for text entailment task
* 1-climate-bert.ipynb: Fine-tune the ClimateBERT model on text entailment using the Climate FEVER dataset
* 2-model-inference.ipynb: Example of how to use the model for inference

## huggingface space

Check out a detailed explanation of this project + an interactive example using [huggingface spaces](https://huggingface.co/spaces/amandakonet/climate-change-misinformation)!
