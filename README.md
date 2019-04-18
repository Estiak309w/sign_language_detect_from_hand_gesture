# sign_language_detect_from_hand_gesture#
# Tools and Library #
jupyter notebook, tensorflow
##Dataset Description##
The dataset was taken from kaggle website. https://www.kaggle.com/datamunge/sign-language-mnist which contains The training data (27,455 cases) and test data (7172 cases)
he original hand gesture image data represented multiple users repeating the gesture against different backgrounds. The Sign Language MNIST data came from greatly extending the small number (1704) of the color images included as not cropped around the hand region of interest. To create new data, an image pipeline was used based on ImageMagick and included cropping to hands-only, gray-scaling, resizing, and then creating at least 50+ variations to enlarge the quantity. The modification and expansion strategy was filters ('Mitchell', 'Robidoux', 'Catrom', 'Spline', 'Hermite'), along with 5% random pixelation, +/- 15% brightness/contrast, and finally 3 degrees rotation. Because of the tiny size of the images, these modifications effectively alter the resolution and class separation in interesting, controllable ways.
This dataset was inspired by the Fashion-MNIST 2 and the machine learning pipeline for gestures by Sreehari 4.
A robust visual recognition algorithm could provide not only new benchmarks that challenge modern machine learning methods such as Convolutional Neural Nets but also could pragmatically help the deaf and hard-of-hearing better communicate using computer vision applications. The National Institute on Deafness and other Communications Disorders (NIDCD) indicates that the 200-year-old American Sign Language is a complete, complex language (of which letter gestures are only part) but is the primary language for many deaf North Americans. ASL is the leading minority language in the U.S. after the "big four": Spanish, Italian, German, and French. One could implement computer vision in an inexpensive board computer like Raspberry Pi with OpenCV, and some Text-to-Speech to enabling improved and automated translation applications.
![amer_sign2](https://user-images.githubusercontent.com/23102524/56342884-07e9b680-61db-11e9-9a9c-b2819e9318c6.png)

## Project Description ##
A Convolutional Neural Based Model which detect sign language from hand gesture. Image quality was reduced to 28*28 pixel . Activation function softmax,optimizer adam was used. to prevent overfitting dropout 0.2 was kept. Epoch 50 and batch_size 128 was kept to find better accuracy.
Accuracy of the algorithm is **79.44%**.
## here is the accuracy gaining by epochs is shown ##
![accuracy vs epochs](https://user-images.githubusercontent.com/23102524/56343429-8e52c800-61dc-11e9-83ed-d1146dfe063f.JPG)
