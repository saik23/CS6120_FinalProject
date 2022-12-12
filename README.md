# SpanEmo
***

Source code for CS6120 final project 'Label Correlation Aware Emotion Classification.'
Re-uses code from the original implementation by the authors: https://github.com/hasanhuz/SpanEmo

## Dependencies
We used Kaggle to run the experiments. Made the Kaggle notebook public to evaluate the project.
Kaggle notebook link: https://www.kaggle.com/code/saikumarreddy01/spanemo

***

## Dataset

Dataset can be downloaded from the SemEval2018 official challenge site: https://competitions.codalab.org/competitions/17751#learn_the_details-datasets 
Place them in the appropriate location for the experiments.

***

## Training

Use the main code block for training.
- Modify the argument dictionary to change the hyper-parameters for training.
- Use P-100 GPU from the Kaggle notebook to run the experiments as GPU is necessary for training.

## Testing

We provide 4 different models for the project, trained with the following settings:
- SpanEmo model:  Reimplemented version of the paper model.
- Ablated model1: SpanEmo model trained only with BCE loss.
- Ablated model2: SpanEmo model trained only with LCA loss.
- SpanEmo model2: SpanEmo model trained with an alternative LCA loss implementation.