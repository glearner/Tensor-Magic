# Tensor-Magic Angular 

This app imports an MNIST ConvNet trained in Keras Python, then makes predictions with TensorFlow.js

- clone it, cd into it, `npm install && ng serve`

## Use a Different Keras Model

```
tensorflowjs_converter --input_format keras keras/yourWeights.h5 src/assets
```

![file1](https://user-images.githubusercontent.com/29622895/40031567-ec8f3338-580d-11e8-91a4-c31e9119e64a.gif)
