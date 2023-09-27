# Topological-Data-Analysis-TDA-
Master's research project - This project is a reimplementation of the paper 'Topological data analysis of financial time series: Landscapes of crashes.' by Marian Gidea and Yuri Katz. The project aims to replicate the results obtained in the paper using Indian stock indices.

Abstract:
The project analyses Indian stock market crashes through a topological lens. The daily log-returns of four Indian stock market indices - SENSEX, BSE SMALLCAP, BSE 100, and BSE 500, were studied. The persistence landscapes and Lp-norms associated with these indices were analysed. The methodology employs topological methods, persistent homology in specific, to identify and quantify topological patterns within multidimensional financial time series data. To conduct the analysis, time-dependent point cloud datasets were extracted using a sliding window technique, and these datasets were then associated with a topological space. The analysis aimed to identify transient loops and measure their persistence within this space. These findings were then encoded into mathematical functions known as "persistence landscapes." The study also sought to assess the temporal changes in these persistence landscapes through their Lp-norms. Furthermore, various statistical properties associated with these norms were studied.

Data: 
The data used in this study are Indian stock market indices: BSE SENSEX, BSE SMALLCAP, BSE-100, BSE-500. The data was obtained from Google Finance from 2 Jan 2004 to 26 July 2023 - a total of 4836 trading days. It was cleaned using the Pandas library of Python. Missing and non-unique date values were removed, and the data was compiled into CSV files.

Reference: 
Gidea, M., & Katz, Y. (2018). Topological data analysis of financial time series: Landscapes of crashes. Physica A: Statistical Mechanics and its Applications, 491, 820-834.
URL: https://arxiv.org/pdf/1703.04385.pdf
DOI: https://doi.org/10.1016/j.physa.2017.09.028

Code References:
1. https://github.com/FloerHogy/FinancialTimeSeriesTDA/blob/main/Project%20TDA/ProjectTDA.ipynb
2. https://github.com/KhalilBergaoui/TDA---Financial-Time-Series-Analysis/blob/main/AitBoumlik_Bergaoui.ipynb
3. https://github.com/GUDHI/tda_financial_time_series_notebook

