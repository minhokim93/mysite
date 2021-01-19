---
title: "Direct Short-Term Forecast of Photovoltaic Power through a Comparative Study between COMS and Himawari-8 Meteorological Satellite Images in a Deep Neural Network"
authors:
- admin
- Hunsoo Song
- Yongil Kim

date: "2020-07-22T00:00:00Z"
doi: "10.3390/rs12152357"

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *MDPI Remote Sensing*
publication_short: MDPI Remote Sensing <span style="color:red;font-style:italic;font-weight:bold;">(2020IF=4.509)</span>

abstract: Meteorological satellite images provide crucial information on solar irradiation and weather conditions at spatial and temporal resolutions which are ideal for short-term photovoltaic (PV) power forecasts. Following the introduction of next-generation meteorological satellites, investigating their application on PV forecasts has become imminent. In this study, Communications, Oceans, and Meteorological Satellite (COMS) and Himawari-8 (H8) satellite images were inputted in a deep neural network (DNN) model for 2 hour (h)- and 1 h-ahead PV forecasts. A one-year PV power dataset acquired from two solar power test sites in Korea was used to directly forecast PV power. H8 was used as a proxy for GEO-KOMPSAT-2A (GK2A), the next-generation satellite after COMS, considering their similar resolutions, overlapping geographic coverage, and data availability. In addition, two different data sampling setups were designed to implement the input dataset. The first setup sampled chronologically ordered data using a relatively more inclusive time frame (6 a.m. to 8 p.m. in local time) to create a two-month test dataset, whereas the second setup randomly sampled 25% of data from each month from the one-year input dataset. Regardless of the setup, the DNN model generated superior forecast performance, as indicated by the lowest normalized mean absolute error (NMAE) and normalized root mean squared error (NRMSE) results in comparison to that of the support vector machine (SVM) and artificial neural network (ANN) models. The first setup results revealed that the visible (VIS) band yielded lower NMAE and NRMSE values, while COMS was found to be more influential for 1 h-ahead forecasts. For the second setup, however, the difference in NMAE results between COMS and H8 was not significant enough to distinguish a clear edge in performance. Nevertheless, this marginal difference and similarity of the results suggest that both satellite datasets can be used effectively for direct short-term PV forecasts. Ultimately, the comparative study between satellite datasets as well as spectral bands, time frames, forecast horizons, and forecast models confirms the superiority of the DNN and offers insights on the potential of transitioning to applying GK2A for future PV forecasts.

# summary: MDPI Remote Sensing <span style="color:red;font-style:italic;font-weight:bold;">(2020IF=4.509)</span>

tags:
- Renewable Energy, Machine Learning, Satellite Image Processing
featured: false


links:
- name: Link
  url: https://www.mdpi.com/2072-4292/12/15/2357

image:
  caption: "Short-term PV forecasting framework"
  focal_point: ""
  preview_only: false
---
