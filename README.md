# Dynamic World Model Runner

[![DOI](https://zenodo.org/badge/413957377.svg)](https://zenodo.org/badge/latestdoi/413957377)

Model files and example notebook for Dynamic World, see
https://doi.org/10.1038/s41597-022-01307-4.

***This is not an officially supported Google product.***

-   [TensorFlow SavedModels](https://www.tensorflow.org/guide/saved_model) for
    the forward and backward path can be found in `./model/forward` and
    `./model/backward` respectively.
-   `./single_image_runner.ipynb` gives a step-by-step guide to making
    predictions with the Dynamic World models.

See the image below for the model block diagram. For Dynamic World, `m = 1.5`
and `b = 2`.

![Dynamic World neural network architecture](https://raw.github.com/google/dynamicworld/master/dw_model_arch.png)
