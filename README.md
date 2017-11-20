# Keras-ACGAN-CIFAR10
Code Modified from https://github.com/lukedeo/keras-acgan, This is CIFAR10 version. Some interesting trick refers to Soumith Chintala GANHACK
This Code will start at the epoch 959(thought it display epoch 0, but it reload epoch 958 training weight!)
You can remove generator.load_weights('params_generator_epoch_{0:03d}.hdf5'.format(save-1))
                discriminator.load_weights('params_discriminator_epoch_{0:03d}.hdf5'.format(save-1))
to get it training from beginning!
