# Problem Statement 
This should be a brief description of the domain of your dataset (e.g. if it is the Titanic Dataset then write about the ship, the incident that happened, what you're trying to do with the data).
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
**21. price_range:** Gives price range for the mobile
<br>


## Model(s) Used

This needs to be a description of the model used and a brief overview of how it works in theory (e.g taken of a CNN Model): 

The network architecture used was a basic CNN model, with Max Pooling and ReLU Activation functions. Input images are resized to an optimal size and then fed into the **Convolutional layer**. These images are converted to their pixel values, which can be imagined as a three-dimensional matrix for the purpose of visualization. The **Convolutional layer** has a kernel. This kernel is generally a small matrix of specified kernel size mxnx3 (3 for RGB images). 
<br>

**Rectified Linear Unit (ReLU)** is the activation layer used in CNNs.The activation function is applied to increase non-linearity in the CNN. Images are made of different objects that are not linear to each other.


**Max Pooling:** A limitation of the feature map output of Convolutional Layers is that they record the precise position of features in the input. This means that small movements in the position of the feature in the input image will result in a different feature map. This can happen with re-cropping, rotation, shifting, and other minor changes to the input image. A common approach to addressing this problem from signal processing is called down sampling. This is where a lower resolution version of an input signal is created that still contains the large or important structural elements, without the fine detail that may not be as useful to the task.

## Future Work
Good ideas or strategies that you were not able to implement which you think can help  improve performance.
