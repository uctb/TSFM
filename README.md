# Foundation Model for Dynamical System
This repo focus on progress on Time Series Foundation Model.

- [Foundation Model for Dynamical System](#foundation-model-for-dynamical-system)
  - [Time Series Foundation Model](#time-series-foundation-model)
    - [Survey\&Benchmark](#surveybenchmark)
      - [2023](#2023)
      - [2024](#2024)
    - [Work](#work)
      - [2024](#2024-1)
      - [2023](#2023-1)
    - [Dataset](#dataset)
  - [Spatio-temporal Foundation Model \& Multi-variate Time Series Foundation Model](#spatio-temporal-foundation-model--multi-variate-time-series-foundation-model)
    - [Survey\&Benchmark](#surveybenchmark-1)
    - [Work](#work-1)
    - [Dataset](#dataset-1)
  - [Foundation Model for Dynamic System](#foundation-model-for-dynamic-system)
    - [Survey\&Benchmark](#surveybenchmark-2)
    - [Work](#work-2)
    - [Dataset](#dataset-2)

<table>
  <tr>
    <th rowspan="2">project</th>
    <th colspan="4">Availability</th>
    <th colspan="1" rowspan="2">Documentation</th>
    <th colspan="3">Code</th>
    <th colspan="3">Data</th>
  </tr>
  <tr>
    <td>code</td>
    <td>weight</td>
    <td>data</td>
    <td>hyperparamters</td>
    <td>pre-train</td>
    <td>fine-tune</td>
    <td>zero-shot</td>
    <td>数据2</td>
    <td>数据3</td>
    <td>数据3</td>
  </tr>
</table>

## Time Series Foundation Model
### Survey&Benchmark

#### 2023

- **Large models for time series and spatio-temporal data: A survey and outlook.**

#### 2024

- **A Survey of Deep Learning and Foundation Models for Time Series Forecasting.** *Miller(University of Georgia), John A., Mohammed Aldosari, Farah Saeed, Nasid Habib Barna, Subas Rana, I. Budak Arpinar, and Ninghao Liu.* [link](https://arxiv.org/abs/2401.13912) :link:18
- **Foundation Models for Time Series Analysis: A Tutorial and Survey.** *Yuxuan Liang(The Hong Kong University of Science and Technology(Guangzhou), Haomin Wen(Beijing Jiaotong University))* [link](https://arxiv.org/pdf/2403.14735) :link:26
- **FoundTS: Comprehensive and Unified Benchmarking of Foundation Models for Time Series Forecasting.** *Zhe Li, Xiangfei Qiu, Peng Chen, Yihang Wang, Hanyin Cheng, Yang Shu, Jilin Hu, Chenjuan Guo, Aoying Zhou, Qingsong Wen, Christian S. Jensen, Bin Yang* [link](https://arxiv.org/abs/2410.11802) [code]
- **GIFT-Eval: A Benchmark For General Time Series Forecasting Model Evaluation.** *Taha Aksu, Gerald Woo, Juncheng Liu, Xu Liu, Chenghao Liu, Silvio Savarese, Caiming Xiong, Doyen Sahoo.* [link](https://arxiv.org/abs/2410.10393)

### Work

#### 2024

- **Exploring Representations and Interventions in Time Series Foundation Models.** *Michał Wiliński, Mononito Goswami, Willa Potosnak, Nina Żukowska, Artur Dubrawski* [link](https://arxiv.org/abs/2409.12915) :link: 9

- **Towards Neural Scaling Laws for Time Series Foundation Models.** *Qingren Yao, Chao-Han Huck Yang, Renhe Jiang, Yuxuan Liang, Ming Jin, Shirui Pan* [link](https://arxiv.org/abs/2410.12360) :link: 1

- **UniMTS: Unified Pre-training for Motion Time Series.** *Xiyuan Zhang, Diyan Teng, Ranak Roy Chowdhury, Shuheng Li, Dezhi Hong, Rajesh K. Gupta, Jingbo Shang.* [link](https://arxiv.org/abs/2410.19818) :link:14 [code](https://github.com/xiyuanzh/UniMTS) ![](https://img.shields.io/github/stars/xiyuanzh/UniMTS?color=yellow)
- **UNITS: A Unified Multi-Task Time Series Model.** *Shanghua Gao, Teddy Koker, Owen Queen, Thomas Hartvigsen, Theodoros Tsiligkaridis, Marinka Zitnik.* [link](https://arxiv.org/pdf/2403.00131) :link:14 [code](https://github.com/mims-harvard/UniTS) ![](https://img.shields.io/github/stars/mims-harvard/UniTS?color=yellow)
- **TIME-FFM: Towards LM-Empowered Federated Foundation Model for Time Series Forecasting.** *Qingxiang Liu, Xu Liu, Chenghao Liu, Qingsong Wen, Yuxuan Liang.* [link](https://arxiv.org/pdf/2405.14252) :link:1
- **S^2IP-LLM: Semantic Space Informed Prompt Learning with LLM for Time Series Forecasting.** *Zijie Pan, Yushan Jiang, Sahil Garg, Anderson Schneider, Yuriy Nevmyvaka, Dongjin Song.* [link](https://openreview.net/pdf?id=qwQVV5R8Y7) :link:10 [code](https://github.com/panzijie825/S2IP-LLM) ![](https://img.shields.io/github/stars/panzijie825/S2IP-LLM?color=yellow)
- **ROSE: Register Assisted General Time Series Forecasting with Decomposed Frequency Learning** *Yihang Wang, Yuying Qiu, Peng Chen, Kai Zhao, Yang Shu, Zhongwen Rao, Lujia Pan, Bin Yang, Chenjuan Guo.* [link](https://arxiv.org/pdf/2405.17478) :link:0
- **In-Context Fine-Tuning for Time-Series Foundation Models** *Abhimanyu Das(Google Research), Matthew Faw, Rajat Sen, Yichen Zhou.* [link](https://arxiv.org/pdf/2410.10469) :link:0
- **Moirai-MoE: Empowering Time Series Foundation Models with Sparse Mixture of Experts** *Xu Liu(Saleforce AI Research, National University of Singapore), Juncheng Liu, Gerald Woo, Taha Aksu, Yuxuan Liang, Roger Zimmermann, Chenghao Liu, Silvio Savarese, Caiming Xiong, Doyen Sahoo.* [link](https://arxiv.org/pdf/2410.10469) :link:0 [code](https://github.com/SalesforceAIResearch/uni2ts/tree/main/project/moirai-moe-1) ![](https://img.shields.io/github/stars/SalesforceAIResearch/uni2ts)
- **FoMo: A Foundation Model for Mobile Traffic Forecasting with Diffusion Model.** *Haoye Chai(Tsinghua University), Shiyuan Zhang, Xiaoqian Qi, Yong Li.* [link](https://arxiv.org/pdf/2410.15322)
- **Time-MoE: Billion-Scale Time Series Foundation Models with Mixture of Experts.** *Xiaoming Shi(princeton University), Shiyu Wang, Yuqi Nie, Dianqi Li, Zhou Ye, Qingsong Wen, and Ming Jin.* [link](https://arxiv.org/pdf/2409.16040) :link:0 [code](https://github.com/Time-MoE/Time-MoE) ![](https://img.shields.io/github/stars/Time-MoE/Time-MoE?color=yellow)
- **Tiny Time Mixers (TTMs): Fast Pre-trained Models for Enhanced Zero/Few-Shot Forecasting of Multivariate Time Series.** *Ekambaram, Vijay(IBM Granite), Arindam Jati, Nam H. Nguyen, Pankaj Dayama, Chandra Reddy, Wesley M. Gifford, and Jayant Kalagnanam.* [link](https://arxiv.org/abs/2401.03955) :link:7 [code](https://github.com/ibm-granite/granite-tsfm) ![](https://img.shields.io/github/stars/ibm-granite/granite-tsfm?color=yellow)
- **Lag-Llama: Towards Foundation Models for Probabilistic Time Series Forecasting.** *Rasul, Kashif, Arjun Ashok, Andrew Robert Williams, Hena Ghonia, Rishika Bhagwatkar, Arian Khorasani, Mohammad Javad Darvishi Bayazi et al.* [link](https://time-series-foundation-models.github.io/lag-llama.pdf) :link:15 [code](https://github.com/time-series-foundation-models/lag-llama/) ![](https://img.shields.io/github/stars/time-series-foundation-models/lag-llama?color=yellow)
- **Unified Training of Universal Time Series Forecasting Transformers.** *Woo, Gerald(Salesforce AI Research), Chenghao Liu, Akshat Kumar, Caiming Xiong, Silvio Savarese, and Doyen Sahoo.* [link](https://arxiv.org/pdf/2402.02592) :link:31 [code](https://github.com/SalesforceAIResearch/uni2ts) ![](https://img.shields.io/github/stars/SalesforceAIResearch/uni2ts?color=yellow)
- **Chronos: Learning the Language of Time Series.** *Das, Abhimanyu(Google Research), Weihao Kong, Rajat Sen, and Yichen Zhou.* [link](https://arxiv.org/abs/2403.07815) :link:46 [code](https://github.com/amazon-science/chronos-forecasting) ![](https://img.shields.io/github/stars/amazon-science/chronos-forecasting?color=yellow)
- **Moment: A family of open time-series foundation models.** *Mononito Goswami, Konrad Szafer, Arjun Choudhry, Yifu Cai, Shuo Li, Artur Dubrawski.* [link](https://arxiv.org/pdf/2402.03885) :link:22 [code](https://github.com/moment-timeseries-foundation-model/moment) ![](https://img.shields.io/github/stars/moment-timeseries-foundation-model/moment?color=yellow)
- **Timer: Generative Pre-trained Transformers Are Large Time Series Models.** *Yong Liu(Tsinghua University), Haoran Zhang, Chenyu Li, Xiangdong Huang, Jianmin Wang, Mingsheng Long.* [link](https://openreview.net/forum?id=bYRYb7DMNo) :link:4 [code](https://github.com/thuml/Large-Time-Series-Model) ![](https://img.shields.io/github/stars/thuml/Large-Time-Series-Model?color=yellow)

#### 2023

- **Large Language Models Are Zero Shot Time Series Forecasters.** *Nate Gruver(NYU), Marc Finzi(CMU), Shikai Qiu(NYU), and Andrew G. Wilson(NYU).* [link](https://arxiv.org/abs/2310.07820) :link:174 [code](https://github.com/ngruver/llmtime) ![](https://img.shields.io/github/stars/ngruver/llmtime?color=yellow)
- **A decoder-only foundation model for time-series forecasting.** *Das, Abhimanyu(Google Research), Weihao Kong, Rajat Sen, and Yichen Zhou.* [link](https://arxiv.org/pdf/2310.10688) :link:55 [code](https://github.com/google-research/timesfm) ![](https://img.shields.io/github/stars/google-research/timesfm?color=yellow)
- **One Fits All: Power General Time Series Analysis by Pretrained LM.** *Tian Zhou, Peisong Niu, xue wang, Liang Sun, Rong Jin.* [link](https://proceedings.neurips.cc/paper_files/paper/2023/file/86c17de05579cde52025f9984e6e2ebb-Paper-Conference.pdf) :link:220 [code](https://github.com/DAMO-DI-ML/NeurIPS2023-One-Fits-All) ![](https://img.shields.io/github/stars/DAMO-DI-ML/NeurIPS2023-One-Fits-All?color=yellow)

### Dataset

## Spatio-temporal Foundation Model & Multi-variate Time Series Foundation Model

### Survey&Benchmark

### Work

### Dataset

## Foundation Model for Dynamic System

### Survey&Benchmark

### Work

### Dataset