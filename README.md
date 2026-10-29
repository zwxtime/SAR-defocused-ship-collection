# SAR-defocused-ship-collection
To evaluate the effectiveness and generalization capability of the proposed PCGNet, we constructed and publicly released a defocused SAR ship single-look complex (SLC) image dataset at https://github.com/zwxtime/SAR-defocused-ship-collection. The dataset contains 4,120 defocused ship SLC patches of size 512 × 512, comprising 2,231 simulated and 1,889 real SAR patches.

1) **Simulated Data:** A total of 2,231 simulated patches are used for training and evaluating PCGNet and the competing methods. The simulations account for complex ship motions, including translational motion and three-dimensional rotations (roll, pitch, and yaw). The radar system and ship motion parameters are listed in Tables I and II, respectively.

2) **Real Data:** A total of 1,889 real SAR patches are collected to evaluate the generalization capability of PCGNet and the competing methods. Specifically, 1,068 defocused ship patches are extracted from 76 GF-3 spotlight-mode scenes in the FAIR-CSAR dataset. For Capella, 522 patches are extracted from 53 publicly available scenes covering harbors, offshore areas, and rivers, including Spotlight, Sliding Spotlight, and Stripmap imaging modes. For ICEYE, 299 patches are extracted from 32 publicly available scenes covering similar maritime and riverine environments, including Spotlight, Dwell, and Stripmap modes.

Overall, the dataset covers C- and X-band SAR observations, multiple imaging modes, and spatial resolutions ranging from 0.32 to 1.2 m, providing diverse conditions for evaluating focusing performance and cross-platform generalization.

Data to be uploaded.
