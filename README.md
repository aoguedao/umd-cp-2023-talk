# A review and application of Disease Informed Neural Networks for efficient parameter estimation

## Mathematical Biology Seminar - University of Maryland, College Park

 In this talk we will introduce a novel parameter estimation approach called Disease Informed Neural Networks (DINNs) that can help to predict the dynamics of infectious diseases. This approach builds on Physics-Informed Neural Networks (PINNs) that have been applied successfully to a variety of applications that can be modeled by linear and non-linear ordinary and partial differential equations. Specifically, this talk will provide a review of DINNs applied to compartmental models in epidemiology with an overview of neural networks capable of learning how diseases spread, forecasting their progression, and finding their unique parameters. Specifically, we will apply our DINNs approach to mathematical models that incorporate transportation between populations and their impact on the dynamics of infectious diseases. We show how these approaches are capable of predicting the behavior of a disease described by governing differential equations that include parameters and variables associated with the movement of the population between neighboring cities. We show that our model validates real data and also how such DINNs based methods predict optimal parameters for given datasets.

[Link](https://www-math.umd.edu/research/seminars/math-biology.html#view-abstract-18)

## Lessons

| Lesson                             | Notebook             |
| :-------------------------------- | :-------------------: |
| SIRD | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aoguedao/umd-cp-2023-talk/blob/main/notebooks/sird.ipynb) |
| SIRD Transport No Prior Knowledge| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aoguedao/umd-cp-2023-talk/blob/main/notebooks/sird_transport_no_prior_knowledge.ipynb) |
| SIRD Transport| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aoguedao/umd-cp-2023-talk/blob/main/notebooks/sird_transport.ipynb) |
| SIRD Transport Noisy Data | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aoguedao/umd-cp-2023-talk/blob/main/notebooks/sird_transport_noise.ipynb) |
| SIRD Transport Missing Data| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aoguedao/umd-cp-2023-talk/blob/main/notebooks/sird_transport_missing.ipynb) |
| SIRD Transport and Cross Transmission | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aoguedao/umd-cp-2023-talk/blob/main/notebooks/sird_transport_cross.ipynb) |


## Remarks
- If you are working on Google Colab you need to install `DeepXDE` and enable GPU.
    1. Run `!pip install deepxde` at the beginning of each notebook 
    2. Go to Menu `Menu > Runtime > Change Runtime` and change hardware accelaration to __GPU__.
- If you are working on your own machine, please follow the [install and setup documentation](https://deepxde.readthedocs.io/en/latest/user/installation.html).
