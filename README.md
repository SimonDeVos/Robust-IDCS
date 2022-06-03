# Robust IDCS

## Description
This is the code for the paper on "Robust Instance-Dependent Cost-Sensitive Classification".

Citation: [to be specified]

Contact the [author](https://www.kuleuven.be/wieiswie/nl/person/00148775) at simon.devos@kuleuven.be.

## Instructions
Run overview.py to execute the experiments as descibed in the paper. \
Settings in overview.py: \
    * set DIR variable to your custom result folder \
    * specify experimental configuration \
    * Default settings:  \
        5 fold cross-validation, 2 repeats \
        Toy example on synthetic data is displayed \
        Three classifiers are trained: logit, cslogit, r-cslogit \
        evaluators: traditional, AUC, Savings \

## Acknowledgments
The code for cslogit and csboost are Python versions of the [original cslogit by Sebastiaan Höppner et al.](https://github.com/SebastiaanHoppner/CostSensitiveLearning).
The Python version of cslogit was provided by [Lennert Van der Schraelen](https://www.kuleuven.be/wieiswie/nl/person/00132137).
A framework of the experiments was largely provided by [Toon Vanderschueren](https://www.kuleuven.be/wieiswie/nl/person/00140754).


