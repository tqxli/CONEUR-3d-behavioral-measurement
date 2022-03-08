---
title: Leaving Flatland: Advances in 3D behavioral measurement
---

# Expanded Table 1 for Leaving Flatland: Advances in 3D behavioral measurement 

**Emerging directions in 3D human and animal tracking.** Thematically organized compilation of recent studies that illustrate a roadmap for improvements in 3D behavioral tracking based on computer vision and deep learning. 

We welcome any suggested edits to include papers we may have missed or to update with newer papers as the field quickly evolves.

<style>
table th:first-of-type {
    width: 5%;
}
table th:nth-of-type(2) {
    width: 15%;
}
table th:nth-of-type(3) {
    width: 40%;
}
table th:nth-of-type(4) {
    width: 40%;
}
</style>

|  |  | Human 3D Tracking | Animal 3D Tracking |
| --- | --- | --- | ---|
| **Occlusion robustness** | *2D cross-view fusion & triangulation* | (Qiu et al., 2019)  (He et al., 2020) (Xie et al., 2020)  (Zhang et al., 2021b) (Lin and Lee, 2021)|  |
| | *2D keypoint triangulation* | (Iskakov et al., 2019) | (Nath et al., 2018)  (Karashchuk et al., 2021)  (Liu et al., 2021b)  |
| | *3D volumetric* | (Iskakov et al., 2019)  (Tu et al., 2020) | (Zimmermann et al., 2020)  (Dunn et al., 2021) | 
| | *temporal information* | (Pavllo et al., 2019)  (Rafi et al., 2020) (Zheng et al., 2021a) (Choi et al., 2021a) (Li et al., 2021b) | (Liu et al., 2021b) (Karashchuk et al., 2021) (Sarkar et al., 2021) (Bala et al., 2021) |
|  | *graphical modeling* | (Cai et al., 2019) (Qiu et al., 2019) (Zeng et al., 2021) (Zou et al., 2021) (Xu and Takano, 2021) | (Zhang et al., 2021a) | 
|  | *explicit occlusion training* | (Cheng et al., 2019) (Cheng et al., 2020) | | 
| **Labeled training data efficiency** | *multi-view consistency* | (Mitra et al., 2020) (Jenni and Favaro, 2020) (Wandt, B., Rudolph, M., Zell, P., Rhodin, H., & Rosenhahn, B., 2021)  (Iqbal et al., 2020) (Usman et al., 2021) | (Yao et al., 2018) (Bala et al., 2021) |
|  | *geometric self-supervision* | (Chen et al., 2019a) (Kocabas et al., 2019) (Pavllo et al., 2019) (Li et al., 2020b) (Wang et al., 2020) | | 
|  | *representation learning* | (Jiang et al., 2019) (Chen et al., 2019b)  (Kundu et al., 2020a) (Sun et al., 2020) (Zimmermann et al., 2021) | (Bala et al., 2021)|
|  | *constraints* | (Ma et al., 2021) (Liu et al., 2021a) | (Karashchuk et al., 2021) | 
|  | *data augmentation* | (Zeng et al., 2020) (Li et al., 2020a) | |  
| **Flexible, scalable and rapid tracking** | *unsynchronized or uncalibrated cameras* | (Habibie et al., 2019) (Yoon et al., 2019) (Kundu et al., 2020b) (Ma et al., 2021) (Chen et al., 2021) (Kocabas et al., 2021) | | 
| | *real-time tracking* | (Ren et al., 2019) (Hwang et al., 2020) (Remelli et al., 2020) (Choi et al., 2021b) | | 
| **Richer body representations** | *dense pose estimation* |(Neverova et al., 2019) (Weinzaepfel et al., 2020)  | (Sanakoyeu et al., 2020) (Bala et al., 2021) |
|  | *body shape reconstruction* |(Pavlakos et al., 2019) (Jiang et al., 2020) (Xu et al., 2020) (Zheng et al., 2021b)  | (Zuffi, S., Kanazawa, A., Berger-Wolf, T., & Black, M. J., 2019) (Biggs et al., 2020a) (Li et al., 2021a) (Deane et al., 2021) | 
| **Multi-subject tracking** | *top-down* | (Dabral et al., 2019) (Dong et al., 2021a) (Huang et al., 2020) (Tu et al., 2020) (Lin and Lee, 2021) (Reddy et al., 2021) | (Bala et al., 2020) (Marshall et al., 2021) |
|  | *bottom-up* |(Jin et al., 2020) (Kundu et al., 2020a) (Dong et al., 2021b) | | 
| | *interaction modeling* | (Hasson et al., 2019) (Li et al., 2019) (Fieraru et al., 2020) | |
| **3D pose uncertainty** | *multi-pose generation* | (Li and Lee, 2019) (Biggs et al., 2020b)  | |  
| | *probabilistic modeling* | (Kolotouros et al., 2021) (Wehrbein et al., 2021)  | (Zhang et al., 2021a) | 
| **Dataset** | *3D pose* | (Sigal et al., 2009) (Ionescu et al., 2014) (Joo et al., 2015) (Mehta et al., 2016) (Lassner et al., 2017) (von Marcard et al., 2018) | (Bala et al., 2020)  (Kearney et al., 2020) (Joska et al., 2021) (Marshall et al., 2021) |  
| | *3D shape* | (Varol et al., 2017) (Güler et al., 2018) (Mahmood et al., 2019) (Choutas et al., 2020) | (Kearney et al., 2020) |
| | *synthetic data* | (Doersch and Zisserman, 2019) (Wang et al., 2019)  (Zhang et al., 2019)  (Sengupta et al., 2020) (Varol et al., 2021) | (Deane et al., 2021) (Bolaños et al., 2021) | 

## References
Bala, P. C., Eisenreich, B. R., Yoo, S. B. M., Hayden, B. Y., Park, H. S., & Zimmermann, J. (2020). Automated markerless pose estimation in freely moving macaques with OpenMonkeyStudio. Nature Communications, 11(1), 4560.

Bala, P. C., Zimmermann, J., Park, H. S., & Hayden, B. Y. (2021). Self-supervised Secondary Landmark Detection via 3D Representation Learning. In arXiv [cs.CV]. arXiv. http://arxiv.org/abs/2110.00543

Biggs, B., Boyne, O., Charles, J., Fitzgibbon, A., & Cipolla, R. (2020). Who Left the Dogs Out? 3D Animal Reconstruction with Expectation Maximization in the Loop. Computer Vision – ECCV 2020, 195–211.

Biggs, B., Ehrhadt, S., Joo, H., Graham, B., Vedaldi, A., & Novotny, D. (2020). 3D Multi-bodies: Fitting Sets of Plausible 3D Human Models to Ambiguous Image Data. Advances in Neural Information Processing Systems 33 (2020), 20496–20507.

Bolaños, L. A., Xiao, D., Ford, N. L., LeDue, J. M., Gupta, P. K., Doebeli, C., Hu, H., Rhodin, H., & Murphy, T. H. (2021). A three-dimensional virtual mouse generates synthetic training data for behavioral analysis. Nature Methods, 18(4), 378–381.

Cai, Y., Ge, L., Liu, J., Cai, J., Cham, T.-J., Yuan, J., & Thalmann, N. M. (2019). Exploiting spatial-temporal relationships for 3d pose estimation via graph convolutional networks. Proceedings of the IEEE/CVF International Conference on Computer Vision, 2272–2281.

Chen, C.-H., Tyagi, A., Agrawal, A., Drover, D., Stojanov, S., & Rehg, J. M. (2019). Unsupervised 3d pose estimation with geometric self-supervision. Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 5714–5724.

Cheng, Y., Yang, B., Wang, B., & Tan, R. T. (2020). 3D Human Pose Estimation Using Spatio-Temporal Networks with Explicit Occlusion Training. Proceedings of the AAAI Conference on Artificial Intelligence, 34(07), 10631–10638.

Cheng, Y., Yang, B., Wang, B., Yan, W., & Tan, R. T. (2019). Occlusion-aware networks for 3d human pose estimation in video. Proceedings of the IEEE/CVF International Conference on Computer Vision, 723–732.

Chen, X., Lin, K.-Y., Liu, W., Qian, C., & Lin, L. (2019). Weakly-supervised discovery of geometry-aware representation for 3d human pose estimation. Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 10895–10904.

Chen, X., Wei, P., & Lin, L. (2021). Deductive Learning for Weakly-Supervised 3D Human Pose Estimation via Uncalibrated Cameras. Proceedings of the AAAI Conference on Artificial Intelligence, 1089–1096.

Choi, H., Moon, G., Chang, J. Y., & Lee, K. M. (2021). Beyond Static Features for Temporally Consistent 3D Human Pose and Shape from a Video. Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 1964–1973.

Choi, S., Choi, S., & Kim, C. (2021). MobileHumanPose: Toward Real-Time 3D Human Pose Estimation in Mobile Devices. Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2328–2338.

Choutas, V., Pavlakos, G., Bolkart, T., Tzionas, D., & Black, M. J. (2020). Monocular Expressive Body Regression through Body-Driven Attention. European Conference on Computer Vision, 20–40.

Dabral, R., Gundavarapu, N. B., Mitra, R., Sharma, A., Ramakrishnan, G., & Jain, A. (2019). Multi-Person 3D Human Pose Estimation from Monocular Images. 2019 International Conference on 3D Vision (3DV), 405–414.

Deane, J., Kearney, S., Kim, K. I., & Cosker, D. (2021). DynaDog+T: A Parametric Animal Model for Synthetic Canine Image Generation. In arXiv [cs.CV]. arXiv. http://arxiv.org/abs/2107.07330

Doersch, C., & Zisserman, A. (2019). Sim2real transfer learning for 3D human pose estimation: motion to the rescue. Advances in Neural Information Processing Systems, 32. 

Dong, J., Fang, Q., Jiang, W., Yang, Y., Huang, Q., Bao, H., & Zhou, X. (2021). Fast and Robust Multi-Person 3D Pose Estimation and Tracking from Multiple Views. IEEE Transactions on Pattern Analysis and Machine Intelligence. https://doi.org/10.1109/TPAMI.2021.3098052

Dong, Z., Song, J., Chen, X., Guo, C., & Hilliges, O. (2021). Shape-aware multi-person pose estimation from multi-view images. Proceedings of the IEEE/CVF International Conference on Computer Vision, 11158–11168.

Dunn, T. W., Marshall, J. D., Severson, K. S., Aldarondo, D. E., Hildebrand, D. G. C., Chettih, S. N., Wang, W. L., Gellis, A. J., Carlson, D. E., Aronov, D., Freiwald, W. A., Wang, F., & Ölveczky, B. P. (2021). Geometric deep learning enables 3D kinematic profiling across species and environments. Nature Methods, 18(5), 564–573.

Fieraru, M., Zanfir, M., Oneata, E., Popa, A.-I., Olaru, V., & Sminchisescu, C. (2020). Three-dimensional reconstruction of human interactions. Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 7214–7223.

Güler, R. A., Neverova, N., & Kokkinos, I. (2018). Densepose: Dense human pose estimation in the wild. Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition, 7297–7306.

Hasson, Y., Varol, G., Tzionas, D., Kalevatykh, I., Black, M. J., Laptev, I., & Schmid, C. (2019). Learning joint reconstruction of hands and manipulated objects. Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 11807–11816.

He, Y., Yan, R., Fragkiadaki, K., & Yu, S.-I. (2020). Epipolar Transformer for Multi-view Human Pose Estimation. Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops, 1036–1037.

Huang, C., Jiang, S., Li, Y., Zhang, Z., Traish, J., Deng, C., Ferguson, S., & Da Xu, R. Y. (2020). End-to-end Dynamic Matching Network for Multi-view Multi-person 3D Pose Estimation. Computer Vision – ECCV 2020, 477–493.

Hwang, D.-H., Kim, S., Monet, N., Koike, H., & Bae, S. (2020). Lightweight 3D human pose estimation network training using teacher-student learning. Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision, 479–488.

Ionescu, C., Papava, D., Olaru, V., & Sminchisescu, C. (2014). Human3.6M: Large Scale Datasets and Predictive Methods for 3D Human Sensing in Natural Environments. IEEE Transactions on Pattern Analysis and Machine Intelligence, 36(7), 1325–1339.
Iqbal, U., Molchanov, P., & Kautz, J. (2020).

 Weakly-supervised 3d human pose learning via multi-view images in the wild. Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 5243–5252.

Iskakov, K., Burkov, E., Lempitsky, V., & Malkov, Y. (2019). Learnable triangulation of human pose. Proceedings of the IEEE/CVF International Conference on Computer Vision, 7718–7727.
Jenni, S., & Favaro, P. (2020). Self-Supervised Multi-View Synchronization Learning for 3D Pose Estimation. Proceedings of the Asian Conference on Computer Vision. 

Jiang, M., Yu, Z., Zhang, Y., Wang, Q., Li, C., & Lei, Y. (2019). Reweighted sparse representation with residual compensation for 3D human pose estimation from a single RGB image. Neurocomputing, 358, 332–343.

Jiang, W., Kolotouros, N., Pavlakos, G., Zhou, X., & Daniilidis, K. (2020). Coherent reconstruction of multiple humans from a single image. Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 5579–5588.

Jin, S., Liu, W., Xie, E., Wang, W., Qian, C., Ouyang, W., & Luo, P. (2020). Differentiable Hierarchical Graph Grouping for Multi-person Pose Estimation. Computer Vision – ECCV 2020, 718–734.

Joo, H., Liu, H., Tan, L., Gui, L., Nabbe, B., Matthews, I., Kanade, T., Nobuhara, S., & Sheikh, Y. (2015). Panoptic studio: A massively multiview system for social motion capture. Proceedings of the IEEE International Conference on Computer Vision, 3334–3342.

Joska, D., Clark, L., Muramatsu, N., Jericevich, R., Nicolls, F., Mathis, A., Mathis, M. W., & Patel, A. (2021). AcinoSet: A 3D Pose Estimation Dataset and Baseline Models for Cheetahs in the Wild. In arXiv [cs.CV]. arXiv. http://arxiv.org/abs/2103.13282

Karashchuk, P., Rupp, K. L., Dickinson, E. S., Walling-Bell, S., Sanders, E., Azim, E., Brunton, B. W., & Tuthill, J. C. (2021). Anipose: A toolkit for robust markerless 3D pose estimation. Cell Reports, 36(13), 109730.

Kearney, S., Li, W., Parsons, M., Kim, K. I., & Cosker, D. (2020). RGBD-dog: Predicting canine pose from RGBD sensors. Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 8336–8345.

Kocabas, M., Huang, C.-H. P., Tesch, J., Muller, L., Hilliges, O., & Black, M. J. (2021). SPEC: Seeing People in the Wild with an Estimated Camera. Proceedings of the IEEE/CVF International Conference on Computer Vision, 11035–11045.

Kocabas, M., Karagoz, S., & Akbas, E. (2019). Self-supervised learning of 3d human pose using multi-view geometry. Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 1077–1086.

Kolotouros, N., Pavlakos, G., Jayaraman, D., & Daniilidis, K. (2021). Probabilistic Modeling for Human Mesh Recovery. Proceedings of the IEEE/CVF International Conference on Computer Vision, 11605–11614.

Kundu, J. N., Revanur, A., Waghmare, G. V., Venkatesh, R. M., & Babu, R. V. (2020). Unsupervised Cross-Modal Alignment for Multi-person 3D Pose Estimation. Computer Vision – ECCV 2020, 35–52.

Kundu, J. N., Seth, S., Rahul, M. V., Rakesh, M., Radhakrishnan, V. B., & Chakraborty, A. (2020). Kinematic-Structure-Preserved Representation for Unsupervised 3D Human Pose Estimation. Proceedings of the AAAI Conference on Artificial Intelligence, 34(07), 11312–11319.

Lassner, C., Romero, J., Kiefel, M., Bogo, F., Black, M. J., & Gehler, P. V. (2017). Unite the people: Closing the loop between 3d and 2d human representations. Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition, 6050–6059.

Li, C., Ghorbani, N., Broomé, S., & Rashid, M. (2021). hSMAL: Detailed Horse Shape and Pose Reconstruction for Motion Pattern Recognition. arXiv Preprint arXiv. https://arxiv.org/abs/2106.10102

Li, C., & Lee, G. H. (2019). Generating multiple hypotheses for 3d human pose estimation with mixture density network. Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 9887–9895.

Lin, J., & Lee, G. H. (2021). Multi-View Multi-Person 3D Pose Estimation with Plane Sweep Stereo. Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 11886–11895.

Li, S., Ke, L., Pratama, K., Tai, Y.-W., Tang, C.-K., & Cheng, K.-T. (2020). Cascaded deep monocular 3D human pose estimation with evolutionary training data. Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 6173–6183.

Liu, S., Huang, X., Fu, N., & Ostadabbas, S. (2021). Heuristic Weakly Supervised 3D Human Pose Estimation in Novel Contexts without Any 3D Pose Ground Truth. In arXiv [cs.CV]. arXiv. http://arxiv.org/abs/2105.10996

Liu, X., Yu, S.-Y., Flierman, N. A., Loyola, S., Kamermans, M., Hoogland, T. M., & De Zeeuw, C. I. (2021). OptiFlex: Multi-Frame Animal Pose Estimation Combining Deep Learning With Optical Flow. Frontiers in Cellular Neuroscience, 15. https://doi.org/10.3389/fncel.2021.621252

Li, W., Liu, H., Ding, R., Liu, M., Wang, P., & Yang, W. (2022). Exploiting Temporal Contexts with Strided Transformer for 3D Human Pose Estimation. IEEE Transactions on Multimedia, 1–1. arXiv.

Li, Y., Li, K., Jiang, S., Zhang, Z., Huang, C., & Da Xu, R. Y. (2020). Geometry-Driven Self-Supervised Method for 3D Human Pose Estimation. Proceedings of the AAAI Conference on Artificial Intelligence, 34, 11442–11449.

Li Z, Sedlar J, Carpentier J, Laptev I, Mansard N, Sivic J. (2019). Estimating 3d motion and forces of person-object interactions from monocular video. Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 8640–8649.

Mahmood, N., Ghorbani, N., Troje, N. F., Pons-Moll, G., & Black, M. J. (2019). AMASS: Archive of Motion Capture as Surface Shapes. Proceedings of the IEEE/CVF International Conference on Computer Vision, 5442–5451.

Marshall, J. D., Klibaite, U., Gellis, A., Aldarondo, D. E., Olveczky, B., & Dunn, T. W. (2021, June 8). The PAIR-R24M Dataset for Multi-animal 3D Pose Estimation. Thirty-Fifth Conference on Neural Information Processing Systems Datasets and Benchmarks Track (Round 1). 

Ma, Z., Yao, Y., Ji, P., & Ma, C. (2021). Learning Transferable Kinematic Dictionary for 3D Human Pose and Shape Reconstruction. In arXiv [cs.CV]. arXiv. http://arxiv.org/abs/2104.00953

Mehta, D., Rhodin, H., Casas, D., Fua, P., Sotnychenko, O., Xu, W., & Theobalt, C. (n.d.). Monocular 3D Human Pose Estimation In The Wild Using Improved CNN Supervision. 2017 International Conference on 3D Vision (3DV), 506–516.

Mitra, R., Gundavarapu, N. B., Sharma, A., & Jain, A. (2020). Multiview-consistent semi-supervised learning for 3d human pose estimation. Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 6907–6916.

Nath, T., Mathis, A., Chen, A. C., Patel, A., Bethge, M., & Mathis, M. W. (2018). Using DeepLabCut for 3D markerless pose estimation across species and behaviors. In Nature protocols (Issue 7, pp. 2152–2176). https://doi.org/10.1038/s41596-019-0176-0

Neverova, N., Thewlis, J., Guler, R. A., Kokkinos, I., & Vedaldi, A. (2019). Slim densepose: Thrifty learning from sparse annotations and motion cues. Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 10915–10923.

Pavlakos, G., Choutas, V., Ghorbani, N., Bolkart, T., Osman, A. A. A., Tzionas, D., & Black, M. J. (2019). Expressive body capture: 3d hands, face, and body from a single image. Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 10975–10985.

Pavllo, D., Feichtenhofer, C., Grangier, D., & Auli, M. (2019). 3d human pose estimation in video with temporal convolutions and semi-supervised training. Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 7753–7762.

Qiu, H., Wang, C., Wang, J., Wang, N., & Zeng, W. (2019). Cross view fusion for 3d human pose estimation. Proceedings of the IEEE International Conference on Computer Vision, 4342–4351.

Rafi, U., Doering, A., Leibe, B., & Gall, J. (2020). Self-supervised Keypoint Correspondences for Multi-person Pose Estimation and Tracking in Videos. Computer Vision – ECCV 2020, 36–52.

Reddy, N. D., Guigues, L., Pishchulin, L., Eledath, J., & Narasimhan, S. G. (2021). TesseTrack: End-to-End Learnable Multi-Person Articulated 3D Pose Tracking. Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 15190–15200.

Remelli, E., Han, S., Honari, S., Fua, P., & Wang, R. (2020). Lightweight Multi-View 3D Pose Estimation through Camera-Disentangled Representation. Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 6040–6049.

Ren, P., Sun, H., Qi, Q., Wang, J., & Huang, W. (2019). SRN: Stacked Regression Network for Real-time 3D Hand Pose Estimation. BMVC. 

Sanakoyeu, A., Khalidov, V., McCarthy, M. S., Vedaldi, A., & Neverova, N. (2020). Transferring dense pose to proximal animal classes. Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 5233–5242.

Sarkar, I., Maji, I., Omprakash, C., Stober, S., Mikulovic, S., & Bauer, P. (2021). Evaluation of deep lift pose models for 3D rodent pose estimation based on geometrically triangulated data. In arXiv [cs.CV]. arXiv. http://arxiv.org/abs/2106.12993

Sengupta, A., Budvytis, I., & Cipolla, R. (2020). Synthetic Training for Accurate 3D Human Pose and Shape Estimation in the Wild. In arXiv [cs.CV]. arXiv. http://arxiv.org/abs/2009.10013

Sigal, L., Balan, A. O., & Black, M. J. (2009). HumanEva: Synchronized Video and Motion Capture Dataset and Baseline Algorithm for Evaluation of Articulated Human Motion. International Journal of Computer Vision, 87(1), 4.

Sun, J. J., Zhao, J., Chen, L.-C., Schroff, F., Adam, H., & Liu, T. (2020). View-Invariant Probabilistic Embedding for Human Pose. Computer Vision – ECCV 2020, 53–70.

Tu, H., Wang, C., & Zeng, W. (2020). VoxelPose: Towards Multi-camera 3D Human Pose Estimation in Wild Environment. Computer Vision – ECCV 2020, 197–212.

Usman, B., Tagliasacchi, A., Saenko, K., & Sud, A. (2021). MetaPose: Fast 3D Pose from Multiple Views without 3D Supervision. In arXiv [cs.CV]. arXiv. http://arxiv.org/abs/2108.04869

Varol, G., Laptev, I., Schmid, C., & Zisserman, A. (2021). Synthetic Humans for Action Recognition from Unseen Viewpoints. International Journal of Computer Vision, 129(7), 2264–2287.

Varol, G., Romero, J., Martin, X., Mahmood, N., Black, M. J., Laptev, I., & Schmid, C. (2017). Learning from Synthetic Humans. Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition, 109–117.

von Marcard, T., Henschel, R., Black, M. J., Rosenhahn, B., & Pons-Moll, G. (2018). Recovering accurate 3d human pose in the wild using imus and a moving camera. Proceedings of the European Conference on Computer Vision (ECCV), 601–617.

Wandt, B., Rudolph, M., Zell, P., Rhodin, H., & Rosenhahn, B. (2021). CanonPose: Self-supervised monocular 3D human pose estimation in the wild. Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 13294–13304.

Wang, K., Lin, L., Jiang, C., Qian, C., & Wei, P. (2019). 3D Human Pose Machines with Self-Supervised Learning. IEEE Transactions on Pattern Analysis and Machine Intelligence, 42(5), 1069–1082.

Wang, Y., Liang, W., Shen, J., Jia, Y., & Yu, L.-F. (2019). A deep Coarse-to-Fine network for head pose estimation from synthetic data. Pattern Recognition, 94, 196–206.

Wehrbein, T., Rudolph, M., Rosenhahn, B., & Wandt, B. (2021). Probabilistic monocular 3d human pose estimation with normalizing flows. Proceedings of the IEEE/CVF International Conference on Computer Vision, 11199–11208.

Weinzaepfel, P., Brégier, R., Combaluzier, H., Leroy, V., & Rogez, G. (2020). DOPE: Distillation of Part Experts for Whole-Body 3D Pose Estimation in the Wild. ECCV 2020, 380–397.

Xie, R., Wang, C., & Wang, Y. (2020). Metafuse: A pre-trained fusion model for human pose estimation. Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 13686–13695.

Xu, H., Bazavan, E. G., Zanfir, A., Freeman, W. T., Sukthankar, R., & Sminchisescu, C. (2020). Ghum & ghuml: Generative 3d human shape and articulated pose models. Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 6184–6193.

Xu, T., & Takano, W. (2021). Graph Stacked Hourglass Networks for 3D Human Pose Estimation. Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 16105–16114.

Yao, Y., Jafarian, Y., & Park, H. S. (2018). MONET: Multiview Semi-supervised Keypoint Detection via Epipolar Divergence. In arXiv [cs.CV]. arXiv. http://arxiv.org/abs/1806.00104

Yoon JS, Shiratori T, Yu SI, Park HS. (2019). Self-supervised adaptation of high-fidelity face models for monocular performance tracking. Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 4601–4609.

Zeng, A., Sun, X., Huang, F., Liu, M., Xu, Q., & Lin, S. (2020). SRNet: Improving Generalization in 3D Human Pose Estimation with a Split-and-Recombine Approach. Computer Vision – ECCV 2020, 507–523.

Zeng, A., Sun, X., Yang, L., Zhao, N., Liu, M., & Xu, Q. (2021). Learning Skeletal Graph Neural Networks for Hard 3D Pose Estimation. Proceedings of the IEEE/CVF International Conference on Computer Vision, 11436–11445.

Zhang, L., Dunn, T., Marshall, J., Olveczky, B., & Linderman, S. (2021). Animal pose estimation from video data with a hierarchical von Mises-Fisher-Gaussian model. International Conference on Artificial Intelligence and Statistics, 2800–2808.

Zhang, X., Wong, Y., Kankanhalli, M. S., & Geng, W. (2019). Unsupervised Domain Adaptation for 3D Human Pose Estimation. Proceedings of the 27th ACM International Conference on Multimedia, 926–934.

Zhang, Z., Wang, C., Qiu, W., Qin, W., & Zeng, W. (2021). AdaFuse: Adaptive Multiview Fusion for Accurate Human Pose Estimation in the Wild. International Journal of Computer Vision, 129(3), 703–718.

Zheng, C., Zhu, S., Mendieta, M., Yang, T., Chen, C., & Ding, Z. (2021). 3D Human Pose Estimation with Spatial and Temporal Transformers. Proceedings of the IEEE/CVF International Conference on Computer Vision, 11656–11665.

Zheng, Z., Yu, T., Liu, Y., & Dai, Q. (2021). PaMIR: Parametric Model-Conditioned Implicit Representation for Image-based Human Reconstruction. IEEE Transactions on Pattern Analysis and Machine Intelligence. https://doi.org/10.1109/TPAMI.2021.3050505

Zimmermann, C., Argus, M., & Brox, T. (2021). Contrastive Representation Learning for Hand Shape Estimation. In arXiv [cs.CV]. arXiv. https://doi.org/10.1109/ICCV.2019.00090

Zimmermann, C., Schneider, A., Alyahyay, M., & Brox, T. (2020). Freipose: A deep learning framework for precise animal motion capture in 3d spaces. BioRxiv. https://doi.org/10.1101/2020.02.27.967620

Zou, L., Huang, Z., Gu, N., Wang, F., Yang, Z., & Wang, G. (2021). GMDN: A lightweight graph-based mixture density network for 3D human pose regression. Computers & Graphics, 95, 115–122.

Zuffi, S., Kanazawa, A., Berger-Wolf, T., & Black, M. J. (2019). Three-D Safari: Learning to Estimate Zebra Pose, Shape, and Texture from Images“ In the Wild.” Proceedings of the IEEE/CVF International Conference on Computer Vision, 5359–5368.

<!-- "...the **go to** statement should be abolished..." [[1]](#1).

## References
<a id="1">[1]</a> 
Dijkstra, E. W. (1968). 
Go to statement considered harmful. 
Communications of the ACM, 11(3), 147-148. -->