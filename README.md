# Will-a-Customer-Accept-the-Coupon #
The major goal of this project is to predict if the drivers with/without passenger will accept more coupons than rejecting them, by using python
libraries for visualization, and also conditioning probabilities.

#### The programming language used is Python, and the libraries used were: Pandas, Seaborn, Matplotlib, and numpy ####

* The complete analysis, including observations,commentss so all the work done is contained in the following Jupiter Notebook:

    [Jupiter Notebook used](https://github.com/Leopard-2019/Will-a-Customer-Accept-the-Coupon/blob/main/notebook/prompt_assig5_1.ipynb)

* There were some columns (age, income, expiration, Bar, CoffeeHouse, CarryAway, RestaurantLessThan20, and Restaurant20to50) initially defined 
  as object that were manipultated, etc in order to be able to be treated as numerical in order to facilitate the analysis. 
  
* There were also some columns (car, Bar,CoffeHouse, CarryAway,RestaurantlLessthan20, restaurant20To50) that present missing values.
 
*  The conditonal probability that drivers with 'Friend(s)' as passenger accept the coupons: "Coffe House", "Restaurant (<20)", and "Carry out & Take
   Away"  is the highest than the rest of the drivers without/with passenger, i.e, 'Alone', "Partner", and "Kid(s)". This is quite evident by looking
   at the results of the conditional probabilities visualized using the barplots shown below.
   
   ![](images/barplotprobabilityacceptnoacceptcouponbyfriendpassanger.png)
   
   ![](images/barplotprobabilityacceptnoacceptcouponbyalonepassanger.png)
   
   ![](images/barplotprobabilityacceptnoacceptcouponbypartnerpassanger.png)
   
   ![](images/barplotprobabilityacceptnoacceptcouponbykidspassanger.png)

* The coupons most likely to be accepted for all the drivers without/with passenger, but with Kid(s) are:"Coffe House", "Restaurant (<20)", 
  and "Carry out & Take Away".
  
 * The conditional probability that drivers without/with passengers accepts coupons  is much higher by a wide margin during sunny days as shown in the
   barplot below:
 
    ![](images/barplotprobabilityacceptnoacceptcouponbyweather.png)
    
 * The conditional probability that "Male" drivers  accepts coupons  is slighlty higher than the Female drivers as shown in barplot below:

    ![](images/barplotprobabilityacceptnoacceptcouponbygender.png)
    
 * The power of using conditional probabilities indicates that within the drivers groups are some diferences, sometimes quite conspicuous for instance:
 
      * The drivers without passenger, i.e. Alone are more keen to not accept the coupons: "Coffee House", Bar, and "Restaurant(20-50)" than accept
        them.
 
      * The drivers with passenger "Friend(s)" are more keen to not accept the coupons:  "Restaurant(20-50)" than accept them.
      
      * The drivers with passenger "Partner" are more keen to not accept the coupons:  "Carry and TakeAway" and "Bar" than accept them.
      
      * The drivers with passenger "Kid(s)" are more keen to not accept the coupons:  "Coffee House", "Bar", and   Restaurant(20-50) than accept them.

 * As a results a generalize answer to the question " Will a Customer Accept the Coupon"  can not be made, since, again differences among the 
   different groups of drivers without/with passengers exist.  
  
    
 * The boxplot inmediately below indicates that the drivers without passsenger, i.e, "Alone", and with "Friends" who accepted the coupons (Y=1) 
   have about the same means age  **(please see the small white circles )** through the different coupons categories, i.e. drivers without/ with
   the aforementioned passengers in their early 30's are more willing to accept the coupons (Y=1). Conversely, the drivers with / without
   passengers who did not accept the coupon (Y=0) are a bit older as shown in the boxplot that follow the first one mentioned.

    ![](images/boxplotagesacceptbypassenger.png)
    
    ![](images/boxplotagesnoacceptbypassenger.png)
    
  *The boxplot below indicates that the drivers without passsenger, i.e, "Alone", and with "Friends" who accepted the coupon (Y=1) have about the
  same median income, but quite lower than the rest of drivers with  passenger groups  "Kid(s)", and "Partner".Quite  similar observation is applied
  by comparing **the mean income among those  groups who accepted the coupon as indicated by the white small circle markers posted on same 
  aforementioned boxplot**.These observations make sense on the countplot of Coupon Accepted (Y=1) by drivers without/with Passengers also shown here
  where the groups that did accept more coupon are the drivers without passenger, i.e, "Alone", and the ones with "Friend(s)". Basically,  it is 
  expected that groups with lower income media will be more keen to accept coupons (see also the heatmap income by drivers without/with passengers
  who accepted the coupon (Y=1)). it is also important to highlight that the drivers without/with passengers who did not accept the coupon (Y=0)
  have higher mean income as shown in the other boxplot shown below.
  
  ![](images/boxplotincomeacceptbypassenger.png)
  ![](images/countplotacceptedcouponbypassengers.png)
  ![](images/heatmapincomecceptbypassenger.png)
  ![](images/boxplotincomenoacceptbypassenger.png)
  
  * The catplot below indicates that the all drivers with/without passengers were much more keen to accept the coupons (Y=1) that expires in 24 hours
    (i.e, 1 day).

   ![](images/catplotexpirationacceptednoaccepteddriversbypassenger.png)
   
   * A exercise Constructing a null and alternative hypothesis for the difference between drivers without/with passengers  who go to the Coffee 
     House more than once a month and income less than $50000 to all other drivers without/with passenger indicated that:
     
            * The p_value=0.0218 is less than alpha=0.05$ so we did reject Ho, i.e. the null hypothesis
             
            * As a result, it is possible to conclude that the drivers without/with passenger with income less than $50000 go more often to the
              Coffee House than drivers without/with passenger with higher income, independently if they have accepted or not the coupons.
      
   * There were other columns that were used in this analysis, but I just wanted to highlight the major finding.   

   * As a final remark, please keep in mind that were much more drivers without passenger surveyed in the data provided as show in the histogram
     below. Therefore, I can nor discard some sort of bias involved.
     
     ![](images/histogramdriverswithout_withpassengers.png)

  
  
