# Project10_bert-base-uncased

## Español
> Este fue el primer proyecto utilizando "transformers" para detección del lenguaje natural (en inglés en esta ocasión), Se comparó el crecimiento entre "accuracy" y "f1" en el entrenamiento de fine tunning del modelo y tokenizador "bert-base-uncased" sobre el dataset "glue". 

## English
> In this project i used a Simple NN with 102 output layers (categories) for a multinomial classification but with "Transfer Learning" of the "IMAGENET1K_V2" model that was pretrained for image classification.

## Descripción / Description
> - Es un proyecto para la comparación de métricas de medición al entrenar un modelo preentrenado como lo es "bert-base-uncased" usando el entrenamiento manual en 5 épocas de evaluación. 
> 
> - Se utilizó PyTorch como herramienta principal y el set de datos "Glue" que viene de `load_dataset from datasets`.
> 
> - Se Trabajó usando el tipo de evalación "clasificación de texto" usando Microsoft Research Paraphrase Corpus.
>  
> - Se entrenó a 5 épocas de entrenamiento totales.
> 
> - BatchSize de 8 datos usando "dataloader".
> 
> - Trabajamos con set de Validación y Entrenamiento Únicamente.

> -------------------

> - This is a computer vision project using torch.cuda to manually accelerate the training loop. This project is to compare the accuracy between "Fine Tuning" and "Feature Extraction" in a 102 different output categories.
> 
> - Using PyTorch as main tool and the "Flowers102" dataset that you can find on `torchvision.datasets`.
> 
> - Worked with 5 different layers of Data Augmentation and the normalize layer.
> 
> - EarlyStopping was used with 7 patience epochs.
> 
> - 50 total epochs for both models.
>
> - BatchSize = 32
>
> - Worked with train, test and valid split.

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

        Epoch: 1 -> Accuracy: 0.8112745098039216, F1: 0.8560747663551402
        --------------------------------------------------------------------------------
        Epoch: 2 -> Accuracy: 0.8651960784313726, F1: 0.9033391915641477
        --------------------------------------------------------------------------------
        Epoch: 3 -> Accuracy: 0.8504901960784313, F1: 0.8988391376451078
        --------------------------------------------------------------------------------
        Epoch: 4 -> Accuracy: 0.8602941176470589, F1: 0.8994708994708994
        --------------------------------------------------------------------------------
        Epoch: 5 -> Accuracy: 0.8676470588235294, F1: 0.9055944055944056

