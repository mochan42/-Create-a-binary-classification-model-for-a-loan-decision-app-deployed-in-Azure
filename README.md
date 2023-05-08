# Create-a-binary-classification-model-for-a-loan-decision-app-deployed-in-Azure

# Aim of the project :
This project consists in :<br>
* Creating a binary classfication model to predict if a client can get a loan or not to buy a house/apartment.<br>
* Deploying the classification model in the cloud via an API.<br>
* Creating a Web application deployed in the cloud so that it can be easy to get the output of the classification model for a none-technical person by clicking on the `Predict` box.

<br>
<br>

# Walkthrough of the Web application :
*  The input data are fed via a drop down menu by selecting the index of the client :<br>
![App_selec_client](https://user-images.githubusercontent.com/107719618/236840897-59afab27-9316-4da5-97b8-fa450c46c41a.png)

<br>

* By clicking on the `Explain prediction` button, the user can explain to the client the features that explains the decision using a waterfall SHAP plot.<br>
![interpretabilite_locale_SHAP_client_7395](https://user-images.githubusercontent.com/107719618/236839768-16e70226-4e28-4e46-8500-399625cbee67.png)

<br>

* Finally, by clicking on the `Compare with other customers` button, the user can illustrate to the client where the client position is compared to other clients based on a number of features, such as income, credit amount etc.<br><br>
![Capture d’écran 2023-05-08 à 15 52 00](https://user-images.githubusercontent.com/107719618/236842562-a0c197d5-6728-44d6-90f2-5c37203bc0bb.png)

<br>
<br>

# Videoclip of the Web application once deployed in Azure :<br>

https://user-images.githubusercontent.com/107719618/227427130-a6a9fedd-5a32-4ce7-b27d-bab16037a00e.mov

