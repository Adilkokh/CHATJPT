import tensorflow as tf from tensorflow.keras import layers, models

])model = models. Sequential layers. Dense (64, activation='relu', input_shape=(input_shape,))

layers. Dense (32,

,activation='relu')

layers. Dense(1,

activation='sigmoid')

([

model.compile(optimizer='ad

am'

loss='binary_crossentropy', metrics=['accuracy'])

model.fit(train_data,

train_labels, epochs=10, validation_data=(test_data, test_labels))
