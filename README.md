# Will-a-Customer-Accept-the-Coupon #
The major goal of this project is to predict if the drivers with/without passenger will accept more coupons than rejecting them, by using python libraries for visualization, and also conditioning probabilities.

### The programming language used is Python, and the libraries used were: Pandas, Seaborn, Matplotlib, and numpy ###

* The complete analysis, including observations and comments are contained in the following Jupiter Note:

![](notebook/prompt_assig5_1.ipynb)
  
* Certainly the drivers with 'Friend(s)' as passenger are more likely to accept the coupons than not, in particular the coupons: "Coffe House",
  "Restaurant (<20)", and "Carry out & Take Away" than the rest of the drivers without/with passenger, i.e, 'Alone', "Partner", and "Kid(s)". This is 
   quite evident by looking at the results of the conditional probabilities visualized using histograms shown below
   
   ![](images/barplotprobabilityacceptnoacceptcouponbyfriendpassanger.png)
   
   ![](images/barplotprobabilityacceptnoacceptcouponbyalonepassanger.png)
   
   ![](images/barplotprobabilityacceptnoacceptcouponbypartnerpassanger.png)
   
   ![](images/barplotprobabilityacceptnoacceptcouponbykidspassanger.png)
