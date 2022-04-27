# Will-a-Customer-Accept-the-Coupon #
The major goal of this project is to predict if the drivers with/without passenger will accept more coupons than rejecting them, by using python libraries for visualization, and also conditioning probabilities.

### The programming language used is Python, and the libraries used were: Pandas, Seaborn, Matplotlib, and numpy ###

* The complete analysis, including observations,comments so all the work done is contained in the following Jupiter Note:

    [Jupiter Notebook used](https://github.com/Leopard-2019/Will-a-Customer-Accept-the-Coupon/blob/main/notebook/prompt_assig5_1.ipynb)

 
* Certainly the drivers with 'Friend(s)' as passenger are the most likely to accept the coupons: "Coffe House",
  "Restaurant (<20)", and "Carry out & Take Away" than the rest of the drivers without/with passenger, i.e, 'Alone', "Partner", and "Kid(s)". This is 
   quite evident by looking at the results of the conditional probabilities visualized using histograms shown below.
   
   ![](images/barplotprobabilityacceptnoacceptcouponbyfriendpassanger.png)
   
   ![](images/barplotprobabilityacceptnoacceptcouponbyalonepassanger.png)
   
   ![](images/barplotprobabilityacceptnoacceptcouponbypartnerpassanger.png)
   
   ![](images/barplotprobabilityacceptnoacceptcouponbykidspassanger.png)

* The coupons most likely to be accepted for all the drivers without/with passenger, but with Kid(s) are:"Coffe House",
  "Restaurant (<20)", and "Carry out & Take Away".
  
 * The probability that drivers without/with passengers accept coupons than not is much higher by a wide margin during sunny days as shown in the figure below:
 
    ![](images/barplotprobabilityacceptnoacceptcouponbyweather.png)
