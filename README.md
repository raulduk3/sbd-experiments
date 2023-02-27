# Shot boundary detection (SBD) Experimentation 
IPHS 484 Senior Seminar Project 

Richard Álvarez

Shot boundary detection (SBD) is considered a substantial process of video browsing and retrieval. SBD aims to detect transition and their boundaries between consecutive shots; hence, shots with rich information are used in the content-based video indexing and retrieval.

Video Hierarchy            |  Shot Transition Types
:-------------------------:|:-------------------------:
![](https://github.com/raulduk3/sbd-experiments/blob/main/figs/downloaded/fig1?raw=true//user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png)  |  ![](https://github.com/raulduk3/sbd-experiments/blob/main/figs/downloaded/fig2?raw=true)

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
