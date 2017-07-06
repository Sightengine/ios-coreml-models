# CoreML Models for iOS, macOS, watchOS and tvOS

## About
Mobile-ready, high-performance machine learning models that you can download and import into your application. All models make use of Apple's CoreML framework.

## Usage
The models can be dragged and dropped directly into the Resources Group in your project's Project Navigator. [See this tutorial](https://www.raywenderlich.com/164213/coreml-and-vision-machine-learning-in-ios-11-tutorial) for more details on the integration.

## General Object Detection

Detect the dominant objects present in an image from a set of 1000 general categories such as trees, animals, food, vehicles, people, and more.

| Model name | Top 5 error | Size | Link
| SqueezeNet | ˜15% | 4.7Mb |  [Download Model](https://docs-assets.developer.apple.com/coreml/models/SqueezeNet.mlmodel)
| ResNet50 | 7.8% | 102.6Mb | [Download Model](https://docs-assets.developer.apple.com/coreml/models/Resnet50.mlmodel)
| Inception v3 | 5.6% | 94.7Mb | [Download Model](https://docs-assets.developer.apple.com/coreml/models/Inceptionv3.mlmodel)
| VGG16 | 7.4% | 553.5Mb | [Download Model](https://docs-assets.developer.apple.com/coreml/models/VGG16.mlmodel)

## General Scene Detection

Detect the scene of an image from general categories such as an airport terminal, bedroom, forest, coast, and more.

| Model name | Size | Link
| Places205-GoogLeNet | 24.8Mb | https://docs-assets.developer.apple.com/coreml/models/GoogLeNetPlaces.mlmodel


## Contribution
Feel free to create a pull request to add models