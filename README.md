# ACV_Colorization: Our Colorization Model

The main branch contains our colorization model, which is our best-performing model. Please explore our different branches to see some of the other models we implemented that didn't work and/or produce good results: JCP- Koalarization, DP- Zhang's, DP2-Intermediate step(ignored).

Our model is trained on CIFAR10 dataste, and evaluated on the corresponding testing dataset. 

##How to use
The main.ipynb contains all the code that needs to be excuted. However, to use it properly, one should consider changing the file paths. 
In addition

## Results
Below image is the training time losses with MSELoss:
![mseloss ours](https://user-images.githubusercontent.com/50256011/235391448-ecfcd51c-85d0-4e04-b2a9-839c6d68f575.png)

Below image is the training time losses with our custom loss:
![custom loss ours](https://user-images.githubusercontent.com/50256011/235391490-31601423-5d62-4ef4-aab9-dd228f860c92.png)

Below image is a demo comparison between image results (where 15 and 14 are average DeltaE values repectively):
![test results](https://user-images.githubusercontent.com/50256011/235391604-e39bb8ca-86b9-4542-ab6e-ba957adfb83b.png)



