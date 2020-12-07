# resnet_upgrad
Code for resnet_upgrad

1. Use tensorflow.keras inplace of keras
2. The input shape should be changed to (n_rows, n_cols, n_channels), i.e a 'channel_last' format as is returned by the tensorflow.keras.backend.image_data_format()
3. Incase you wish to run the tensorboard plugin update tensorboard to below version, if not just comment out the tensorboar code in the ipynb file
4. Alot of the code is deprecated so ignore the warnings for now, will updated as soon as able to.

Tensorflow version: tensorflow == 2.3.1
Tensorboard version: tensorboard == 2.4.0
                     tensorboard-plugin-wit == 1.7.0
