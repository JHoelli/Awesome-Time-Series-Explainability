# Awesome-Time-Series-Explainability
A curated list of XAI for time series. Mostly focused on Post-Hoc Explainability.

## Outline 

## Surveys
- [**Explainable AI for time series classification: a review, taxonomy and research directions**](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9895252) , (2022) by *A Theissler, F Spinnato, U Schlegel, R Guidotti*
- [**Explainable artificial intelligence (xai) on timeseries data: A survey**](https://arxiv.org/abs/2104.00950) , (2021) by *Rojat, T., Puget, R., Filliat, D., Del Ser, J., Gelin, R., & Díaz-Rodríguez, N.*

  
## Libraries 

- [**TSInterpret: A Python Package for the Interpretability of Time Series Classification**](https://joss.theoj.org/papers/10.21105/joss.05220.pdf) (2023) by *Höllig, J., Kulbach, C., & Thoma, S.* [https://github.com/fzi-forschungszentrum-informatik/TSInterpret](https://github.com/fzi-forschungszentrum-informatik/TSInterpret), ![](https://img.shields.io/github/stars/fzi-forschungszentrum-informatik/TSInterpret.svg?style=social)
- [**Time Interpret: a Unified Model Interpretability Library for Time Series**](https://arxiv.org/abs/2306.02968) (2023) by *Enguehard, J.* [https://github.com/josephenguehard/time_interpret](https://github.com/josephenguehard/time_interpret), ![](https://img.shields.io/github/stars/josephenguehard/time_interpret.svg?style=social)

## Classification 

  

### Feature Attribution

- [**Benchmarking Deep Learning Interpretability in Time Series Predictions**](https://arxiv.org/abs/2010.13924) (2020) by *Ismail, A. A., Gunady, M., Corrada Bravo, H., & Feizi, S.* [https://github.com/ayaabdelsalam91/TS-Interpretability-Benchmark](https://github.com/ayaabdelsalam91/TS-Interpretability-Benchmark), ![](https://img.shields.io/github/stars/ayaabdelsalam91/TS-Interpretability-Benchmark.svg?style=social)
- [**Agnostic Local Explanation for Time Series Classification**](https://ieeexplore.ieee.org/document/8995349) (2019) by *Guillemé, M., Masson, V., Rozé, L., & Termier, A. *
- [**TSInsight: A local-global attribution framework for interpretability in time series data**](https://www.mdpi.com/1424-8220/21/21/7373)(2021) by *Siddiqui, S. A., Mercier, D., Dengel, A., & Ahmed, S.*
- [**timeXplain -- A Framework for Explaining the Predictions of Time Series Classifiers**](https://arxiv.org/abs/2007.07606) (2019) by *Mujkanovic, F., Doskoč, V., Schirneck, M., Schäfer, P., & Friedrich, T.* [https://github.com/LoadingByte/timeXplain](https://github.com/LoadingByte/timeXplain), ![](https://img.shields.io/github/stars/LoadingByte/timeXplain.svg?style=social)
- [**Explainable AI for Time Series via Virtual Inspection Layers**](https://arxiv.org/pdf/2303.06365) , (2023) by *Vielhaben, J., Lapuschkin, S., Montavon, G., & Samek, W.*

### Counterfactuals 
- [**TSEvo: Evolutionary counterfactual explanations for time series classification**](https://ieeexplore.ieee.org/abstract/document/10069160) (2022) by *Höllig, J., Kulbach, C., & Thoma, S.* [https://github.com/JHoelli/TSEvo](https://github.com/JHoelli/TSEvo), ![](https://img.shields.io/github/stars/JHoelli/TSEvo.svg?style=social)
- [**Instance-based Counterfactual Explanations for Time Series Classification**](https://arxiv.org/abs/2009.13211) (2020) by *Delaney, E., Greene, D., & Keane, M. T.* [https://github.com/e-delaney/Instance-Based_CFE_TSC](https://github.com/e-delaney/Instance-Based_CFE_TSC), ![](https://img.shields.io/github/stars/e-delaney/Instance-Based_CFE_TSC.svg?style=social)
- [**Counterfactual explanations for multivariate time series**](https://ieeexplore.ieee.org/document/9462056) (2021) by *Ates, E., Aksar, B., Leung, V. J., & Coskun, A. K.* [https://github.com/peaclab/CoMTE](https://github.com/peaclab/CoMTE), ![](https://img.shields.io/github/stars/peaclab/CoMTE.svg?style=social)
- [**Motif-Guided Time Series Counterfactual Explanations**](https://link.springer.com/chapter/10.1007/978-3-031-37731-0_16) (2022) by *Li, P., Boubrahimi, S. F., & Hamdi, S. M.* [https://github.com/Luckilyeee/Motif-guided-counterfactual-explanation](https://github.com/Luckilyeee/Motif-guided-counterfactual-explanation), ![](https://img.shields.io/github/stars/Luckilyeee/Motif-guided-counterfactual-explanation.svg?style=social)
- [**Attention-Based Counterfactual Explanation for Multivariate Time Series**](https://link.springer.com/chapter/10.1007/978-3-031-39831-5_26) (2023) by *Li, P., Boubrahimi, S. F., & Hamdi, S. M.* [https://sites.google.com/view/attention-based-cf](https://sites.google.com/view/attention-based-cf)

### Frameworks (Multiple Explanation Types)
- [**Understanding Any Time Series Classifier with a Subsequence-based Explainer**](https://dl.acm.org/doi/pdf/10.1145/3624480) , (2023) by *Spinnato, F., Guidotti, R., Monreale, A., Nanni, M., Pedreschi, D., & Giannotti, F.* [https://github.com/fspinna/lasts](https://github.com/fspinna/lasts), ![](https://img.shields.io/github/stars/fspinna/lasts.svg?style=social)
  


## Regression / Forecasting

- [**TsSHAP: Robust model agnostic feature-based explainability for univariate time series forecasting**](https://arxiv.org/pdf/2303.12316.pdf) (2023) by *Raykar, V. C., Jati, A., Mukherjee, S., Aggarwal, N., Sarpatwar, K., Ganapavarapu, G., & Vaculin, R.*
- [**TS-MULE: Local Interpretable Model-Agnostic Explanations for Time Series Forecast Models**](https://link.springer.com/chapter/10.1007/978-3-030-93736-2_1) (2021) by *Schlegel, U., Vo, D. L., Keim, D. A., & Seebacher, D.*  [https://github.comdbvis-ukon/ts-mule](https://github.com/dbvis-ukon/ts-mule), ![](https://img.shields.io/github/stars/dbvis-ukon/ts-mule.svg?style=social)
- [**Counterfactual Explanations for Time Series Forecasting**](https://arxiv.org/abs/2310.08137) (2023) by *Wang, Z., Miliou, I., Samsten, I., & Papapetrou, P.*  [https://github.com/zhendong3wang/counterfactual-explanations-for-forecasting](https://github.com/zhendong3wang/counterfactual-explanations-for-forecasting), ![](https://img.shields.io/github/stars/zhendong3wang/counterfactual-explanations-for-forecasting.svg?style=social)
- [**Explaining time series predictions with dynamic masks**](http://proceedings.mlr.press/v139/crabbe21a/crabbe21a.pdf) (2021) by *Crabbé, J., & Van Der Schaar, M.*  [https://github.com/JonathanCrabbe/Dynamask](https://github.com/JonathanCrabbe/Dynamask), ![](https://img.shields.io/github/stars/JonathanCrabbe/Dynamask.svg?style=social)
- [**TEMPORAL DEPENDENCIES IN FEATURE IMPORTANCE FOR TIME SERIES PREDICTION**](https://www.cs.toronto.edu/~mvolkovs/ICLR23_WinIT.pdf) (2023) by *Leung, K. K., Rooke, C., Smith, J., Zuberi, S., & Volkovs, M.*  [https://github.com/layer6ai-labs/WinIT](https://github.com/layer6ai-labs/WinIT), ![](https://img.shields.io/github/stars/layer6ai-labs/WinIT.svg?style=social)
- [**Series saliency: Temporal interpretation for multivariate time series forecasting**](https://arxiv.org/pdf/2012.09324.pdf) (2020) by *Pan, Q., Hu, W., & Zhu, J.*
- [**MTEX-CNN: Multivariate Time Series EXplanations for Predictions with Convolutional Neural Networks**](https://ieeexplore.ieee.org/document/8970899) (2019) by *Assaf, R., Giurgiu, I., Bagehorn, F., & Schumann, A.*

## Classification and Regression / Forcasting 
- [**Tsviz: Demystification of deep learning models for time-series analysis**](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8695734) (2019) by *Siddiqui, S. A., Mercier, D., Munir, M., Dengel, A., & Ahmed, S.* [https://github.com/shoaibahmed/TSViz-Core](https://github.com/shoaibahmed/TSViz-Core), ![](https://img.shields.io/github/stars/shoaibahmed/TSViz-Core.svg?style=social)

  

## Benchmarking and Evaluation

- [**A Deep Dive into Perturbations as Evaluation Technique for Time Series XAI**](https://arxiv.org/pdf/2307.05104), (2023) by *Schlegel, U., & Keim, D. A.*
- [**Introducing the Attribution Stability Indicator: a Measure for Time Series XAI Attributions**](https://arxiv.org/abs/2310.04178), (2023) by *Schlegel, U., & Keim, D. A. *
- [**Robust Framework for Explanation Evaluation in Time Series Classification**](https://arxiv.org/abs/2306.05501), (2023) by *Nguyen, T. T., Nguyen, T. L., & Ifrim, G.* [https://github.com/mlgig/amee](https://github.com/mlgig/amee), ![](https://img.shields.io/github/stars/mlgig/amee.svg?style=social)
- [**Evaluating Explanation Methods for Multivariate Time Series Classification**](https://arxiv.org/abs/2308.15223), (2023) by *Serramazza, D. I., Nguyen, T. T., Nguyen, T. L., & Ifrim, G. * [https://github.com/mlgig/Evaluating-Explanation-Methods-for-MTSC](https://github.com/mlgig/Evaluating-Explanation-Methods-for-MTSC), ![](https://img.shields.io/github/stars/mlgig/Evaluating-Explanation-Methods-for-MTSC.svg?style=social)
- [**XTSC-Bench: Quantitative Benchmarking for Explainers on Time Series Classification**](https://arxiv.org/pdf/2310.14957.pdf), (2023) by *Höllig, J., Thoma, S., & Grimm, F.* [https://github.com/JHoelli/XTSC-Bench](https://github.com/JHoelli/XTSC-Bench), ![](https://img.shields.io/github/stars/JHoelli/XTSC-Bench.svg?style=social)
- [**Time to Focus: A Comprehensive Benchmark Using Time Series Attribution Methods**](https://arxiv.org/abs/2202.03759), (2022) by *Mercier, D., Bhatt, J., Dengel, A., & Ahmed, S.*
- [**Towards a rigorous evaluation of XAI methods on time series**](https://ieeexplore.ieee.org/document/9022428), (2019) by *Schlegel, U., Arnout, H., El-Assady, M., Oelke, D., & Keim, D. A.* 
