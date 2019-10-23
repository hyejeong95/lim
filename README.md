# lim

# deplearning 모델 부분정의 하는 것 
# https://colab.research.google.com/github/tensorflow/docs/blob/master/site/ko/tutorials/keras/classification.ipynb

# 층결정 
# model = keras.Sequential([
#    keras.layers.Flatten(input_shape=(28, 28)),
#    keras.layers.Dense(128, activation='relu'),
#    keras.layers.Dense(88, activation='relu'),
#    keras.layers.Dense(48, activation='relu'),
#    keras.layers.Dense(10, activation='softmax')
#])

# overfitting
# train accuracy와 validation set accuracy 크게 차이가 나면 overfitting 
# keras.layers.Dropout(0.5)추가 :중간 중간에 넣어주기 
# model.fit(train_images, train_labels, epochs=5,
#        validation_data=(test_images,test_labels) )


