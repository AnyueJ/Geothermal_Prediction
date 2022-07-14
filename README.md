# Recurrent Neural Networks for Short-term and Long-term Prediction of Geothermal Reservoirs
Accurate prediction of geothermal reservoir responses to alternative energy production scenarios is critical for optimizing the development of the underlying resources. Besides the conventional physics-based models that offer a comprehensive prediction tool, Data-driven models provide an efficient alternative to build predictive models by extracting and using the statistical patterns in data to make predictions. In particular, recurrent neural networks (RNN) are data-driven models that are commonly applied to predict time series sequences. This paper presents a variant of RNN that also utilizes the efficiency of convolutional neural network (CNN) for the prediction of energy production from geothermal reservoirs. Specifically, a CNN-RNN architecture is developed that takes historical production data and future well controls to predict the well quantities that describe the production performance of the reservoir. The model is paired with a labeling scheme to handle real field disturbances such as data gaps. In additional to the model structure, we also introduce a thorough workflow of applying the model, which includes data pre-processing, feature selection, different training strategies for short-term and long-term prediction. The performance and accuracy are evaluated by applying it to multiple datasets, including a field reservoir model. 

<p align="center">
<img src="https://github.com/AnyueJ/Geothermal_Prediction/blob/main/Image/CNNRNNModel.png" width="722" height="440">
</p>

## Prerequisites
Python 3.8.8

Tensorflow 2.3.0

## Data
Due to the data confidentiality, we are not allowed to share the field examples that were used in our paper. Only the synthetic examples are available in this repo

## Citation
@article{jiang2022recurrent,
  title={Recurrent neural networks for short-term and long-term prediction of geothermal reservoirs},
  author={Jiang, Anyue and Qin, Zhen and Faulder, Dave and Cladouhos, Trenton T and Jafarpour, Behnam},
  journal={Geothermics},
  volume={104},
  pages={102439},
  year={2022},
  publisher={Elsevier}
}

## Acknowledgments
This material is based upon work supported by the U.S. Department of Energy's Office of Energy Efficiency and Renewable Energy (EERE) under the Geothermal Technologies Office award number DE-EE0008765. The authors acknowledge the Energi Simulation support of the Center for Reservoir Characterization and Forecasting at USC.
