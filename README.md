# Every_Face
Awesome Faceswap papers&amp;code&amp;datasets&amp;.. collection

##  Papers

### 20xx
| Title                                                                                      |   Venue   |              Dataset              |                                                                              PDF                                                                               |                      CODE                      |
|:------------------------------------------------------------------------------------------ |:---------:|:---------------------------------:|:--------------------------------------------------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------:|
| Compositional Zero-Shot Learning using Multi-Branch Graph Convolution and Cross-layer Knowledge Sharing | PR 2024 | MIT-States & UT-Zappos & C-GQA | [PDF](https://www.sciencedirect.com/science/article/pii/S0031320323006143) | - |
| GIPCOL: Graph-Injected Soft Prompting for Compositional Zero-ShotLearning | WACV 2024 | MIT-States & UT-Zappos & C-GQA | [PDF](https://arxiv.org/pdf/2311.05729.pdf) | [CODE](https://github.com/HLR/GIPCOL) |

##  Projects

| Title                                                                                      |   Project Address|              Introduction              | 
|:------------------------------------------------------------------------------------------ |:---------:|:---------------------------------:|
| DeepFaceLab | [DeepFaceLab](https://github.com/iperov/DeepFaceLab) | DeepFaceLab is an open-source GAN-based face-swapping deepfake system on Github, and it provides an easy-to-use and expandable pipelne, which is the dominant face-swapping framework today.| 
| FaceSwap | [FaceSwap](https://github.com/deepfakes/faceswap/tree/master) | Faceswap is a GAN-based deepfake open-source tool on github. it provides an easy-to-use GUI interface to facilitate operations such as training and face-swapping. |
| SwapFace |[SwapFace](https://swapface.org/#/tutorial) | SwapFace is a closed-source deepfake tool for Windows that provides an easy-to-use GUI interface to enable users to accomplish one-click face swapping tasks in a foolproof way. |
| Roop | [Roop](https://github.com/s0md3v/roop) | Roop is a one-click deepfake open source tool on github. it enables replacing the face in the original video with just a single image without dataset and training. |
| FSGAN | [FSGAN](https://github.com/YuvalNirkin/fsgan) | Face Swapping GAN (FSGAN) is a novel Recurrent Neural Network (RNN)-based face reproduction method that can be adapted to pose and expression changes, and can be applied to single images or video sequences. |
| HifiFace | [HifiFace](https://github.com/maum-ai/hififace) | HifiFace uses a 3D shape-aware identity extractor to obtain three-bit shape identities. Also, a semantic facial fusion module is introduced to address occlusion and illumination |
| Vid2DensePose | [Vid2DensePose](https://github.com/Flode-Labs/vid2densepose) | The Vid2DensePose is a powerful tool designed for applying the DensePose model to videos, generating detailed "Part Index" visualizations for each frame. This tool is exceptionally useful for enhancing animations, particularly when used in conjunction with MagicAnimate for temporally consistent human image animation. |

##  Datasets
### FFHQ
Introduced by Karras et al. in  [Style-Based Generator Architecture for Generative Adversarial Networks](https://arxiv.org/abs/1812.04948v3).

Flickr-Faces-HQ (FFHQ) consists of 70,000 high-quality PNG images at 1024×1024 resolution and contains considerable variation in terms of age, ethnicity and image background. It also has good coverage of accessories such as eyeglasses, sunglasses, hats, etc. The images were crawled from Flickr, thus inheriting all the biases of that website, and automatically aligned and cropped using dlib. Only images under permissive licenses were collected. Various automatic filters were used to prune the set, and finally Amazon Mechanical Turk was used to remove the occasional statues, paintings, or photos of photos.

Source: http:https://github.com/NVlabs/ffhq-dataset
### YouTube Faces DB
ntroduced by Wolf et al. in [Face recognition in unconstrained videos with matched background similarity](https://ieeexplore.ieee.org/document/5995566).

YouTube Faces DB dataset contains 3,425 videos of 1,595 different people. All the videos were downloaded from YouTube. An average of 2.15 videos are available for each subject. The shortest clip duration is 48 frames, the longest clip is 6,070 frames, and the average length of a video clip is 181.3 frames.

Source: https://www.cs.tau.ac.il/~wolf/ytfaces/
### FaceForensics++
Introduced by Rössler et al. in [FaceForensics: A Large-scale Video Dataset for Forgery Detection in Human Faces](https://arxiv.org/abs/1803.09179).

FaceForensics is a video dataset consisting of more than 500,000 frames containing faces from 1004 videos that can be used to study image or video forgeries. All videos are downloaded from Youtube and are cut down to short continuous clips that contain mostly frontal faces. This dataset has two versions:
* Source-to-Target: where the authors reenact over 1000 videos with new facial expressions extracted from other videos, which e.g. can be used to train a classifier to detect fake images or videos.
* Selfreenactment: where the authors use Face2Face to reenact the facial expressions of videos with their own facial expressions as input to get pairs of videos, which e.g. can be used to train supervised generative refinement models.

Source: https://github.com/ondyari/FaceForensics
### DFDC
Introduced by Dolhansky et al. in [The Deepfake Detection Challenge (DFDC) Preview Dataset](https://arxiv.org/abs/1910.08854).

The DFDC (Deepfake Detection Challenge) is a dataset for deepface detection consisting of more than 100,000 videos.

The DFDC dataset consists of two versions:
* Preview dataset. with 5k videos. Featuring two facial modification algorithms.
* Full dataset, with 124k videos. Featuring eight facial modification algorithms.

Source: https://ai.meta.com/datasets/dfdc/
##  Acknowledgements
This page is made by [Bohuan Qu](https://github.com/Gdnaiteab),[Yize Cai](https://github.com/OskarJoa),[Xizhe Wu](https://github.com/SeverusNg), both of whom are students of Dalian University of Technology.
