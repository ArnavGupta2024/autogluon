# AutoGluon

AutoGluon automates machine learning tasks enabling you to easily achieve strong predictive performance in your applications. With just a few lines of code, you can train and deploy high-accuracy machine learning and deep learning models on image, text, time series, and tabular data.

### Installing AutoGluon
```python
!pip install -U pip
!pip install -U setuptools wheel
!pip install -U "mxnet<2.0.0" bokeh==2.0.1
!pip install autogluon --no-cache-dir
# Without --no-cache-dir, smaller aws instances may have trouble installing
```

### AutoGluon Tasks
* Tabular
* Time Series
* Multimodal

### Datasets Used
[Bike Sharing Demand](https://www.kaggle.com/competitions/bike-sharing-demand/data)

> Task - To predict the total count of bikes rented during each hour covered by the test set, using only information available prior to the rental period

[House Hold Energy - Time Series](https://www.kaggle.com/datasets/jaganadhg/house-hold-energy-data)

> Task - To predict energy consumption


### Resources

* [Installing AutoGluon](https://auto.gluon.ai/dev/install.html)
* [AutoGluon Tabular](https://auto.gluon.ai/dev/tutorials/tabular/index.html)
* [AutoGluon TimeSeries](https://auto.gluon.ai/dev/tutorials/timeseries/index.html)
* [Hyperparameter Optimization](https://auto.gluon.ai/dev/tutorials/multimodal/advanced_topics/hyperparameter_optimization.html)

