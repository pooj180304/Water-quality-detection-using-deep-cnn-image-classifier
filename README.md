Found 228 files belonging to 2 classes.
Model: "sequential"
_________________________________________________________________
 Layer (type)                Output Shape              Param #   
=================================================================
 conv2d (Conv2D)             (None, 254, 254, 16)      448       
                                                                 
 max_pooling2d (MaxPooling2D  (None, 127, 127, 16)     0         
 )                                                               
                                                                 
 conv2d_1 (Conv2D)           (None, 125, 125, 32)      4640      
                                                                 
 max_pooling2d_1 (MaxPooling  (None, 62, 62, 32)       0         
 2D)                                                             
                                                                 
 conv2d_2 (Conv2D)           (None, 60, 60, 16)        4624      
                                                                 
 max_pooling2d_2 (MaxPooling  (None, 30, 30, 16)       0         
 2D)                                                             
                                                                 
 flatten (Flatten)           (None, 14400)             0         
                                                                 
 dense (Dense)               (None, 256)               3686656   
                                                                 
 dense_1 (Dense)             (None, 1)                 257       
                                                                 
=================================================================
Total params: 3,696,625
Trainable params: 3,696,625
Non-trainable params: 0
_________________________________________________________________
Epoch 1/24
5/5 [==============================] - 11s 2s/step - loss: 1.2024 - accuracy: 0.4812 - val_loss: 0.7021 - val_accuracy: 0.5000
Epoch 2/24
5/5 [==============================] - 12s 2s/step - loss: 0.7234 - accuracy: 0.5250 - val_loss: 0.6791 - val_accuracy: 0.6406
Epoch 3/24
5/5 [==============================] - 11s 2s/step - loss: 0.6482 - accuracy: 0.6500 - val_loss: 0.6086 - val_accuracy: 0.7812
Epoch 4/24
5/5 [==============================] - 12s 2s/step - loss: 0.5834 - accuracy: 0.7063 - val_loss: 0.4997 - val_accuracy: 0.7656
Epoch 5/24
5/5 [==============================] - 12s 2s/step - loss: 0.5525 - accuracy: 0.7250 - val_loss: 0.5101 - val_accuracy: 0.7188
Epoch 6/24
5/5 [==============================] - 11s 2s/step - loss: 0.5925 - accuracy: 0.6562 - val_loss: 0.5268 - val_accuracy: 0.7344
Epoch 7/24
5/5 [==============================] - 11s 2s/step - loss: 0.5060 - accuracy: 0.7625 - val_loss: 0.5341 - val_accuracy: 0.7188
Epoch 8/24
5/5 [==============================] - 11s 2s/step - loss: 0.4676 - accuracy: 0.7875 - val_loss: 0.4527 - val_accuracy: 0.7812
Epoch 9/24
5/5 [==============================] - 10s 2s/step - loss: 0.4064 - accuracy: 0.8250 - val_loss: 0.3766 - val_accuracy: 0.8438
Epoch 10/24
5/5 [==============================] - 11s 2s/step - loss: 0.3783 - accuracy: 0.8375 - val_loss: 0.4497 - val_accuracy: 0.7344
Epoch 11/24
5/5 [==============================] - 10s 2s/step - loss: 0.3597 - accuracy: 0.8250 - val_loss: 0.2892 - val_accuracy: 0.8750
Epoch 12/24
5/5 [==============================] - 10s 2s/step - loss: 0.3288 - accuracy: 0.8188 - val_loss: 0.2969 - val_accuracy: 0.8906
Epoch 13/24
5/5 [==============================] - 10s 2s/step - loss: 0.2909 - accuracy: 0.8938 - val_loss: 0.2056 - val_accuracy: 0.9375
Epoch 14/24
5/5 [==============================] - 10s 2s/step - loss: 0.2314 - accuracy: 0.9563 - val_loss: 0.1814 - val_accuracy: 0.9219
Epoch 15/24
5/5 [==============================] - 9s 2s/step - loss: 0.2116 - accuracy: 0.9312 - val_loss: 0.1696 - val_accuracy: 0.9688
Epoch 16/24
5/5 [==============================] - 9s 2s/step - loss: 0.1740 - accuracy: 0.9438 - val_loss: 0.1031 - val_accuracy: 0.9844
Epoch 17/24
5/5 [==============================] - 9s 2s/step - loss: 0.0981 - accuracy: 1.0000 - val_loss: 0.0740 - val_accuracy: 1.0000
Epoch 18/24
5/5 [==============================] - 10s 2s/step - loss: 0.0635 - accuracy: 0.9937 - val_loss: 0.0370 - val_accuracy: 1.0000
Epoch 19/24
5/5 [==============================] - 10s 2s/step - loss: 0.0530 - accuracy: 0.9937 - val_loss: 0.0429 - val_accuracy: 0.9844
Epoch 20/24
5/5 [==============================] - 9s 2s/step - loss: 0.0322 - accuracy: 0.9937 - val_loss: 0.0814 - val_accuracy: 0.9688
Epoch 21/24
5/5 [==============================] - 12s 2s/step - loss: 0.0271 - accuracy: 0.9937 - val_loss: 0.0144 - val_accuracy: 1.0000
Epoch 22/24
5/5 [==============================] - 12s 2s/step - loss: 0.0295 - accuracy: 1.0000 - val_loss: 0.0095 - val_accuracy: 1.0000
Epoch 23/24
5/5 [==============================] - 17s 4s/step - loss: 0.0246 - accuracy: 0.9937 - val_loss: 0.0327 - val_accuracy: 1.0000
Epoch 24/24
5/5 [==============================] - 14s 3s/step - loss: 0.0127 - accuracy: 1.0000 - val_loss: 0.0098 - val_accuracy: 1.0000

![image](https://github.com/user-attachments/assets/9e6f65f1-7211-47cc-80f8-31d4237f08f8)
