# Livrable STAGE 

This directory contains the implementation of the easy_nlp pipeline applied to the field of crisis and psychology.

To use the pipeline, you have to install the package easy_nlp

```bash
$ git clone https://github.com/Moumeneb1/IRIT_INTERNSHIP.git
$ pip install IRIT_INTERNSHIP/
```

```
.
├── ...
├── Crisis
│   ├── Bert_Base.ipynb
│   ├── Flaubert_base.ipynb
│   ├── Camembert_base.ipynb
│   ├── Bert+features.ipynb
│   ├── Flaubert+Features.ipynb
│   ├── Flaubert_base_adapted.ipynb
│   ├── Bert_CrisisNLP.ipynb
│   ├── Flaubert_LSTM.ipynb
│   ├── Flaubert_CNN.ipynb
│   ├── Bert Multitask.ipynb
│   ├── Flaubert_Multitask.ipynb 
|   └── Flaubert_base+ Focal Loss.ipynb
├── Psycho
│   ├── Bert_Base.ipynb
│   ├── Flaubert_LSTM.ipynb
|   └── Flaubert_Multitask.ipynb
└── ...
```



## EcologyCrisis 

These results showcase some of the models used on the RANDOM-SAMPLING CONFIGURATION  

| Model                                | Binary | Three class | Multiclass |
|--------------------------------------|--------|-------------|------------|
| [Bert_base](/crisis/Bert_Base.ipynb) | 0.824    | 0.742          | 0.586       |
| [Flaubert_base](/crisis/Flaubert_base.ipynb) | 0.841    |  0.765       |  0.617      |
| [Camembert_base](/crisis/Camembert_base.ipynb) | 0.812    | 0.7427       | 0.5587       |
| [Flaubert+Features](/crisis/Bert_Base.ipynb) | 0.834   |0.834       | 0.613        |
| [Flaubert_base_adapted](/crisis/Flaubert_base_adapted.ipynb) | __0.853__   | 0.767         |0.654       |
| [Bert_CrisisNLP](/crisis/Bert_CrisisNLP.ipynb) | 0.822   | 0.742       | 0.591       |
| [Flaubert_LSTM.ipynb](/crisis/Flaubert_LSTM.ipynb) | 0.848    | 0.7637         | __0.6713__      |
| [Flaubert_CNN.ipynb](/crisis/[Flaubert_CNN.ipynb) | 0.8515    | 0.7656         | 0.6654      |
| [Flaubert_Multitask.ipynb ](/crisis/[Flaubert_Multitask.ipynb) | 0.847    | 0.769        | 0.625       |
| [Flaubert_base+ Focal Loss.ipynb](/crisisFlaubert_base+FocalLoss.ipynb) | 0.853   | __0.7804__     | 0.66       |


## Psycho 
These results showcase the results of using these models on the psycho corpus


| Model                                | Binary | Three class |
|--------------------------------------|--------|-------------|
| [Bert_base](/crisis/Bert_Base.ipynb) | 0.7096           | 0.5610       |
| [Flaubert_LSTM](/crisis/Flaubert_LSTM.ipynb) | 0.7836   | 0.6972        |
| [Flaubert_Multitask](/crisis/Flaubert_Multitask.ipynb) | 0.7607          | 0.6972         |


You can find the adapted Language models weights on these links : 

- [flaubert_base_cased_psycho]()
- [bert_base_multilingual_cased_psycho](https://drive.google.com/file/d/1L2JMjOEByZ0nbE2urYeziLtzHlFGLN_d/view?usp=sharing)
- [flaubert_base_cased_crisis](https://drive.google.com/file/d/1akx2kbtFv25o3kJLChDrosMhM4j6dx7M/view?usp=sharing)
- [bert_base_multilingual_cased_crisis]()
