# Lyryc: A Lyrical Image Caption Generator

Please find the app module of the project [here](https://github.com/singhpratham72/Lyryc.git).

# Requirements
- [tensorflow](https://github.com/tensorflow/tensorflow) (TensorFlow is an end-to-end open source platform for machine learning)
- [keras](https://github.com/keras-team/keras) (Keras is an open-source software library that provides a Python interface for artificial neural networks.)
- [pickle](https://github.com/python/cpython/blob/3.10/Lib/pickle.py) (The pickle module implements binary protocols for serializing and de-serializing a Python object structure.)
- [numpy](https://github.com/numpy/numpy) (NumPy is a Python library used for working with arrays.)

# In a Nutshell   
Here is how you can use this project to generate a caption for an image:
- Add an image of your choice to the top level directory and name it `test.jpg`.
- In `IML_CaptionGenerator.ipynb`, run the 'Import Tensorflow and Keras' block.
- In `IML_CaptionGenerator.ipynb`, run the 'Caption Generation' block. This will print the generated caption for `test.jpg`. You can test a different model by specifying it here.
``` 
model = load_model('model/model_11.h5')
``` 

# Folder Structure
```
├──  data
│    └── datasets  - here's the datasets folder that is responsible for all data handling.
│
│
├── model            - this folder contains any model generated by the code.
│   └── model_n.h5
│   
│ 
├──  tools            - here's the helper files for the project.
```

![slide1](https://github.com/singhpratham72/Lyryc/blob/c8fe0506ef7983cbe3e42bc5db91f4e9e8a6a7ad/lyrycslides/Lyryc_page-0001.jpg)
![slide2](https://github.com/singhpratham72/Lyryc/blob/c8fe0506ef7983cbe3e42bc5db91f4e9e8a6a7ad/lyrycslides/Lyryc_page-0002.jpg)
![slide3](https://github.com/singhpratham72/Lyryc/blob/c8fe0506ef7983cbe3e42bc5db91f4e9e8a6a7ad/lyrycslides/Lyryc_page-0003.jpg)
![slide4](https://github.com/singhpratham72/Lyryc/blob/c8fe0506ef7983cbe3e42bc5db91f4e9e8a6a7ad/lyrycslides/Lyryc_page-0004.jpg)
![slide5](https://github.com/singhpratham72/Lyryc/blob/c8fe0506ef7983cbe3e42bc5db91f4e9e8a6a7ad/lyrycslides/Lyryc_page-0005.jpg)
![slide6](https://github.com/singhpratham72/Lyryc/blob/c8fe0506ef7983cbe3e42bc5db91f4e9e8a6a7ad/lyrycslides/Lyryc_page-0006.jpg)
