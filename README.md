# Shot Boundary Detection (SBD) 

Independent undergraduate research project conducted by Richard Álvarez at Kenyon College on Shot Boundary Detection (SBD)

### Project goals
- explore the industrial practicality of state-of-the-art shot boundary detection (SBD) tools/methods for film and video production
- benchmark those SBD solutions against academically studied video datsets (e.g. TRECVID)
- create a new dataset of video segments and labeled shot boundaries across many different video types (e.g. shorts, films, music videos, presentations, animations, live performances, etc.)

Shot boundary detection (SBD) is considered a substantial process of video browsing and retrieval. SBD aims to detect transitions and their boundaries between consecutive shots; hence, shots with rich information are used in the content-based video indexing and retrieval.

<i>(add more description and motivation)</i>

### Visuals and figures

| Cut | Dissolve | Fade |
|-----|----------|------|
|![](https://videoprocessing.ai/assets/img/benchmarks/sbd/cut.gif)|![](https://videoprocessing.ai/assets/img/benchmarks/sbd/diss.gif)|![](https://videoprocessing.ai/assets/img/benchmarks/sbd/fade.gif)|

Video Hierarchy            |  Shot Transition Types
:-------------------------:|:-------------------------:
![](https://github.com/raulduk3/sbd-experiments/blob/main/figs/downloaded/fig1?raw=true//user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png)  |  ![](https://github.com/raulduk3/sbd-experiments/blob/main/figs/downloaded/fig2?raw=true)

### Algorithms and tools

|Algorithm / Tool                             |Type                                         |Implemented?|Trained?|Benchmarked?|Link                                                |
|---------------------------------------------|---------------------------------------------|------------|--------|------------|----------------------------------------------------|
|SceneBoundaryDetection                       |3D CNN                                       |Yes         |        |            |https://github.com/abramjos/Scene-boundary-detection|
|DeepSBD                                      |Spatio-temporal Convolutional Neural Networks|Yes         |        |            |https://github.com/melgharib/DSBD                   |
|TransNet V2                                  |Neural Network                               |Yes         |        |            |https://github.com/soCzech/TransNetV2               |
|Hectate                                      |Multi-tool                                   |Yes         |        |            |https://github.com/yahoo/hecate                     |
|Walsh-Handamard Motion                       |Algorithm                                    |Yes         |        |            |https://github.com/bvssvni/fwht                     |
|Histogram Mutual Info Harris                 |Algorithm                                    |            |        |            |                                                    |
|Histogram SIFT                               |Algorithm                                    |            |        |            |                                                    |
|SURF Histrogram                              |Algorithm                                    |            |        |            |                                                    |
|Contourlet Transform 3 level of decomposition|Algorithm                                    |            |        |            |                                                    |
|ShotDetection                                |??? (HBA)                                    |Yes         |        |            |https://github.com/yasinyildirim/ShotDetection      |

### Credits
If you find this repository useful, please cite :)
```
Richard Álvarez
IPHS 400 Senior Seminar Spring '23 Kenyon College
```
