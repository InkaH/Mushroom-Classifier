# TensorFlow Lite image classification Android example application

## Overview

This is a demo application for [TensorFlow Lite](https://tensorflow.org/lite)
on Android modified from the original Tensorflow Lite example application at https://github.com/tensorflow/examples/tree/master/lite/examples/image_classification/android. It uses
[Image classification](https://www.tensorflow.org/lite/models/image_classification/overview)
to continuously classify whatever it sees from the device's back camera.
Inference is performed using the TensorFlow Lite Java API. The demo app
classifies frames in real-time, displaying the top 5 most probable
classifications. 

### Model
This app uses a custom neural network model trained for classifying mushroom species. Model is not included in this package, so this app is not usable as is. 

## Requirements

*   Android Studio 3.2 (installed on a Linux, Mac or Windows machine)

*   Android device in
    [developer mode](https://developer.android.com/studio/debug/dev-options)
    with USB debugging enabled

*   USB cable (to connect Android device to your computer)

Copyright 2019 Inka Haltiapuu

Licensed under the Apache License, Version 2.0;
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
