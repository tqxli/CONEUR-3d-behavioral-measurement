# Table 1. Emerging directions in 3D human and animal tracking. (Expanded Version) 

Thematically organized compilation of recent studies that illustrate a roadmap for improvements
in 3D behavioral tracking based on computer vision and deep learning. 

<style>
table th:first-of-type {
    width: 10%;
}
table th:nth-of-type(2) {
    width: 10%;
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
| **Occlusion Robustness** | *2D cross-view fusion + triangulation* | (Qiu et al., 2019) (He et al., 2020) (Xie et al., 2020) (Zhang et al., 2021b) (Lin and Lee, 2021)|  |
| | *2D keypoint triangulation* | (Iskakov et al., 2019) | (Nath et al., 2018)  (Karashchuk et al., 2021) (Liu et al., 2021b)  |
| | *3D volumetric* | (Iskakov et al., 2019) (Tu et al., 2020) | (Zimmermann et al., 2020) (Dunn et al., 2021) | 
| | *temporal information* | (Pavllo et al., 2019)  (Rafi et al., 2020) (Zheng et al., 2021a) (Choi et al., 2021a) (Li et al., 2021b) | (Liu et al., 2021b) (Karashchuk et al., 2021) (Sarkar et al., 2021) (Bala et al., 2021) |
|  | *graphical modeling* | (Cai et al., 2019) (Qiu et al., 2019) (Zeng et al., 2021) (Zou et al., 2021) (Xu and Takano, 2021) | (Zhang et al., 2021a) | 
|  | *explicit occlusion training* | (Cheng et al., 2019) (Cheng et al., 2020) | | 
| **Labeled Training Data Efficiency** | *multi-view consistency* | (Mitra et al., 2020) (Jenni and Favaro, 2020) (Wandt, B., Rudolph, M., Zell, P., Rhodin, H., & Rosenhahn, B., 2021) (Iqbal et al., 2020) (Usman et al., 2021) | (Yao et al., 2018) (Bala et al., 2021) |
|  | *geometric self-supervision* | (Chen et al., 2019a) (Kocabas et al., 2019) (Pavllo et al., 2019) (Li et al., 2020b) (Wang et al., 2020) | | 
|  | *representation learning* | (Jiang et al., 2019) (Chen et al., 2019b) (Kundu et al., 2020a) (Sun et al., 2020) (Zimmermann et al., 2021) | (Bala et al., 2021)|
|  | *constraints* | (Ma et al., 2021) (Liu et al., 2021a) | (Karashchuk et al., 2021) | 
|  | *data augmentation* | (Zeng et al., 2020) (Li et al., 2020a) | |  
| **Flexible, Scalable and Rapid Tracking** | *unsynchronized or uncalibrated cameras* | (Habibie et al., 2019) (Yoon et al., 2019) (Kundu et al., 2020b) (Ma et al., 2021) (Chen et al., 2021) (Kocabas et al., 2021) | | 
| | *real-time tracking* | (Ren et al., 2019) (Hwang et al., 2020) (Remelli et al., 2020) (Choi et al., 2021b) | | 
| **Multi-Subject tracking** | *top-down* | (Dabral et al., 2019) (Dong et al., 2021a) (Huang et al., 2020) (Tu et al., 2020) (Lin and Lee, 2021) (Reddy et al., 2021) | (Bala et al., 2020) (Marshall et al., 2021) |
|  | *bottom-up* |(Jin et al., 2020) (Kundu et al., 2020a) (Dong et al., 2021b) | | 
| | *interaction modeling* | (Hasson et al., 2019) (Li et al., 2019) (Fieraru et al., 2020) | |
| **Richer body Representations** | *dense pose estimation* |(Neverova et al., 2019) (Weinzaepfel et al., 2020)  | (Sanakoyeu et al., 2020) (Bala et al., 2021) |
|  | *body shape reconstruction* |(Pavlakos et al., 2019) (Jiang et al., 2020) (Xu et al., 2020) (Zheng et al., 2021b)  | (Zuffi, S., Kanazawa, A., Berger-Wolf, T., & Black, M. J., 2019) (Biggs et al., 2020a) (Li et al., 2021a) (Deane et al., 2021) | 
| **Pose Uncertainty Quantification** | *multi-pose generation* | (Li and Lee, 2019) (Biggs et al., 2020b)  | |  
| | *probabilistic distribution modeling* | (Kolotouros et al., 2021) (Wehrbein et al., 2021)  | (Zhang et al., 2021a) | 
| **Dataset** | *3D pose* | (Sigal et al., 2009) (Ionescu et al., 2014) (Joo et al., 2015) (Mehta et al., 2016) (Lassner et al., 2017) (von Marcard et al., 2018) | (Bala et al., 2020)  (Kearney et al., 2020) (Joska et al., 2021) (Marshall et al., 2021) |  
| | *3D shape* | (Varol et al., 2017) (Güler et al., 2018) (Mahmood et al., 2019) (Choutas et al., 2020) | (Kearney et al., 2020) |
| | *synthetic data* | (Doersch and Zisserman, 2019) (Wang et al., 2019) (Zhang et al., 2019)  (Sengupta et al., 2020) (Varol et al., 2021) | (Deane et al., 2021) (Bolaños et al., 2021) | 

## References
