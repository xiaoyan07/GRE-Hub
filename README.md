<h2 align="center">Global Road Extraction: Open-Source Solutions & Resources (GRE-Hub)</h2>

<h5 align="center"> <a href="https://scholar.google.com/citations?user=MDA37NMAAAAJ&hl=zh-CN">Xiaoyan LU</a> and
<a href="https://scholar.google.com/citations?user=SbbCxE8AAAAJ&hl=zh-CN">Qihao WENG</a></h5>

[[`Paper`]()] 


**Open-Source Road Extraction Datasets**

| Name                                                                                  | Year    | Resolution (m/pixel)| Buffer width (m) | Size (pixels) | Images(train/val/test) | Paper                                                                            |
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

**Open-Source Code for Road Extraction **

| Name                                                  | Paper                                                                                                                                                                                           |
|:------------------------------------------------------|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| DeepRoadMapper (Máttyus et al., 2017)                 | [Paper](https://github.com/mitroadmaps/roadtracer/tree/master/deeproadmapper)                                                                                                                   |
| RoadTracer (Bastani et al., 2018)                     | [Paper](https://github.com/mitroadmaps/roadtracer)                                                                                                                                              |
| D-LinkNet (Zhou et al., 2018)                         | [Paper](https://github.com/zlckanata/DeepGlobe-Road-Extraction-Challenge)                                                                                                                       |
| Sun et al.(Sun et al., 2019)                          | [Paper](https://github.com/suniique/Leveraging-Crowdsourced-GPS-Data-for-Road-Extraction-from-Aerial-Imagery)                                                                                   |
| OrientationLearning (Batra et al., 2019)              | [Paper](https://github.com/anilbatra2185/road_connectivity)                                                                                                                                     |
| CRESIv2 (Etten, 2020)                                 | [Paper](https://github.com/avanetten/cresi)                                                                                                                                                     |
| Sat2Graph (He et al., 2020)                           | [Paper](https://github.com/songtaohe/Sat2Graph)                                                                                                                                                 |
| VecRoad (Tan et al., 2020)                            | [Paper](https://github.com/tansor/VecRoad)                                                                                                                                                      |
| Wei et al. (Wei et al., 2020)                         | [Paper](https://github.com/astro-ck/Road-Extraction)                                                                                                                                            |
| RoadDA (Zhang et al., 2021)                           | [Paper](https://github.com/LANMNG/RoadDA)                                                                                                                                                       |
| Bastani et al.(Bastani and Madden, 2021)              | [Paper](https://github.com/favyen/muno21)                                                                                                                                                       |
| ScRoadExtractor (Wei and Ji, 2021)                    | [Paper](https://github.com/weiyao1996/ScRoadExtractor)                                                                                                                                          |
| CoANet (Mei et al., 2021)                             | [Paper](https://github.com/mj129/CoANet)                                                                                                                                                        |
| RNGDet (Xu et al., 2022)                              | [Paper](https://github.com/TonyXuQAQ/RNGDetPlusPlus)                                                                                                                                            |
| CMMPNet (Liu et al., 2022a)                           | [Paper](https://github.com/liulingbo918/CMMPNet)                                                                                                                                                |
| SPIN Road Mapper (Bandara et al., 2022)               | [Paper](https://github.com/wgcban/SPIN_RoadMapper)                                                                                                                                              |
| RNGDet++ (Xu et al., 2023b)                           | [Paper](https://github.com/TonyXuQAQ/RNGDetPlusPlus)                                                                                                                                            |
| SemiRoadExNet (Chen et al., 2023b)                    | [Paper](https://github.com/hchen118/SemiRoadExNet)                                                                                                                                              |
| Iqbal et al. (Iqbal et al., 2023)                     | [Paper](https://github.com/engrjavediqbal/roads-segmentation-adaptation)                                                                                                                        |
| MSMDFF-Net (Wang et al., 2024)                        | [Paper](https://github.com/wycloveinfall/MSMDFF-NET)                                                                                                                                            |
| SAM-Road (Hetang et al., 2024)                        | [Paper](https://github.com/htcr/sam_road)                                                                                                                                                       |
| IS-RoadDet (Yang et al., 2024a)                       | [Paper](https://github.com/WanderRainy/IS-Road)                                                                                                                                                 |
| GRNetSF_GRSet (Lu et al., 2024)                       | [Paper](https://github.com/xiaoyan07/GRNet_GRSet)                                                                                                                                               |
| SAM_MLoRA (Lu and Weng, 2024)                         | [Paper](https://github.com/xiaoyan07/SAM_MLoRA)                                                                                                                                                 |
| SAM-Road++ (Yin et al., 2024)                         | [Paper](https://github.com/earth-insights/samroadplus)                                                                                                                                          |
<br />