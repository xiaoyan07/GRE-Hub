<h2 align="center">Global Road Extraction: Open-Source Solutions & Resources (GRE-Hub)</h2>

<h5 align="center"><a href="https://scholar.google.com/citations?user=MDA37NMAAAAJ&hl=zh-CN">Xiaoyan LU</a> and <a https://scholar.google.com/citations?user=SbbCxE8AAAAJ&hl=zh-CN">Qihao WENG</a></h5>

[[`Paper`]()] 


**Open-Source Road Extraction Datasets**

| Datasets                                                                              | Year    | Resolution (m/pixel)| Buffer width (m) | Size (pixels) | Images(train/val/test) | Paper                                                                            |
|:--------------------------------------------------------------------------------------|:--------|---------------------|------------------|--------------|------------------------|----------------------------------------------------------------------------------|
| [Massachusetts](https://www.cs.toronto.edu/~vmnih/data/)                              | 2013    | 1                   | 7                | 1500×1500    | 1108/14/49             | [Paper](https://www.cs.toronto.edu/~vmnih/docs/Mnih_Volodymyr_PhD_Thesis.pdf)    |
| [RoadTracer ](https://roadmaps.csail.mit.edu/roadtracer/)                             | 2018    | 0.6                 | 6                | 1024×1024    | 2880/-/1920            | [Paper](https://roadmaps.csail.mit.edu/roadtracer.pdf)                           |
| [SpaceNet3](https://spacenet.ai/spacenet-roads-dataset/)                              | 2018    | 0.3                 | 2                | 1300×1300    | 2213/-/567             | [Paper](https://arxiv.org/pdf/1807.01232)                                        |
| [DeepGlobe](https://competitions.codalab.org/competitions/18467#participate-get_data) | 2018    | 0.5                 | -                | 1024×1024    | 4696/-/1530            | [Paper](https://arxiv.org/pdf/1805.06561)                                        |
| [CityScale](https://github.com/songtaohe/Sat2Graph)                                   | 2020    | 1                   | -                | 2048×2048    | 144/9/27               | [Paper](https://arxiv.org/pdf/2007.09547)                                        |
| [CHN6-CUG](https://github.com/CUG-URS/CHN6-CUG-Roads-Dataset)                         | 2021    | 0.5                 | -                | 512×512      | 3608/-/903             | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0924271621000873) |
| [MUNO21 ](https://favyen.com/muno21/)                                                 | 2021    | 1                   | -                | 11133~16520  | 80/-/11                | [Paper](https://favyen.com/muno21.pdf)                                           |
| [LSRV](http://rsidea.whu.edu.cn/resource_LSRV_sharing.htm)                            | 2021    | 0.3~0.6             | -                | 16640~23552  | -/-/3                  | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0924271621000770) |
| [GSRV](https://github.com/xiaoyan07/GRNet_GRSet)                                      | 2024    | 0.3~1.2             | -                | 1024~36,864  | -/-/5743               | [Paper](https://www.tandfonline.com/doi/full/10.1080/10095020.2024.2362760?src=) |
| [GRSet](https://github.com/xiaoyan07/GRNet_GRSet)                                     | 2024    | 1                   | 5                | 1024×1024    | 47,210/-/-             | [Paper](https://www.tandfonline.com/doi/full/10.1080/10095020.2024.2362760?src=) |
| [Global-Scale](https://github.com/earth-insights/samroadplus)                         | 2024    | 1                   | -                | 1024×1024    | 2375/339/624+130       | [Paper](https://arxiv.org/pdf/2411.16733)                                        |

<br />

**Open-Source Code for Road Extraction**

| Year | Methods                                  | Paper | Code                                                                                                            |
|------|:-----------------------------------------|-------|:----------------------------------------------------------------------------------------------------------------|
| 2017 | DeepRoadMapper   |  [(Máttyus et al., 2017)](https://openaccess.thecvf.com/content_ICCV_2017/papers/Mattyus_DeepRoadMapper_Extracting_Road_ICCV_2017_paper.pdf) | [Tensorflow](https://github.com/mitroadmaps/roadtracer/tree/master/deeproadmapper)                              |
| 2018 | RoadTracer         |   [(Bastani et al., 2018)](https://roadmaps.csail.mit.edu/roadtracer.pdf) | [Tensorflow](https://github.com/mitroadmaps/roadtracer)                                                         |
| 2018 | D-LinkNet             |    [(Zhou et al., 2018)](https://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w4/Zhou_D-LinkNet_LinkNet_With_CVPR_2018_paper.pdf) | [Pytorch](https://github.com/zlckanata/DeepGlobe-Road-Extraction-Challenge)                                     |
| 2019 | Sun et al.            |    [(Sun et al., 2019)](https://openaccess.thecvf.com/content_CVPR_2019/papers/Sun_Leveraging_Crowdsourced_GPS_Data_for_Road_Extraction_From_Aerial_Imagery_CVPR_2019_paper.pdf) | [Pytorch](https://github.com/suniique/Leveraging-Crowdsourced-GPS-Data-for-Road-Extraction-from-Aerial-Imagery) |
| 2019 | OrientationLearning |   [(Batra et al., 2019)](https://anilbatra2185.github.io/papers/RoadConnectivityCVPR2019.pdf) | [Pytorch](https://github.com/anilbatra2185/road_connectivity)                                                   |
| 2020 | CRESIv2                   |  [(Etten, 2020)](https://openaccess.thecvf.com/content_WACV_2020/papers/Van_Etten_City-Scale_Road_Extraction_from_Satellite_Imagery_v2_Road_Speeds_and_WACV_2020_paper.pdf) | [Pytorch](https://github.com/avanetten/cresi)                                                                   |
| 2020 | Sat2Graph            |  [(He et al., 2020)](https://arxiv.org/pdf/2007.09547) | [Tensorflow](https://github.com/songtaohe/Sat2Graph)                                                            |
| 2020 | VecRoad               |   [(Tan et al., 2020)](https://openaccess.thecvf.com/content_CVPR_2020/papers/Tan_VecRoad_Point-Based_Iterative_Graph_Exploration_for_Road_Graphs_Extraction_CVPR_2020_paper.pdf) | [Pytorch](https://github.com/tansor/VecRoad)                                                                    |
| 2020 | Wei et al.          |   [ (Wei et al., 2020)](https://ieeexplore.ieee.org/document/9094008) | [Pytorch](https://github.com/astro-ck/Road-Extraction)                                                          |
| 2021 | RoadDA             |  [(Zhang et al., 2021)](https://ieeexplore.ieee.org/abstract/document/9516689) | [Pytorch](https://github.com/LANMNG/RoadDA)                                                                     |
| 2021 | Bastani et al. |   [(Bastani and Madden, 2021)](https://favyen.com/muno21.pdf) | [Pytorch & Tensorflow](https://github.com/favyen/muno21)                                                        |
| 2021 | ScRoadExtractor     |   [ (Wei and Ji, 2021)  ](https://ieeexplore.ieee.org/document/9372390) | [Pytorch](https://github.com/weiyao1996/ScRoadExtractor)                                                        |
| 2021 | CoANet                |   [(Mei et al., 2021) ](https://ieeexplore.ieee.org/document/9563125) | [Pytorch](https://github.com/mj129/CoANet)                                                                      |
| 2022 | RNGDet                 |   [(Xu et al., 2022) ](https://ieeexplore.ieee.org/abstract/document/9810294) | [Pytorch](https://github.com/TonyXuQAQ/RNGDetPlusPlus)                                                          |
| 2022 | CMMPNet               |  [(Liu et al., 2022a)](https://ieeexplore.ieee.org/abstract/document/9696168) | [Pytorch](https://github.com/liulingbo918/CMMPNet)                                                              |
| 2022 | SPIN Road Mapper   |  [(Bandara et al., 2022)](https://ieeexplore.ieee.org/abstract/document/9812134) | [Pytorch](https://github.com/wgcban/SPIN_RoadMapper)                                                            |
| 2023 | RNGDet++               |   [(Xu et al., 2023b)](https://ieeexplore.ieee.org/abstract/document/10093124) | [Pytorch](https://github.com/TonyXuQAQ/RNGDetPlusPlus)                                                          |
| 2023 | SemiRoadExNet      |   [(Chen et al., 2023b)](https://www.sciencedirect.com/science/article/pii/S0924271623000722) | [Pytorch](https://github.com/hchen118/SemiRoadExNet)                                                            |
| 2023 | Iqbal et al.       |    [(Iqbal et al., 2023)](https://www.sciencedirect.com/science/article/pii/S0924271623002952?casa_token=MiZxjJSbIYYAAAAA:7dwQIAnQLlqaG_Q_udcF5WL-hp-GDuVSPna9glp6mfg30LwRndxZPbipTLO1Z5naVqBI2WPSew) | [Pytorch](https://github.com/engrjavediqbal/roads-segmentation-adaptation)                                      |
| 2024 | MSMDFF-Net          |   [(Wang et al., 2024)](https://ieeexplore.ieee.org/document/10477437) | [Pytorch](https://github.com/wycloveinfall/MSMDFF-NET)                                                          |
| 2024 | SAM-Road            |    [(Hetang et al., 2024)](https://openaccess.thecvf.com/content/CVPR2024W/SG2RL/papers/Hetang_Segment_Anything_Model_for_Road_Network_Graph_Extraction_CVPRW_2024_paper.pdf) | [Pytorch](https://github.com/htcr/sam_road)                                                                     |
| 2024 | IS-RoadDet           |    [(Yang et al., 2024a)](https://ieeexplore.ieee.org/abstract/document/10720904) | [Pytorch](https://github.com/WanderRainy/IS-Road)                                                               |
| 2024 | GRNetSF_GRSet         |   [(Lu et al., 2024)](https://www.tandfonline.com/doi/full/10.1080/10095020.2024.2362760) | [Pytorch](https://github.com/xiaoyan07/GRNet_GRSet)                                                             |
| 2024 | SAM_MLoRA          |    [(Lu and Weng, 2024)](https://ieeexplore.ieee.org/abstract/document/10637992) | [Pytorch](https://github.com/xiaoyan07/SAM_MLoRA)                                                               |
| 2024 | SAM-Road++            |   [(Yin et al., 2024)](https://arxiv.org/abs/2411.16733) | [Pytorch](https://github.com/earth-insights/samroadplus)                                                        |
<br />

**Contact**

<a href="https://scholar.google.com/citations?user=MDA37NMAAAAJ&hl=zh-CN">Xiaoyan LU</a>: xiaoyan07.lu@polyu.edu.hk or luxiaoyan@whu.edu.cn