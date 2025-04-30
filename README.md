# 90803ML-FinalProject
90-803 Machine Learning course final project materials for Team 20
Team members: Eurus Li, Garrett Kent, Kate Munkacsy

Project focus: Predicting average monthly bus ridership

Key data sources:
- monthly bus ridership: https://data.wprdc.org/dataset/prt-monthly-average-ridership-by-route
- monthly bus stop usage: https://data.wprdc.org/dataset/prt-transit-stop-usage
- monthly average temperature: https://www.weather.gov/media/pbz/records/histemp.pdf
- monthly total precipitation: https://www.weather.gov/media/pbz/records/hisprec.pdf
- Census demographics: https://data.census.gov/table/ACSDP5Y2023.DP05?t=Age+and+Sex&g=050XX00US42003,42003$8600000
- Census commuter information: https://data.census.gov/table/ACSST5Y2023.S0801?t=Age+and+Sex&g=050XX00US42003,42003$8600000&tp=true

Scripts:
- 0_initial_data_import: import, prepare, and join data on monthly bus ridership, monthly bus stop usage, and monthly weather 
- 1_EDA: calculate descriptive statistics and visualize data
- 2_feature_generation: build feature matrix for monthly bus ridership data
- 3a_model_development: train and evaluate various models to predict monthly bus ridership
- 3b_model_development_with_PCA: (experimental) try incorporating PCA into model development
- 4_neural_network_model: train and evaluate neural network to predict monthly bus ridership
- 5_additional_analyses: explore Census data for ZIP codes in which the routes with the top 10 highest ridership predictions operate
