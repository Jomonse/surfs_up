# surfs_up

Analysis of two months in different stations of the year and see how the temperature changes.

## Overview of the analysis
The porpuse of the analysis is to find how temperature changes in the middle and end of the year in order to decide if is susteinable to open a surf and ice cream shop in Oahu, Hawaii.

## Results
For the month of June, we can see that the temperature don't have significant changes in the past of the years.
![June_plot](https://user-images.githubusercontent.com/21062253/142821249-89e1b4f6-c98f-4588-b53e-3ebcb47584fa.png)
And for the results, we can supposed that the weather is almost the same between june and december, because the plot of june are very similar.
![December_plot](https://user-images.githubusercontent.com/21062253/142821441-435e7dea-eedc-431d-922f-900d6b1b0db4.png)
But more than the plots, the statistics describe of each month have similar results
![december_describe](https://user-images.githubusercontent.com/21062253/142821637-eb90612c-258a-4eef-a34c-56a930660e84.png) _december

![june describe](https://user-images.githubusercontent.com/21062253/142821639-ea022dfa-56df-4c96-ae96-d9ea9a3e8ca8.png) _june

But to be sure of our assumptions it is neccessary to made an hypothesis test were:
H0: μ1 = μ2
Ha: μ1 =/  μ2

Since it is observed that ∣t∣=31.604>tc=1.961|t| = 31.604 > t_c = 1.961∣t∣=31.604>tc =1.961, it is then concluded that the null hypothesis is rejected.

Using the P-value approach: The p-value is p=0p = 0p=0, and since p=0<0.05p = 0 < 0.05p=0<0.05, it is concluded that the null hypothes is rejected.

### Conclusion

It is concluded that the null hypothesis Ho is rejected. Therefore, there is enough evidence to claim that the population mean μ1\mu_1μ1 is different than μ2\mu_2μ2, at the α=0.05\alpha = 0.05α=0.05 significance level.

## Summary
Even if the temperature changes between june and december, the temperature is still high so the bussiness is feaseable, but to have a better idea it is neccesary to know the temperature for another month in another station, in this case I decided to made January.
![jan_plot](https://user-images.githubusercontent.com/21062253/142824816-2aa0af82-2318-43b2-a54d-b89714f16d18.png)
![jan_describe](https://user-images.githubusercontent.com/21062253/142824881-0afdeecd-3429-466e-9e56-bdc43ced6ce2.png)

In this case we can see that the temperature descends more, but it is still a good weather for the business, so I will recomend to open the surf and ice cream shop, knowing that as in all the bussiness there will be better months than anothers.
