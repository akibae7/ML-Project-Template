# Problem Statement 
In this dataset , data collected are the sales data of mobile phones of various companies . In the competitive mobilephone market you cannot simply assume things . In this problem to estimate the price of mobiles this company creates we have to predict the price range indicationg how high the price is by finding out some relation between the features of a mobile phone.
## Dataset

The dataset used is the [Mobile Price Classification](https://www.kaggle.com/iabhishekofficial/mobile-price-classification) . 

The  class labels are:
<br>

**1. battery_power:** ->Total energy a battery can store in one time measured in mAh
<br>
**2. blue:** ->Has bluetooth or not
<br>
**3. clock_speed:** ->speed at which microprocessor executes instructions
<br>
**4. dual_sim:** ->Has dual sim support or not
<br>
**5. fc:** ->Front Camera mega pixels
<br>
**6. four_g** ->Has 4G or not
<br>
**7. int_memory:** ->Internal Memory in Gigabytes
<br>
**8. m_dep:** ->Mobile Depth in cm
<br>
**9. mobile_wt** ->Weight of mobile phone
<br>
**10. n_cores** ->Number of cores of processor
<br>
**11. pc** ->Primary Camera mega pixels 
<br>
**12. px_height:** ->Pixel Resolution Height
<br>
**13. px_width** ->Pixel Resolution Width
<br>
**14. ram** ->Random Access Memory in Megabytes
<br>
**15. sc_h** ->Screen Height of mobile in cm
<br>
**16. sc_w** ->Screen Width of mobile in cm
<br>
**17. talk_time** ->longest time that a single battery charge will last when you are
<br>
**18. three_g** ->Has 3G or not
<br>
**19. touch_screen** ->Has touch screen or not
<br>
**20. wifi** ->Has wifi or not
<br>
**21. price_range:** ->Gives price range for the mobile
<br>


## Model(s) Used

1. **K Nearest Neighbours:** This model is most useful in data which can be linearly separated. It simply finds the "K nearest neighbours" and uses the hoghest class occurence as the final class preidction.

2. **Naive Bayes**: Naive Bayes classifiers are a collection of classification algorithms based on Bayes’ Theorem. It is not a single algorithm but a family of algorithms where all of them share a common principle, i.e. every pair of features being classified is independent of each other.

3. **Decision Tree Classifier**: This model identifies the most informative attribute at every level and uses it to make a tree. The final tree can then be used as a simple if-else statement to identify the final prediction.

4. **Logistic Regression**: Logistic regression predicts the output of a categorical dependent variable. Therefore the outcome must be a categorical or discrete value. It can be either Yes or No, 0 or 1, true or False, etc. but instead of giving the exact value as 0 and 1, it gives the probabilistic values which lie between 0 and 1.



