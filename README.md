# Sample scripts for exported models from Custom Vision Service.

This repository contains samples scripts to use exported models from [Custom Vision Service](https://customvision.ai).


| Language | Model type | Link |
| -------- | -------- | ---- |
| Javascript | TensorFlow.js | [README](samples/javascript/tensorflowjs) |
| Python   | ONNX     | [README](samples/python/onnx) |
| Python   | OpenVino | [README](samples/python/openvino) |
| Python   | TensorFlow (Frozen Graph) | [README](samples/python/tensorflow) |
| Python   | TensorFlow Lite | [README](samples/python/tensorflow_lite) |


## How to export a model from Custom Vision Service?
Please see this [document](https://docs.microsoft.com/en-us/azure/cognitive-services/custom-vision-service/export-your-model).


## Notes
Those sample scripts are not aiming to get identical results with Custom Vision's prediction APIs. There are slight differences in the pre-processing logic, which cause small difference in the inference results.


## Resources
* [Custom Vision Service documents](https://docs.microsoft.com/en-us/azure/cognitive-services/custom-vision-service/)

