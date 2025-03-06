# Glass_surface_detect_dataset

This paper conducts experiments on all widely used datasets of glass surfaces, including the GDD dataset [1], the HSO dataset [2], the GSD dataset [3], and the Trans10K dataset [4], to demonstrate the effectiveness of the method proposed in this paper. According to the scenarios that may be involved in and focused on by this study, the dataset used in this paper (open source) has been re-screened, constructed, and annotated. This dataset is specifically designed for training and evaluating object detection models in the working environment of robots. The dataset contains 15,339 images, which are divided into 10,407 training images, 2,932 validation images, and 2,000 test images. Such a distribution ensures that the model has sufficient data to learn different features during training and can fairly evaluate the generalization ability of the model during the validation and testing phases.
The images in the dataset are from various environments, including the glass in shopping mall environments, office environments, and home environments, as well as car window glass, machine glass, showcase glass, and countertop glass. There are also indoor and outdoor decorative glasses under different weather and lighting conditions, as well as glasses in special scenarios, such as those illuminated by lights, with reflective objects around, glasses with indistinct frames, and interference from empty areas. These simulate the complex glass scenarios that robots may encounter in the real world. Figure 1 depicts the typical scenarios in the dataset.


References
[1] Mei H, Yang X, Wang Y, et al. Don't hit me! glass detection in real-world scenes[C]//Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2020: 3687-3696.
[2] Yu L, Mei H, Dong W, et al. Progressive glass segmentation[J]. IEEE Transactions on Image Processing, 2022, 31: 2920-2933.
[3] Lin J, He Z, Lau R W H. Rich context aggregation with reflection prior for glass surface detection[C]//Proceedings of the IEEE/CVF conference on computer vision and pattern recognition. 2021: 13415-13424.
[4] Xie E, Wang W, Wang W, et al. Segmenting transparent objects in the wild[C]//Computer Vision–ECCV 2020: 16th European Conference, Glasgow, UK, August 23–28, 2020, Proceedings, Part XIII 16. Springer International Publishing, 2020: 696-711.
