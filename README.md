# PVSet_data

PVSet_data was publicly available in paper "[SolarSegNet: A multimodal frequency-aware network for photovoltaic power stations extraction using Sentinel-1 and Sentinel-2 images in coastal China](https://www.sciencedirect.com/science/article/pii/S1569843225003401)" on "[International Journal of Applied Earth Observation and Geoinformation](https://www.sciencedirect.com/journal/international-journal-of-applied-earth-observation-and-geoinformation?utm_campaign=STMJ_1636705839_SC&utm_medium=SRCH&utm_source=B&dgcid=STMJ_1636705839_SC)".

This dataset, which combines Sentinel-1 and Sentinel-2 data, contains multimodal SolarSegNet extracted photovoltaic data for coastal provinces of China. The dataset, based on 10-meter resolution, includes yearly photovoltaic distribution results from 2019 to 2024.


## Citation

Please cite our paper if you use this dataset in your work:

```bibtex
@article{WANG2025104693,
title = {SolarSegNet: A multimodal frequency-aware network for photovoltaic power stations extraction using Sentinel-1 and Sentinel-2 images in coastal China},
journal = {International Journal of Applied Earth Observation and Geoinformation},
volume = {142},
pages = {104693},
year = {2025},
issn = {1569-8432},
doi = {https://doi.org/10.1016/j.jag.2025.104693},
url = {https://www.sciencedirect.com/science/article/pii/S1569843225003401},
author = {Fangxiong Wang and Zhiying Liao and Yingzi Hou and Zhenqi Cui and Yiqi Wang and Jiachen Gong and Haomiao Yu and Junfu Wang and Yuanyi Zhu and Qiao Yu and Jianfeng Zhu},
keywords = {Photovoltaic power stations, Multimodal network, Semantic segmentation, Sentinel images, Coastal China},
abstract = {Current deep learning-based remote sensing methods for photovoltaic (PV) power stations identification primarily focus on inland high-irradiance areas, but exhibit significant limitations in accurately delineating boundary of multi-scale PV power stations in coastal regions. This challenge arises due to frequent cloud and fog coverage in coastal areas, leading to spectral confusion in optical images and complicating accurate PV extraction. To address this issue, this study proposes SolarSegNet, a multimodal semantic segmentation network integrating Sentinel-1 synthetic aperture radar (SAR) and Sentinel-2 multispectral images (MSI) data. SolarSegNet consists of three modules: The adaptive depth separable (ADS) module for local detailed feature extraction, the global-local awareness block (GLAB) for capturing global context, and the adaptive high-frequency awareness block (AHFAB) to mitigate cloud interference. Experiments comparing ten multi-source data combinations indicated that the visible-spectral index-SAR scheme performed optimally. Training and comparative experiments on the newly constructed PV benchmark dataset demonstrated that SolarSegNet significantly improved segmentation accuracy (with IoU, Precision, and Recall enhanced by 1.49%, 0.89%, and 0.90%, respectively) and reduced computational complexity (with parameters decreased by 165.5M and FLOPS reduced by 77.52G). Furthermore, PV regions mapping from 2019 to 2024 reveals continuous growth and a pronounced north-to-south expansion along China’s coast. By 2024, the installed area reached 983.70 km2, marking a 47.20% year-on-year increase. These results confirm SolarSegNet’s effectiveness for coastal PV power stations and its potential application in renewable energy spatial planning. The PV distribution dataset is available at https://github.com/0311lzy/PVSet_data.}
}
