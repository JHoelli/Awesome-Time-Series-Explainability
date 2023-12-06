# Awesome-Time-Series-Explainability
A list of XAI for time series. This list focuses (currently) on Post-Hoc Explainability for time series data, including paper and github links. The list is expanded and updated gradually. Feel Free to update missing or new paper.
<img src="https://github.com/fzi-forschungszentrum-informatik/TSInterpret/blob/main/docs/img/Post-Hoc.png" width="600"
/>

## Outline 
- [Surveys](https://github.com/JHoelli/Awesome-Time-Series-Explainability#Surveys)
- [Libraries ](https://github.com/JHoelli/Awesome-Time-Series-Explainability#Libraries)
- [Classification ](https://github.com/JHoelli/Awesome-Time-Series-Explainability#Classification)
- [Regression / Forecasting](https://github.com/JHoelli/Awesome-Time-Series-Explainability#Regression-/-Forecasting)
- [Classification and Regression / Forcasting](https://github.com/JHoelli/Awesome-Time-Series-Explainability#Classification-and-Regression-/-Forcasting)
- [Benchmarking and Evaluation](https://github.com/JHoelli/Awesome-Time-Series-Explainability#Benchmarking-and-Evaluation)
- [Ante-Hoc Explanations](https://github.com/JHoelli/Awesome-Time-Series-Explainability#Ante-Hoc-Explanation)

## Surveys
- [**Post Hoc Explainability for Time Series Classification: Toward a signal processing perspective**](https://ieeexplore.ieee.org/document/9810094) , (2022) by *R. Mochaourab, A. Venkitaraman, I. Samsten, P. Papapetrou and C. R. Rojas*
- [**Explainable AI for time series classification: a review, taxonomy and research directions**](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9895252) , (2022) by *A Theissler, F Spinnato, U Schlegel, R Guidotti*
- [**Explainable artificial intelligence (xai) on timeseries data: A survey**](https://arxiv.org/abs/2104.00950) , (2021) by *Rojat, T., Puget, R., Filliat, D., Del Ser, J., Gelin, R., & Díaz-Rodríguez, N.*
- [**XAI Methods for Neural Time Series Classification: A Brief Review**](https://arxiv.org/abs/2108.08009) , (2021) by *Simic, I., Sabol, V., Veas, E.*

  
## Libraries 

- [**TSInterpret: A Python Package for the Interpretability of Time Series Classification**](https://joss.theoj.org/papers/10.21105/joss.05220.pdf) (2023) by *Höllig, J., Kulbach, C., & Thoma, S.* [https://github.com/fzi-forschungszentrum-informatik/TSInterpret](https://github.com/fzi-forschungszentrum-informatik/TSInterpret), ![](https://img.shields.io/github/stars/fzi-forschungszentrum-informatik/TSInterpret.svg?style=social)
- [**Time Interpret: a Unified Model Interpretability Library for Time Series**](https://arxiv.org/abs/2306.02968) (2023) by *Enguehard, J.* [https://github.com/josephenguehard/time_interpret](https://github.com/josephenguehard/time_interpret), ![](https://img.shields.io/github/stars/josephenguehard/time_interpret.svg?style=social)

## Classification 

  

### Feature Attribution
- [**Explaining time series classifiers through meaningful perturbation and optimisation**](https://doi.org/10.1016/j.ins.2023.119334), (2023), by *H Meng, C Wagner, I Triguero* [https://github.com/menghan1994/ETSC_through_Meainingful_Perturbation_and_Optimisation](https://github.com/menghan1994/ETSC_through_Meainingful_Perturbation_and_Optimisation), ![](https://img.shields.io/github/stars/menghan1994/ETSC_through_Meainingful_Perturbation_and_Optimisation.svg?style=social)
- [**Explainable AI for Time Series via Virtual Inspection Layers**](https://arxiv.org/pdf/2303.06365) , (2023) by *Vielhaben, J., Lapuschkin, S., Montavon, G., & Samek, W.*
- [**LIMESegment: Meaningful, Realistic Time Series Explanations**](https://proceedings.mlr.press/v151/sivill22a.html) , (2022) by *Sivill, T., & Flach, P.*, [https://github.com/TortySivill/LIMESegment](https://github.com/TortySivill/LIMESegment), ![](https://img.shields.io/github/stars/TortySivill/LIMESegment.svg?style=social)
- [**TSInsight: A local-global attribution framework for interpretability in time series data**](https://www.mdpi.com/1424-8220/21/21/7373)(2021) by *Siddiqui, S. A., Mercier, D., Dengel, A., & Ahmed, S.*
- [**Benchmarking Deep Learning Interpretability in Time Series Predictions**](https://arxiv.org/abs/2010.13924) (2020) by *Ismail, A. A., Gunady, M., Corrada Bravo, H., & Feizi, S.* [https://github.com/ayaabdelsalam91/TS-Interpretability-Benchmark](https://github.com/ayaabdelsalam91/TS-Interpretability-Benchmark), ![](https://img.shields.io/github/stars/ayaabdelsalam91/TS-Interpretability-Benchmark.svg?style=social)
- [**What went wrong and when? Instance-wise feature importance for time-series black-box models**](https://papers.nips.cc/paper_files/paper/2020/file/08fa43588c2571ade19bc0fa5936e028-Paper.pdf) (2020) by *Tonekaboni, S., Joshi, S., Campbell, K., Duvenaud, D. K., & Goldenberg, A.* [https://github.com/sanatonek/time_series_explainability](https://github.com/sanatonek/time_series_explainability), ![](https://img.shields.io/github/stars/sanatonek/time_series_explainability.svg?style=social)
- [**Agnostic Local Explanation for Time Series Classification**](https://ieeexplore.ieee.org/document/8995349) (2019) by *Guillemé, M., Masson, V., Rozé, L., & Termier, A. *
- [**timeXplain -- A Framework for Explaining the Predictions of Time Series Classifiers**](https://arxiv.org/abs/2007.07606) (2019) by *Mujkanovic, F., Doskoč, V., Schirneck, M., Schäfer, P., & Friedrich, T.* [https://github.com/LoadingByte/timeXplain](https://github.com/LoadingByte/timeXplain), ![](https://img.shields.io/github/stars/LoadingByte/timeXplain.svg?style=social)
- [**Tsxplain: Demystification of dnn decisions for time-series using natural language and statistical features**](https://link.springer.com/chapter/10.1007/978-3-030-30493-5_43) (2019) by *Munir, M., Siddiqui, S. A., Küsters, F., Mercier, D., Dengel, A., & Ahmed, S.* 
- [**MTEX-CNN: Multivariate Time Series EXplanations for Predictions with Convolutional Neural Networks**](https://ieeexplore.ieee.org/document/8970899) (2019) by *Assaf, R., Giurgiu, I., Bagehorn, F., & Schumann, A.*

### Counterfactuals 
- [**Attention-Based Counterfactual Explanation for Multivariate Time Series**](https://link.springer.com/chapter/10.1007/978-3-031-39831-5_26) (2023) by *Li, P., Boubrahimi, S. F., & Hamdi, S. M.* [https://sites.google.com/view/attention-based-cf](https://sites.google.com/view/attention-based-cf)
- [**Shapelet-Based Counterfactual Explanations for Multivariate Time Series**](https://arxiv.org/abs/2208.10462) (2022) by *Bahri, O., Boubrahimi, S. F., & Hamdi, S. M.* [https://github.com/omarbahri/SETS](https://github.com/omarbahri/SETS), ![](https://img.shields.io/github/stars/omarbahri/SETS.svg?style=social)
- [**TSEvo: Evolutionary counterfactual explanations for time series classification**](https://ieeexplore.ieee.org/abstract/document/10069160) (2022) by *Höllig, J., Kulbach, C., & Thoma, S.* [https://github.com/JHoelli/TSEvo](https://github.com/JHoelli/TSEvo), ![](https://img.shields.io/github/stars/JHoelli/TSEvo.svg?style=social)
- [**Counterfactual explanations for multivariate time series**](https://ieeexplore.ieee.org/document/9462056) (2021) by *Ates, E., Aksar, B., Leung, V. J., & Coskun, A. K.* [https://github.com/peaclab/CoMTE](https://github.com/peaclab/CoMTE), ![](https://img.shields.io/github/stars/peaclab/CoMTE.svg?style=social)
- [**Motif-Guided Time Series Counterfactual Explanations**](https://link.springer.com/chapter/10.1007/978-3-031-37731-0_16) (2022) by *Li, P., Boubrahimi, S. F., & Hamdi, S. M.* [https://github.com/Luckilyeee/Motif-guided-counterfactual-explanation](https://github.com/Luckilyeee/Motif-guided-counterfactual-explanation), ![](https://img.shields.io/github/stars/Luckilyeee/Motif-guided-counterfactual-explanation.svg?style=social)
- [**Instance-based Counterfactual Explanations for Time Series Classification**](https://arxiv.org/abs/2009.13211) (2020) by *Delaney, E., Greene, D., & Keane, M. T.* [https://github.com/e-delaney/Instance-Based_CFE_TSC](https://github.com/e-delaney/Instance-Based_CFE_TSC), ![](https://img.shields.io/github/stars/e-delaney/Instance-Based_CFE_TSC.svg?style=social)

### Frameworks (Multiple Explanation Types)
- [**Understanding Any Time Series Classifier with a Subsequence-based Explainer**](https://dl.acm.org/doi/pdf/10.1145/3624480) , (2023) by *Spinnato, F., Guidotti, R., Monreale, A., Nanni, M., Pedreschi, D., & Giannotti, F.* [https://github.com/fspinna/lasts](https://github.com/fspinna/lasts), ![](https://img.shields.io/github/stars/fspinna/lasts.svg?style=social)
- [**TimeSHAP: Explaining Recurrent Models through Sequence Perturbations**](https://arxiv.org/abs/2012.00073), (2020) by *Bento, J., Saleiro, P., Cruz, A. F., Figueiredo, M. A., & Bizarro, P.*, [https://github.com/feedzai/timeshap](https://github.com/feedzai/timeshap), ![](https://img.shields.io/github/stars/feedzai/timeshap.svg?style=social)
  


## Regression / Forecasting

- [**TsSHAP: Robust model agnostic feature-based explainability for univariate time series forecasting**](https://arxiv.org/pdf/2303.12316.pdf) (2023) by *Raykar, V. C., Jati, A., Mukherjee, S., Aggarwal, N., Sarpatwar, K., Ganapavarapu, G., & Vaculin, R.*
- [**Counterfactual Explanations for Time Series Forecasting**](https://arxiv.org/abs/2310.08137) (2023) by *Wang, Z., Miliou, I., Samsten, I., & Papapetrou, P.*  [https://github.com/zhendong3wang/counterfactual-explanations-for-forecasting](https://github.com/zhendong3wang/counterfactual-explanations-for-forecasting), ![](https://img.shields.io/github/stars/zhendong3wang/counterfactual-explanations-for-forecasting.svg?style=social)
- [**TEMPORAL DEPENDENCIES IN FEATURE IMPORTANCE FOR TIME SERIES PREDICTION**](https://www.cs.toronto.edu/~mvolkovs/ICLR23_WinIT.pdf) (2023) by *Leung, K. K., Rooke, C., Smith, J., Zuberi, S., & Volkovs, M.*  [https://github.com/layer6ai-labs/WinIT](https://github.com/layer6ai-labs/WinIT), ![](https://img.shields.io/github/stars/layer6ai-labs/WinIT.svg?style=social)
- [**TS-MULE: Local Interpretable Model-Agnostic Explanations for Time Series Forecast Models**](https://link.springer.com/chapter/10.1007/978-3-030-93736-2_1) (2021) by *Schlegel, U., Vo, D. L., Keim, D. A., & Seebacher, D.*  [https://github.comdbvis-ukon/ts-mule](https://github.com/dbvis-ukon/ts-mule), ![](https://img.shields.io/github/stars/dbvis-ukon/ts-mule.svg?style=social)
- [**Explaining time series predictions with dynamic masks**](http://proceedings.mlr.press/v139/crabbe21a/crabbe21a.pdf) (2021) by *Crabbé, J., & Van Der Schaar, M.*  [https://github.com/JonathanCrabbe/Dynamask](https://github.com/JonathanCrabbe/Dynamask), ![](https://img.shields.io/github/stars/JonathanCrabbe/Dynamask.svg?style=social)
- [**Series saliency: Temporal interpretation for multivariate time series forecasting**](https://arxiv.org/pdf/2012.09324.pdf) (2020) by *Pan, Q., Hu, W., & Zhu, J.*


## Classification and Regression / Forcasting 
- [**Tsviz: Demystification of deep learning models for time-series analysis**](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8695734) (2019) by *Siddiqui, S. A., Mercier, D., Munir, M., Dengel, A., & Ahmed, S.* [https://github.com/shoaibahmed/TSViz-Core](https://github.com/shoaibahmed/TSViz-Core), ![](https://img.shields.io/github/stars/shoaibahmed/TSViz-Core.svg?style=social)
- [**Learning Perturbations to Explain Time Series Predictions**](https://arxiv.org/pdf/2305.18840.pdf) (2023) by *Enguehard, J.* [https://github.com/josephenguehard/time_interpret](https://github.com/josephenguehard/time_interpret), ![](https://img.shields.io/github/stars/josephenguehard/time_interpret.svg?style=social)


## Benchmarking and Evaluation
- [**Evaluation of post-hoc interpretability methods in time-series classification**](https://www.nature.com/articles/s42256-023-00620-w), (2023) by *Turbé, H., Bjelogrlic, M., Lovis, C. et al.*, [https://github.com/hturbe/InterpretTime](https://github.com/hturbe/InterpretTime), ![](https://img.shields.io/github/stars/mlgig/amee.svg?style=social)
- [**A Deep Dive into Perturbations as Evaluation Technique for Time Series XAI**](https://arxiv.org/pdf/2307.05104), (2023) by *Schlegel, U., & Keim, D. A.*
- [**Introducing the Attribution Stability Indicator: a Measure for Time Series XAI Attributions**](https://arxiv.org/abs/2310.04178), (2023) by *Schlegel, U., & Keim, D. A. *
- [**Robust Framework for Explanation Evaluation in Time Series Classification**](https://arxiv.org/abs/2306.05501), (2023) by *Nguyen, T. T., Nguyen, T. L., & Ifrim, G.* [https://github.com/mlgig/amee](https://github.com/mlgig/amee), ![](https://img.shields.io/github/stars/mlgig/amee.svg?style=social)
- [**Evaluating Explanation Methods for Multivariate Time Series Classification**](https://arxiv.org/abs/2308.15223), (2023) by *Serramazza, D. I., Nguyen, T. T., Nguyen, T. L., & Ifrim, G. * [https://github.com/mlgig/Evaluating-Explanation-Methods-for-MTSC](https://github.com/mlgig/Evaluating-Explanation-Methods-for-MTSC), ![](https://img.shields.io/github/stars/mlgig/Evaluating-Explanation-Methods-for-MTSC.svg?style=social)
- [**XTSC-Bench: Quantitative Benchmarking for Explainers on Time Series Classification**](https://arxiv.org/pdf/2310.14957.pdf), (2023) by *Höllig, J., Thoma, S., & Grimm, F.* [https://github.com/JHoelli/XTSC-Bench](https://github.com/JHoelli/XTSC-Bench), ![](https://img.shields.io/github/stars/JHoelli/XTSC-Bench.svg?style=social)
- [**Time to Focus: A Comprehensive Benchmark Using Time Series Attribution Methods**](https://arxiv.org/abs/2202.03759), (2022) by *Mercier, D., Bhatt, J., Dengel, A., & Ahmed, S.*
- [**Towards a rigorous evaluation of XAI methods on time series**](https://ieeexplore.ieee.org/document/9022428), (2019) by *Schlegel, U., Arnout, H., El-Assady, M., Oelke, D., & Keim, D. A.*


## Ante-Hoc Explanation
While this repository mostly focuses on post-hoc explanations - i.e. introducing the explanations after the training of the predictor, this section includes some approches that include explanability into the predicors design (e.g., via architecture or training).
### Classification
- [**Xcm: An explainable convolutional neural network for multivariate time series classification**](https://www.mdpi.com/2227-7390/9/23/3137) (2021) by *Fauvel, K., Lin, T., Masson, V., Fromont, É., & Termier, A.* [https://github.com/XAIseries/XCM](https://github.com/XAIseries/XCM), ![](https://img.shields.io/github/stars/XAIseries/XCM.svg?style=social)
- [**Explaining Deep Classification of Time-Series Data with Learned Prototypes**](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8050893/) (2019) by *Gee, A. H., Garcia-Olano, D., Ghosh, J., & Paydarfar, D.* [https://github.com/alangee/ijcai19-ts-prototypes](https://github.com/alangee/ijcai19-ts-prototypes), ![](https://img.shields.io/github/stars/alangee/ijcai19-ts-prototypes.svg?style=social)
- [**Medical Time Series Classification with Hierarchical Attention-based Temporal
Convolutional Networks: A Case Study of Myotonic Dystrophy Diagnosis**](https://openaccess.thecvf.com/content_CVPRW_2019/papers/Explainable%20AI/Lin_Medical_Time_Series_Classification_with_Hierarchical_Attention-based_Temporal_Convolutional_Networks_CVPRW_2019_paper.pdf) (2019) by *Lin, L., Xu, B., Wu, W., Richardson, T. W., & Bernal, E. A.*
- [**Explainable Failure Predictions with RNN Classifiers based on Time Series Data**](https://arxiv.org/abs/1901.08554) (2019) by *Giurgiu, I., & Schumann, A.*
- [**Retain: An interpretable predictive model for healthcare using reverse time attention mechanism**](https://proceedings.neurips.cc/paper/2016/hash/231141b34c82aa95e48810a9d1b33a79-Abstract.html) (2016) by *Choi, E., Bahadori, M. T., Sun, J., Kulas, J., Schuetz, A., & Stewart, W.* [https://github.com/mp2893/retain](https://github.com/mp2893/retain), ![](https://img.shields.io/github/stars/mp2893/retain.svg?style=social)

### Forecasting
- [**Temporal fusion transformers for interpretable multi-horizon time series forecasting**](https://www.sciencedirect.com/science/article/pii/S0169207021000637) (2021) by *Lim, B., Arık, S. Ö., Loeff, N., & Pfister, T.*
- [**Exploring interpretable LSTM neural networks over multi-variable data**](http://proceedings.mlr.press/v97/guo19b.html) (2019) by *Guo, Tian, Tao Lin, and Nino Antulov-Fantulin* [https://github.com/weilai0980/IMV-LSTM](https://github.com/weilai0980/IMV-LSTM), ![](https://img.shields.io/github/stars/weilai0980/IMV-LSTM.svg?style=social)
- [**Medical Time Series Classification with Hierarchical Attention-based Temporal
- [**A memory-network based solution for multivariate time-series forecasting**](https://arxiv.org/abs/1809.02105) (2018) by *Chang, Y. Y., Sun, F. Y., Wu, Y. H., & Lin, S. D.*

