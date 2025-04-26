# Project10_bert-base-uncased

## Español
> Este fue el primer proyecto utilizando "transformers" para detección del lenguaje natural (en inglés en esta ocasión), Se comparó el crecimiento entre "accuracy" y "f1" en el entrenamiento de fine tunning del modelo y tokenizador "bert-base-uncased" sobre el dataset "glue". 

## English
> This was my first project using "transformers" library for NLP (Natural Lenguage Processing) tasks in english, it was compared the evolution between "accuracy" and "f1" in the fine-tuning using the tokenizer and model "bert-base-uncased" in the "glue" dataset.

## Descripción / Description
> - Es un proyecto para la comparación de métricas de medición al entrenar un modelo preentrenado como lo es "bert-base-uncased" usando el entrenamiento manual en 5 épocas de evaluación. 
> 
> - Se utilizó "transformers" como herramienta principal y el set de datos "Glue" que viene de `load_dataset from datasets`.
> 
> - Se Trabajó usando el tipo de evalación "clasificación de texto" usando Microsoft Research Paraphrase Corpus.
>  
> - Se entrenó a 5 épocas de entrenamiento totales.
> 
> - BatchSize de 8 datos usando "dataloader".
> 
> - Trabajamos con set de Validación y Entrenamiento Únicamente.

> -------------------

> - Is a project to compare metrics in a pretrained model like "bert-base-uncased" using manual training with 5 evaluate epochs.
> 
> - Using transformers as main tool and the "Glue" dataset that you can find on `load_dataset from datasets`.
> 
> - Worked with "text clasification" using the Microsoft Research Paraphrase Corpus.
> 
> - 5 total train epochs.
>
> - BatchSize = 8 using "dataloader"
>
> - Worked with test and valid split.

## Tecnologías usadas / Used Technologies
- Python (main)
- PyTorch
- Google Colab / Jupyter NoteBook
- Datasets
- Transformers
- Accelerate
- Evaluate
- Matplotlib.pyplot
- tqdm

## Final Results / Resultados Finales

        Epoch: 1 -> Accuracy: 0.8112745098039216, F1: 0.8752025931928687
        --------------------------------------------------------------------------------
        Epoch: 2 -> Accuracy: 0.8357843137254902, F1: 0.8814159292035398
        --------------------------------------------------------------------------------
        Epoch: 3 -> Accuracy: 0.8406862745098039, F1: 0.8900169204737732
        --------------------------------------------------------------------------------
        Epoch: 4 -> Accuracy: 0.8504901960784313, F1: 0.8957264957264958
        --------------------------------------------------------------------------------
        Epoch: 5 -> Accuracy: 0.8406862745098039, F1: 0.8896434634974533

