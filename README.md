# 🍃 Frugal AI Challenge

**Machine Learning challenge to build models that are not only performant, but also efficient in terms of memory and electricity consumption**

This challenge took part in January 2025 and proposed three tasks related to the environment: text classification, object detection and audio classification.

More information on the [dedicated page](https://frugalaichallenge.org/)

## 📵 Detecting climate disinformation

8-labels classification problem to detect disinformation in various text sources.

- Proposed model: Recurrent Neural Network (RNN) with GloVe embedding
- Performance: WIP
- Resources consumption: WIP

[Dataset](https://huggingface.co/datasets/QuotaClimat/frugalaichallenge-text-train) - [Go to this task](./text-classification)

## 🪓 Detecting illegal deforestation

Binary classification problem on audio data to detect the presence of chainsaws in forests and natural environments, indicating potential illegal logging activities.

- Proposed model: 1D convolutional neural network with residual connections
- Performance: 75% accuracy
- Resources consumption: WIP

[Dataset](https://huggingface.co/datasets/rfcx/frugalai) - [Go to this task](./audio-classification)

## 🔥 Classifying regions at risk of wildfires

Detect smoke in photographs of forests, mountains... using bounding boxes.

- Proposed model: YOLO image classifier
- Performance: WIP
- Resources consumption: WIP

[Dataset](https://huggingface.co/datasets/pyronear/pyro-sdis) - [Go to this task](./smoke-detection)

