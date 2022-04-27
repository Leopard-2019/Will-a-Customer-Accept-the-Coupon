# Will-a-Customer-Accept-the-Coupon #
The major goal of this project is to predict if the drivers with/without passenger will accept more coupons than rejecting them, by using python libraries for visualization, and also conditioning probabilities.

#### The programming language used is Python, and the libraries used were: Pandas, Seaborn, Matplotlib, and numpy ####

* The complete analysis, including observations,comments so all the work done is contained in the following Jupiter Notebook:

    [Jupiter Notebook used](https://github.com/Leopard-2019/Will-a-Customer-Accept-the-Coupon/blob/main/notebook/prompt_assig5_1.ipynb)

 
*  The conditonal probability that drivers with 'Friend(s)' as passenger accept the coupons: "Coffe House",
  "Restaurant (<20)", and "Carry out & Take Away"  is the highest than the rest of the drivers without/with passenger, i.e, 'Alone', "Partner", and "Kid(s)". This is quite evident by looking at the results of the conditional probabilities visualized using histograms shown below.
   
   ![](images/barplotprobabilityacceptnoacceptcouponbyfriendpassanger.png)
   
   ![](images/barplotprobabilityacceptnoacceptcouponbyalonepassanger.png)
   
   ![](images/barplotprobabilityacceptnoacceptcouponbypartnerpassanger.png)
   
   ![](images/barplotprobabilityacceptnoacceptcouponbykidspassanger.png)

* The coupons most likely to be accepted for all the drivers without/with passenger, but with Kid(s) are:"Coffe House",
  "Restaurant (<20)", and "Carry out & Take Away".
  
 * The conditional probability that drivers without/with passengers accept coupons  is much higher by a wide margin during sunny days as shown in the
   figure below:
 
    ![](images/barplotprobabilityacceptnoacceptcouponbyweather.png)
    
 * The conditional probability that "Male" drivers  accepts coupons  is slighlty than the Female drivers as shown infigure below:

    ![](images/barplotprobabilityacceptnoacceptcouponbygender.png)
