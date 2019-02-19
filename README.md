# Grey-Atom---Hackathon2
# Trade Forecasting (https://bit.ly/2tp8uWG)
Welcome to Antallagma - a digital exchange for trading goods. Antallagma started its
operations 5 years back and has supported more than a million transactions till date. The
Antallagma platform enables working of a traditional exchange on an online portal.
On one hand, buyers make a bid at the value they are willing to buy ("bid value”) and the
quantity they are willing to buy. Sellers on the other hand, ask for an ask price and the
quantity they are willing to sell. The portal matches the buyers and sellers in realtime to create
trades. All trades are settled at the end of the day at the median price of all agreed trades.
You are one of the traders on the exchange and can supply all the material being traded on
the exchange. In order to improve your logistics, you want to predict the median trade prices
and volumes for all the trades happening (at item level) on the exchange. You can then plan to
use these predictions to create an optimized inventory strategy.
You are expected to create trade forecasts for all items being traded on Antallagma along with
the trade prices for a period of 6 months.

Evaluation Criteria:

Overall Error = Lambda1 x RMSE error of volumes + Lambda2 x RMSE error of prices Where
Lambda1 and Lambda2 are normalising parameters
Description:

● There were in-total of 1529 unique stocks in the data.

● The data is from jan-2014 to june-2016. Divide the data into train and test (Jan-2016 to
June-2016). Build your models on train and present your final scores on test.

● Category_1, Category_2, Category_3 are Binary masked feature, Ordered Masked
feature, Unordered Masked feature respectively.

● Price (Median Price at Sale on that day), Number_Of_Sales (Total Item Sold on that day)
are two target variables.

