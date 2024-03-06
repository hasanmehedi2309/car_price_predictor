
# Car Price Predictor

The project aimed to develop a predictive model using linear regression to forecast the prices of used cars. It leveraged historical data on various attributes of cars such as mileage, age, brand, model, fuel type, and transmission type to predict the selling prices of used cars. The primary objective was to assist both buyers and sellers in estimating fair prices for used cars based on key features.



## Data Exploring

The graphs the relationship between different data. One can gain insight how the data is distributed and can make decision if quanlilization of data is needed

![foo](https://github.com/hasanmehedi2309/car_price_predictor/assets/98232012/3042ffc2-e8f7-4111-b088-6f5c1df5aed1)

**Data after quanlilization**

![after_quantiling](https://github.com/hasanmehedi2309/car_price_predictor/assets/98232012/5885b0ea-de62-417a-ab69-2dd1c0ba831a)



## Standardization

Sdandardization is a very important process in machine learning. This process converts the large value into a range of 0 and 1. Data standardization transforms data into a consistent, standard format, making it easier to understand and use. This also helps the models run faster.

**Before Standardization**

![before_stand](https://github.com/hasanmehedi2309/car_price_predictor/assets/98232012/3eb2a4a0-5494-4f96-a853-019ce1164b8f)

It can be seen that the data is not liner but logrithmic.

**After Standardization**

![after_stand](https://github.com/hasanmehedi2309/car_price_predictor/assets/98232012/1f2f68cd-67de-45aa-9a72-432123acf134)

Using logrithmic standardization the is converted into liner and the values are relatively small which is easier to understand.
## Testing & Conclusion

**Predictions with Traning Data**

![train](https://github.com/hasanmehedi2309/car_price_predictor/assets/98232012/0e0157ab-5805-4d86-9206-1b2e56327a1b)

**Predictions with Testing Data**

![test](https://github.com/hasanmehedi2309/car_price_predictor/assets/98232012/5db91b3a-b1d1-4870-aa23-95630c17ec84)

From comparing the two graphs it can be seen that in both cases the graphs are almost linear. The model accuracy is 89%. So, it can be said that the model hasn't been overfitted and very much reliable.