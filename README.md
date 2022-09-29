# GPU Accelerated TensorFlow Lite applications on Android NDK.
Run and measure the performance of TensorFlow Lite GPU Delegate on Android NDK.



## 1. Applications
List of Applications
### [Blazeface](https://github.com/terryky/android_tflite/tree/master/tflite_blazeface)
- Lightweight Face Detection.<br>
[<img src="tflite_blazeface/tflite_blazeface.png" width=500>](https://github.com/terryky/android_tflite/tree/master/tflite_blazeface)

### [DBFace](https://github.com/terryky/android_tflite/tree/master/tflite_dbface)
- Higher accurate Face Detection.<br>
[<img src="tflite_dbface/tflite_dbface.jpg" width=600>](https://github.com/terryky/android_tflite/tree/master/tflite_dbface)

### [Age Gender Estimation](https://github.com/terryky/android_tflite/tree/master/tflite_age_gender)
- Detect faces and estimage their Age and Gender
- based on pretrained model of [https://github.com/yu4u/age-gender-estimation](https://github.com/yu4u/age-gender-estimation)<br>
[<img src="tflite_age_gender/tflite_gender.jpg" width=300>](https://github.com/terryky/android_tflite/tree/master/tflite_age_gender)

### [Image Classification](https://github.com/terryky/android_tflite/tree/master/tflite_classification)
- Image Classfication using Moilenet.<br>
[<img src="tflite_classification/tflite_classification.png" width=500>](https://github.com/terryky/android_tflite/tree/master/tflite_classification)

### [Object Detection](https://github.com/terryky/android_tflite/tree/master/tflite_detection)
- Object Detection using MobileNet SSD.<br>
[<img src="tflite_detection/tflite_detection.png" width=500>](https://github.com/terryky/android_tflite/tree/master/tflite_detection)

### [Hair Segmentation](https://github.com/terryky/android_tflite/tree/master/tflite_hair_segmentation)
- Hair segmentation and recoloring.<br>
[<img src="tflite_hair_segmentation/hair_segmentation.jpg" width=600>](https://github.com/terryky/android_tflite/tree/master/tflite_hair_segmentation)

### [3D Handpose](https://github.com/terryky/android_tflite/tree/master/tflite_handpose)
- 3D Handpose Estimation from single RGB images.<br>
[<img src="tflite_handpose/handpose.png" width=600>](https://github.com/terryky/android_tflite/tree/master/tflite_handpose)

### [Iris Detection](https://github.com/terryky/android_tflite/tree/master/tflite_iris_landmark)
- Eye position estimation by detecting the iris.<br>
[<img src="tflite_iris_landmark/iris_landmark.png" width=600>](https://github.com/terryky/android_tflite/tree/master/tflite_iris_landmark)

### [Posenet](https://github.com/terryky/android_tflite/tree/master/tflite_posenet)
- Pose Estimation.<br>
[<img src="tflite_posenet/tflite_posenet.png" width=500>](https://github.com/terryky/android_tflite/tree/master/tflite_posenet)

### [Depth Estimation (DenseDepth)](https://github.com/terryky/android_tflite/tree/master/tflite_dense_depth)
- Depth Estimation from single images.<br>
- based on pretrained model of [https://github.com/ialhashim/DenseDepth](https://github.com/ialhashim/DenseDepth)
[<img src="tflite_dense_depth/dense_depth.jpg" width=600>](https://github.com/terryky/android_tflite/tree/master/tflite_dense_depth)

### [Semantic Segmentation](https://github.com/terryky/android_tflite/tree/master/tflite_segmentation)
- Assign semantic labels to every pixel in the input image.<br>
[<img src="tflite_segmentation/tflite_segmentation.png" width=600>](https://github.com/terryky/android_tflite/tree/master/tflite_segmentation)

### [Selfie to Anime](https://github.com/terryky/android_tflite/tree/master/tflite_selfie2anime)
- Generate anime-style face image.<br>
- based on pretrained model of [https://github.com/margaretmz/Selfie2Anime-with-TFLite](https://github.com/margaretmz/Selfie2Anime-with-TFLite)<br>
[<img src="tflite_selfie2anime/selfie2anime.jpg" width=600>](https://github.com/terryky/android_tflite/tree/master/tflite_selfie2anime)

### [Anime GAN](https://github.com/terryky/android_tflite/tree/master/tflite_animegan2)
- Transform photos into anime style images.<br>
- based on pretrained model of [https://github.com/TachibanaYoshino/AnimeGANv2](https://github.com/TachibanaYoshino/AnimeGANv2)<br>
[<img src="tflite_animegan2/animegan2.png" width=600>](https://github.com/terryky/android_tflite/tree/master/tflite_animegan2)

### [U^2-Net portrait drawing](https://github.com/terryky/android_tflite/tree/master/tflite_face_portrait)
- Human portrait drawing by [U^2-Net](https://github.com/NathanUA/U-2-Net).<br>
[<img src="tflite_face_portrait/face_portrait.jpg" width=600>](https://github.com/terryky/android_tflite/tree/master/tflite_face_portrait)

### [Artistic Style Transfer](https://github.com/terryky/android_tflite/tree/master/tflite_style_transfer)
- Create new artworks in artistic style.<br>
[<img src="tflite_style_transfer/style_transfer.png" width=600>](https://github.com/terryky/android_tflite/tree/master/tflite_style_transfer)

### [MIRNet](https://github.com/terryky/android_tflite/tree/master/tflite_mirnet)
- Enhance low-light images upto a great extent.<br>
- based on pretrained model of [https://github.com/sayakpaul/MIRNet-TFLite](https://github.com/sayakpaul/MIRNet-TFLite)
[<img src="tflite_mirnet/mirnet.jpg" width=600>](https://github.com/terryky/android_tflite/tree/master/tflite_mirnet)


## 2. How to Build & Run

### 2.1 setup environment

- Download and install [Android NDK](https://developer.android.com/ndk/downloads).

```
$ mkdir ~/Android/
$ mv ~/Download/android-ndk-r20b-linux-x86_64.zip ~/Android
$ cd ~/Android
$ unzip android-ndk-r20b-linux-x86_64.zip
```

- Download and install [bazel](https://docs.bazel.build/versions/master/install-ubuntu.html).

```
$ wget https://github.com/bazelbuild/bazel/releases/download/3.1.0/bazel-3.1.0-installer-linux-x86_64.sh
$ chmod 755 bazel-3.1.0-installer-linux-x86_64.sh
$ sudo ./bazel-3.1.0-installer-linux-x86_64.sh
```

### 2.2 build TensorFlow Lite library and GPU Delegate library

- run the build script to build TensorFlow Library

```
$ mkdir ~/work
$ git clone https://github.com/terryky/android_tflite.git
$ cd android_tflite/third_party/
$ ./build_libtflite_r2.4_android.sh

(Tensorflow configure will start after a while. Please enter according to your environment)


$ ls -l tensorflow/bazel-bin/tensorflow/lite/
-r-xr-xr-x  1 terryky terryky 3118552 Dec 26 19:58 libtensorflowlite.so*

$ ls -l tensorflow/bazel-bin/tensorflow/lite/delegates/gpu/
-r-xr-xr-x 1 terryky terryky 80389344 Dec 26 19:59 libtensorflowlite_gpu_delegate.so*
```


### 2.3 Download the needed assets

```
$ cd ~/work/android_tflite
$ ./download_all_assets.sh
```


### 2.4 Build Android Applications
- Download and install [Android Studio](https://developer.android.com/studio/install).
- Start Android Studio.

```
$ cd ${ANDROID_STUDIO_INSTALL_DIR}/android-studio/bin/
$ ./studio.sh
```

- Install NDK 20.0 by SDK Manager of Android Studio.
- Open application folder (eg. ```~/work/android_tflite/tflite_posenet```).
- Build and Run.

## 3. Tested Environment

| Host PC             | Target Device           |
|:-------------------:|:-----------------------:|
| x86_64              | arm64-v8a               |
| Ubuntu 18.04.4 LTS  | Android 9 (API Level 28)|
| Android NDK r20b    |                         |


## 4. Related Articles
- [Android NDK 環境で TensorFlow Lite GPU Delegate を使う方法 (Qiita)](https://qiita.com/terryky/items/7b92114af1c9b3b3ef7b)

## 5.  Acknowledgements
- https://github.com/google/mediapipe
- https://github.com/yu4u/age-gender-estimation
- https://github.com/TachibanaYoshino/AnimeGANv2
- https://github.com/openvinotoolkit/open_model_zoo/tree/master/demos/python_demos/human_pose_estimation_3d_demo
- https://github.com/ialhashim/DenseDepth
- https://github.com/MaybeShewill-CV/bisenetv2-tensorflow
- https://github.com/margaretmz/Selfie2Anime-with-TFLite
- https://github.com/NathanUA/U-2-Net
- https://tfhub.dev/sayakpaul/lite-model/east-text-detector/int8/1
- https://github.com/PINTO0309/PINTO_model_zoo
