# Microsoft Azure | Deploying Dall-E-3 Model

## Deploying DALL-E 3 Model with Azure OpenAI Service

To deploy a DALL-E 3 model with Azure OpenAI service, make sure you have the following prerequisites:

1. **DALL-E 3 and DALL-E 2:** Obtain access to DALL-E in your desired Azure subscription.

2. **Azure Subscription:** If you don't have one, you can [create a free Azure subscription](https://azure.microsoft.com/en-gb/free/ai-services/?WT.mc_id=%3Fwt.mc_id%3Dstudentamb_298069).

3. **Azure OpenAI Resource:** Create an Azure OpenAI resource in the SwedenCentral region. You can find more information on how to create a resource and deploy a model [here](https://learn.microsoft.com/en-us/azure/ai-services/openai/how-to/create-resource?pivots=web-portal&WT.mc_id=%3Fwt.mc_id%3Dstudentamb_298069).

4. **Access to DALL-E:** Ensure that you have access granted to DALL-E in the desired Azure subscription.

5. **Application for Azure OpenAI Service:** Submit an application to access Azure OpenAI Service. You can apply for access by completing [this form](https://customervoice.microsoft.com/Pages/ResponsePage.aspx?id=v4j5cvGGr0GRqy180BHbR7en2Ais5pxKtso_Pz4b1_xUNTZBNzRKNlVQSFhZMU9aV09EVzYxWFdORCQlQCN0PWcu). If you need assistance, you can open an issue on [this link](https://customervoice.microsoft.com/Pages/ResponsePage.aspx?id=v4j5cvGGr0GRqy180BHbR7en2Ais5pxKtso_Pz4b1_xUNTZBNzRKNlVQSFhZMU9aV09EVzYxWFdORCQlQCN0PWcu) to contact Microsoft.

*Note: The application for Azure OpenAI Service is currently required. If you have any questions or need further assistance, feel free to reach out.*




***





### 1. Click on Sign in
![Step 1 screenshot](https://images.tango.us/workflows/77564e19-90af-465f-8199-1769f76ab172/steps/ceb6930d-24ae-48d9-8abc-6bd6545c39ec/09e994a6-02c1-4267-8e1c-ae7a57161641.png?crop=focalpoint&fit=crop&fp-x=0.5000&fp-y=0.5000&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=1125&mark-y=6&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz02OSZoPTgyJmZpdD1jcm9wJmNvcm5lci1yYWRpdXM9MTA%3D)


## # [Microsoft Azure portal (PWA)](https://portal.azure.com/)
Upon signing in, you'll enter the Microsoft Azure Portal (PWA), a user-friendly web platform. This hub is your control center for managing Azure services. Familiarize yourself with the layout, using tabs and menus to navigate and access tools for configuring settings, monitoring, and resource management.


### 2. Type "Azure OpenAI"

In the Azure Portal's search bar, enter "Azure OpenAI" to explore relevant services and features related to the integration of OpenAI technology within the Microsoft Azure ecosystem. This step allows you to discover and leverage AI capabilities seamlessly integrated with Azure, enhancing your cloud computing experience.

![Step 2 screenshot](https://images.tango.us/workflows/77564e19-90af-465f-8199-1769f76ab172/steps/efa765fc-0c2c-48a7-9f55-0ee2aad53d88/eb99fcf9-6f80-4f4f-bbad-ab79056d756c.png?crop=focalpoint&fit=crop&fp-x=0.5000&fp-y=0.5000&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=298&mark-y=6&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz00NTUmaD00NiZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 3. Click on Create
To initiate the resource creation process, click on the "Create" button. This action opens a new window where you can select and configure various Azure resources, allowing you to tailor your cloud environment according to your specific requirements.

![Step 3 screenshot](https://images.tango.us/workflows/77564e19-90af-465f-8199-1769f76ab172/steps/2c8d7c6e-f85f-4c02-9e78-744d1de56b0e/24ec5a12-5114-4725-9975-c8378132845a.png?crop=focalpoint&fit=crop&fp-x=0.5000&fp-y=0.5000&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=379&mark-y=172&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0xMTUmaD02MCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 4. Click on Create new

Continue the resource creation process by selecting "Create new." This action prompts the Azure Portal to guide you through the steps of defining and configuring a new instance or resource. Clicking on "Create new" ensures a personalized setup to meet your specific needs within the Microsoft Azure environment.

![Step 4 screenshot](https://images.tango.us/workflows/77564e19-90af-465f-8199-1769f76ab172/steps/c1d765f1-2f2d-4926-9be2-e45a2555d295/730b0afb-5fc9-4bae-be12-b17ab67ecf9e.png?crop=focalpoint&fit=crop&fp-x=0.5000&fp-y=0.5000&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=370&mark-y=551&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz05NyZoPTM0JmZpdD1jcm9wJmNvcm5lci1yYWRpdXM9MTA%3D)

###Configuring DALL-E-3 Instance

### 5. Type "Dall-E-3"

### 6. Click on OK

### 7. Click on Region

### 8. Click on Sweden Central

### 9. Type "DallEAzureTry"
![Step 9 screenshot](https://images.tango.us/workflows/77564e19-90af-465f-8199-1769f76ab172/steps/92dd6163-5f4f-4904-afc5-c4084fdf6d3c/5835df0c-46ff-483a-b3bc-04b789c4dabe.png?crop=focalpoint&fit=crop&fp-x=0.5613&fp-y=0.6265&fp-z=1.4456&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=161&mark-y=422&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz04NzgmaD02MiZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 10. Click on Pricing tier

to access the pricing options.

### 11. Click on Standard S0

to choose the pricing tier that aligns with your requirements. This selection determines the performance and capabilities of your DALL-E-3 instance within the Microsoft Azure environment.

### 12. Click on Next 3 time


### 13. Click on Create

After completing the necessary configurations, proceed to the final step by clicking on "Create." This action initiates the deployment process, and Azure will begin creating your DALL-E-3 instance with the specified settings. Once the deployment is successful, you can start leveraging the power of DALL-E-3 within your Azure environment.

![Step 13 screenshot](https://images.tango.us/workflows/77564e19-90af-465f-8199-1769f76ab172/steps/16f0ceab-5c9c-4ecb-a801-303060f6ddb6/1e88b3b4-53d6-479e-be5f-6b54a57eaad9.png?crop=focalpoint&fit=crop&fp-x=0.5000&fp-y=0.5000&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=275&mark-y=840&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0xMTgmaD00MyZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 14. Click on DallEAzureTry
![Step 14 screenshot](https://images.tango.us/workflows/77564e19-90af-465f-8199-1769f76ab172/steps/eb756a3b-b60e-434e-84f6-b63c436371a1/592314f1-6f2b-467c-bddb-cbdfe024a035.png?crop=focalpoint&fit=crop&fp-x=0.4724&fp-y=0.5185&fp-z=2.5186&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=453&mark-y=411&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0yOTMmaD04NCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 15. Click on Go to Azure OpenAI Studio

After the successful creation of your DALL-E-3 instance, click on "Go to Azure OpenAI Studio." This action directs you to the dedicated studio, where you can explore, manage, and utilize the capabilities of OpenAI seamlessly integrated with Azure.

![Step 15 screenshot](https://images.tango.us/workflows/77564e19-90af-465f-8199-1769f76ab172/steps/1499e8cd-0a1a-4a55-862a-e7310b658790/038b0108-207c-4e3f-a18a-ad01a7da7fb1.png?crop=focalpoint&fit=crop&fp-x=0.4305&fp-y=0.2233&fp-z=1.8902&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=340&mark-y=326&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz01MjAmaD0xMTMmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)


### 16. Click on Create new deployment

To further customize your environment, click on "Create new deployment" within Azure OpenAI Studio. This step allows you to define specific configurations for your deployment, tailoring it to your project's requirements.

![Step 16 screenshot](https://images.tango.us/workflows/77564e19-90af-465f-8199-1769f76ab172/steps/f82cf6a4-191a-4d5b-a5df-533be622f59d/4dd2612a-a45b-4141-b036-8610bdc16bb0.png?crop=focalpoint&fit=crop&fp-x=0.3358&fp-y=0.4794&fp-z=1.9014&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=342&mark-y=401&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz01MTYmaD0xMDMmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)


### 17. 
![Step 17 screenshot](https://images.tango.us/workflows/77564e19-90af-465f-8199-1769f76ab172/steps/f55ec3bf-bd88-4067-a3c1-39b1ba25d5fb/90dfe91d-2960-486f-8c6f-38270754559a.png?crop=focalpoint&fit=crop&fp-x=0.1840&fp-y=0.3215&fp-z=1.9270&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=172&mark-y=398&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz01MDYmaD0xMTAmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)


### 18. Click on Select a Model

In the deployment process, click on "Select a Model" within Azure OpenAI Studio. This step enables you to choose the specific AI model that best suits your needs, offering flexibility and customization for your project.

![Step 18 screenshot](https://images.tango.us/workflows/77564e19-90af-465f-8199-1769f76ab172/steps/1f6fe710-751e-4cf4-94dd-93f232dc7359/ffd8f90b-a742-4184-ae89-69c7bcf26471.png?crop=focalpoint&fit=crop&fp-x=0.4872&fp-y=0.4280&fp-z=1.2432&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=165&mark-y=419&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz04NzAmaD02NyZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 19. Click on dall-e-3

### 20. Type "DALL-E"

### 21. Click on Create

### 22. Click on DALL-E
![Step 22 screenshot](https://images.tango.us/workflows/77564e19-90af-465f-8199-1769f76ab172/steps/f860887a-09cc-49fb-a1af-bdf8a28609c0/f03564af-1a73-460a-965d-6a400f6e290e.png?crop=focalpoint&fit=crop&fp-x=0.5000&fp-y=0.5000&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=163&mark-y=391&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz03MyZoPTM4JmZpdD1jcm9wJmNvcm5lci1yYWRpdXM9MTA%3D)


### 23. Click on …
![Step 23 screenshot](https://images.tango.us/workflows/77564e19-90af-465f-8199-1769f76ab172/steps/def6fae4-74f4-4285-889f-e943f4aa7dbe/17e00e04-3fb5-432a-b40d-1e4bf46116f4.png?crop=focalpoint&fit=crop&fp-x=0.6036&fp-y=0.2083&fp-z=2.0283&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=365&mark-y=325&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz00NzEmaD0xMTUmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)


### 24. Type "Draw a digital painting of a kid flying though the clouds during sunset".
you can search for something called prompt Engineering.
![Step 24 screenshot](https://images.tango.us/workflows/77564e19-90af-465f-8199-1769f76ab172/steps/529ad56a-acb8-4410-8816-8d6288fbc3ad/7e7ebaf1-989b-454c-86b1-a2d0b806a327.png?crop=focalpoint&fit=crop&fp-x=0.4748&fp-y=0.3786&fp-z=1.0805&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=81&mark-y=342&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0xMDM4Jmg9NTYmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)

<br/>

