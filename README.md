# Keras-ACGAN-CIFAR10
Code Modified from https://github.com/lukedeo/keras-acgan,  
This is CIFAR10 version. Some interesting trick refers to Soumith Chintala ganhacks(https://github.com/soumith/ganhacks). 
This Code will start at the epoch 950(thought it display epoch 0, but it reload epoch 949 pretrain training weight!)  
You can remove:  
```python
generator.load_weights('params_generator_epoch_{0:03d}.hdf5'.format(save-1))  
```
```python
discriminator.load_weights('params_discriminator_epoch_{0:03d}.hdf5'.format(save-1))  
```
to get it train from beginning!  
This is one of generate image:  
![image](https://github.com/King-Of-Knights/Keras-ACGAN-CIFAR10/blob/master/plot_generated.png)
