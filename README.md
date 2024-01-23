# [Microsoft Azure | Deploying Dall-E-3 Model](https://app.tango.us/app/workflow/77564e19-90af-465f-8199-1769f76ab172?utm_source=markdown&utm_medium=markdown&utm_campaign=workflow%20export%20links)


# Deploying DALL-E 3 Model with Azure OpenAI Service

To deploy a DALL-E 3 model with Azure OpenAI service, make sure you have the following prerequisites:

1. **DALL-E 3 and DALL-E 2:** Obtain access to DALL-E in your desired Azure subscription.

2. **Azure Subscription:** If you don't have one, you can [create a free Azure subscription](https://azure.microsoft.com/en-gb/free/ai-services/?WT.mc_id=%3Fwt.mc_id%3Dstudentamb_298069).

3. **Azure OpenAI Resource:** Create an Azure OpenAI resource in the SwedenCentral region. You can find more information on how to create a resource and deploy a model [here](https://learn.microsoft.com/en-us/azure/ai-services/openai/how-to/create-resource?pivots=web-portal&WT.mc_id=%3Fwt.mc_id%3Dstudentamb_298069).

4. **Access to DALL-E:** Ensure that you have access granted to DALL-E in the desired Azure subscription.

5. **Application for Azure OpenAI Service:** Submit an application to access Azure OpenAI Service. You can apply for access by completing [this form](https://customervoice.microsoft.com/Pages/ResponsePage.aspx?id=v4j5cvGGr0GRqy180BHbR7en2Ais5pxKtso_Pz4b1_xUNTZBNzRKNlVQSFhZMU9aV09EVzYxWFdORCQlQCN0PWcu). If you need assistance, you can open an issue on [this link](https://customervoice.microsoft.com/Pages/ResponsePage.aspx?id=v4j5cvGGr0GRqy180BHbR7en2Ais5pxKtso_Pz4b1_xUNTZBNzRKNlVQSFhZMU9aV09EVzYxWFdORCQlQCN0PWcu) to contact Microsoft.

*Note: The application for Azure OpenAI Service is currently required. If you have any questions or need further assistance, feel free to reach out.*




***




## # [Cloud Computing Services | Microsoft Azure](https://azure.microsoft.com/en-us/?WT.mc_id=%3Fwt.mc_id%3Dstudentamb_298069)


### 1. Click on Sign in
![Step 1 screenshot](https://images.tango.us/workflows/77564e19-90af-465f-8199-1769f76ab172/steps/ceb6930d-24ae-48d9-8abc-6bd6545c39ec/09e994a6-02c1-4267-8e1c-ae7a57161641.png?crop=focalpoint&fit=crop&fp-x=0.9666&fp-y=0.0514&fp-z=2.5606&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=1009&mark-y=14&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0xNzcmaD0yMTAmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)


## # [Microsoft Azure portal (PWA)]([https://portal.azure.com/](https://azure.microsoft.com/en-gb/free/ai-services/?WT.mc_id=%3Fwt.mc_id%3Dstudentamb_298069))


### 2. Type "azure openai"
![Step 2 screenshot](https://images.tango.us/workflows/77564e19-90af-465f-8199-1769f76ab172/steps/efa765fc-0c2c-48a7-9f55-0ee2aad53d88/eb99fcf9-6f80-4f4f-bbad-ab79056d756c.png?crop=focalpoint&fit=crop&fp-x=0.4379&fp-y=0.0314&fp-z=1.4730&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=265&mark-y=8&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz02NzAmaD02NyZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 3. Click on Azure OpenAI
![Step 3 screenshot](https://images.tango.us/workflows/77564e19-90af-465f-8199-1769f76ab172/steps/a2a50a3d-8ca8-4a36-a3f8-504694e42373/cc83c881-9d07-4f46-9610-570bb38c6b9c.png?crop=focalpoint&fit=crop&fp-x=0.4111&fp-y=0.3750&fp-z=1.5642&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=282&mark-y=408&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz02MzcmaD04OSZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 4. Click on Create
![Step 4 screenshot](https://images.tango.us/workflows/77564e19-90af-465f-8199-1769f76ab172/steps/2c8d7c6e-f85f-4c02-9e78-744d1de56b0e/24ec5a12-5114-4725-9975-c8378132845a.png?crop=focalpoint&fit=crop&fp-x=0.3637&fp-y=0.2233&fp-z=2.5285&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=455&mark-y=377&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0yOTAmaD0xNTEmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)


### 5. Click on Create new
![Step 5 screenshot](https://images.tango.us/workflows/77564e19-90af-465f-8199-1769f76ab172/steps/c1d765f1-2f2d-4926-9be2-e45a2555d295/730b0afb-5fc9-4bae-be12-b17ab67ecf9e.png?crop=focalpoint&fit=crop&fp-x=0.3486&fp-y=0.6265&fp-z=2.6264&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=473&mark-y=409&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0yNTQmaD04OCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 6. Type "Dall-E-3"
![Step 6 screenshot](https://images.tango.us/workflows/77564e19-90af-465f-8199-1769f76ab172/steps/38642f90-3143-49eb-a2fc-44d22d1cfa16/82c8009f-f6cc-4d07-8382-5a152702ed94.png?crop=focalpoint&fit=crop&fp-x=0.5159&fp-y=0.8282&fp-z=1.4959&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=269&mark-y=641&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz02NjImaD02NCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 7. Click on OK
![Step 7 screenshot](https://images.tango.us/workflows/77564e19-90af-465f-8199-1769f76ab172/steps/416c8867-e2be-45ca-a5e6-13290916fd47/da28410d-b26f-481f-b39a-8ff79feb5f88.png?crop=focalpoint&fit=crop&fp-x=0.3808&fp-y=0.8879&fp-z=2.5088&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=452&mark-y=597&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0yOTcmaD0xMDgmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)


### 8. Click on Region
![Step 8 screenshot](https://images.tango.us/workflows/77564e19-90af-465f-8199-1769f76ab172/steps/160f4603-9f17-4d9a-be6d-3928adfa2f0d/0de8ee96-5a16-4aac-bf88-0e11936940ed.png?crop=focalpoint&fit=crop&fp-x=0.5613&fp-y=0.7449&fp-z=1.4456&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=161&mark-y=541&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz04NzgmaD02MiZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 9. Click on Sweden Central
![Step 9 screenshot](https://images.tango.us/workflows/77564e19-90af-465f-8199-1769f76ab172/steps/03141651-99f1-4fd4-8d4d-1f88dbc6fccd/2cd2aed9-89dc-4459-afca-ac1bff101b65.png?crop=focalpoint&fit=crop&fp-x=0.5621&fp-y=0.4815&fp-z=1.4472&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=160&mark-y=414&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz04NzkmaD03OCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 10. Type "DallEAzureTry"
![Step 10 screenshot](https://images.tango.us/workflows/77564e19-90af-465f-8199-1769f76ab172/steps/92dd6163-5f4f-4904-afc5-c4084fdf6d3c/5835df0c-46ff-483a-b3bc-04b789c4dabe.png?crop=focalpoint&fit=crop&fp-x=0.5613&fp-y=0.6265&fp-z=1.4456&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=161&mark-y=422&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz04NzgmaD02MiZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 11. Click on Pricing tier
![Step 11 screenshot](https://images.tango.us/workflows/77564e19-90af-465f-8199-1769f76ab172/steps/6caed47a-251b-4d0d-bc56-65d0800f4478/5fa00540-4e25-4c18-8bdd-f400b461e06d.png?crop=focalpoint&fit=crop&fp-x=0.5613&fp-y=0.5298&fp-z=1.4456&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=161&mark-y=422&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz04NzgmaD02MiZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 12. Click on Standard S0
![Step 12 screenshot](https://images.tango.us/workflows/77564e19-90af-465f-8199-1769f76ab172/steps/1ca61aa4-8271-4808-8fe9-a2c3e478ab77/84c2be21-f64d-42d9-85d9-47464671b43e.png?crop=focalpoint&fit=crop&fp-x=0.5621&fp-y=0.5720&fp-z=1.4472&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=160&mark-y=414&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz04NzkmaD03OCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 13. Click on Next
![Step 13 screenshot](https://images.tango.us/workflows/77564e19-90af-465f-8199-1769f76ab172/steps/1630f219-da3a-4c74-83f1-5fe33d731a39/3edf44f6-4571-4a36-a825-c51024eee475.png?crop=focalpoint&fit=crop&fp-x=0.1797&fp-y=0.9516&fp-z=2.5088&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=393&mark-y=742&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0yOTcmaD0xMDgmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)


### 14. Click on Create
![Step 14 screenshot](https://images.tango.us/workflows/77564e19-90af-465f-8199-1769f76ab172/steps/16f0ceab-5c9c-4ecb-a801-303060f6ddb6/1e88b3b4-53d6-479e-be5f-6b54a57eaad9.png?crop=focalpoint&fit=crop&fp-x=0.2783&fp-y=0.9516&fp-z=2.5088&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=452&mark-y=742&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0yOTcmaD0xMDgmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)


### 15. Click on DallEAzureTry
![Step 15 screenshot](https://images.tango.us/workflows/77564e19-90af-465f-8199-1769f76ab172/steps/eb756a3b-b60e-434e-84f6-b63c436371a1/592314f1-6f2b-467c-bddb-cbdfe024a035.png?crop=focalpoint&fit=crop&fp-x=0.4724&fp-y=0.5185&fp-z=2.5186&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=453&mark-y=411&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0yOTMmaD04NCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 16. Click on Go to Azure OpenAI Studio
![Step 16 screenshot](https://images.tango.us/workflows/77564e19-90af-465f-8199-1769f76ab172/steps/1499e8cd-0a1a-4a55-862a-e7310b658790/038b0108-207c-4e3f-a18a-ad01a7da7fb1.png?crop=focalpoint&fit=crop&fp-x=0.4305&fp-y=0.2233&fp-z=1.8902&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=340&mark-y=326&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz01MjAmaD0xMTMmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)


### 17. Click on Create new deployment
![Step 17 screenshot](https://images.tango.us/workflows/77564e19-90af-465f-8199-1769f76ab172/steps/f82cf6a4-191a-4d5b-a5df-533be622f59d/4dd2612a-a45b-4141-b036-8610bdc16bb0.png?crop=focalpoint&fit=crop&fp-x=0.3358&fp-y=0.4794&fp-z=1.9014&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=342&mark-y=401&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz01MTYmaD0xMDMmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)


### 18. Click on …
![Step 18 screenshot](https://images.tango.us/workflows/77564e19-90af-465f-8199-1769f76ab172/steps/0470e612-a0b4-40cc-ab00-1cd08f26d6f5/028ab6a5-a55b-4e97-b1ca-35016b6b0675.png?crop=focalpoint&fit=crop&fp-x=0.1840&fp-y=0.3215&fp-z=1.9270&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=172&mark-y=398&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz01MDYmaD0xMTAmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)


### 19. Type "dall-e-3"
![Step 19 screenshot](https://images.tango.us/workflows/77564e19-90af-465f-8199-1769f76ab172/steps/b4f7919e-faa9-429c-9f36-dbd5d22f2c6c/941658f9-f799-443c-bd60-197a3d16471b.png?crop=focalpoint&fit=crop&fp-x=0.4872&fp-y=0.4280&fp-z=1.2432&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=165&mark-y=419&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz04NzAmaD02NyZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 20. Click on Create new deployment
![Step 20 screenshot](https://images.tango.us/workflows/77564e19-90af-465f-8199-1769f76ab172/steps/87777aa8-cbd7-4c5a-82b1-b6a845a97b50/c1fbd636-2acf-444b-9733-f35ef2ce5ff5.png?crop=focalpoint&fit=crop&fp-x=0.3358&fp-y=0.4794&fp-z=1.9014&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=342&mark-y=401&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz01MTYmaD0xMDMmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)


### 21. Click on …
![Step 21 screenshot](https://images.tango.us/workflows/77564e19-90af-465f-8199-1769f76ab172/steps/f55ec3bf-bd88-4067-a3c1-39b1ba25d5fb/90dfe91d-2960-486f-8c6f-38270754559a.png?crop=focalpoint&fit=crop&fp-x=0.1840&fp-y=0.3215&fp-z=1.9270&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=172&mark-y=398&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz01MDYmaD0xMTAmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)


### 22. Click on Select a Model
![Step 22 screenshot](https://images.tango.us/workflows/77564e19-90af-465f-8199-1769f76ab172/steps/1f6fe710-751e-4cf4-94dd-93f232dc7359/ffd8f90b-a742-4184-ae89-69c7bcf26471.png?crop=focalpoint&fit=crop&fp-x=0.4872&fp-y=0.4280&fp-z=1.2432&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=165&mark-y=419&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz04NzAmaD02NyZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 23. Click on Deploy model…
![Step 23 screenshot](https://images.tango.us/workflows/77564e19-90af-465f-8199-1769f76ab172/steps/fd4e0299-192b-47c1-af76-046b64ad4ad1/8c757c45-ea8c-45ba-9bd5-90b0ffa1afa2.png?crop=focalpoint&fit=crop&fp-x=0.7927&fp-y=0.4280&fp-z=2.7803&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=525&mark-y=378&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0xNTAmaD0xNTAmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)


### 24. Click on dall-e-3
![Step 24 screenshot](https://images.tango.us/workflows/77564e19-90af-465f-8199-1769f76ab172/steps/7c99df4a-0b04-4ac1-ad33-cf42baab1454/e7e01aae-3b43-41b8-ba68-14ddd40ef2d1.png?crop=focalpoint&fit=crop&fp-x=0.2880&fp-y=0.5854&fp-z=1.9803&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=356&mark-y=394&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz00ODcmaD0xMTgmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)


### 25. Type "DALL-E"
![Step 25 screenshot](https://images.tango.us/workflows/77564e19-90af-465f-8199-1769f76ab172/steps/3184461c-0787-43e8-b5a3-ea367376ae6f/bf4fdbfe-5c16-4a13-93a5-8cba2b3ee2c6.png?crop=focalpoint&fit=crop&fp-x=0.4996&fp-y=0.6481&fp-z=1.2278&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=137&mark-y=482&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz05MjUmaD02NCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 26. Click on Create
![Step 26 screenshot](https://images.tango.us/workflows/77564e19-90af-465f-8199-1769f76ab172/steps/9a81e980-27fd-433e-884f-99ded3d48aab/8531878b-802f-418b-9169-f8930f08b106.png?crop=focalpoint&fit=crop&fp-x=0.6530&fp-y=0.8138&fp-z=2.5156&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=448&mark-y=413&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0zMDUmaD0xMzYmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)


### 27. Click on DALL-E
![Step 27 screenshot](https://images.tango.us/workflows/77564e19-90af-465f-8199-1769f76ab172/steps/f860887a-09cc-49fb-a1af-bdf8a28609c0/f03564af-1a73-460a-965d-6a400f6e290e.png?crop=focalpoint&fit=crop&fp-x=0.1661&fp-y=0.4532&fp-z=2.7735&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=452&mark-y=400&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0yMDImaD0xMDYmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)


### 28. Click on Close
![Step 28 screenshot](https://images.tango.us/workflows/77564e19-90af-465f-8199-1769f76ab172/steps/bbd6e5b5-0548-4afc-b842-6f935b843098/19d04319-3c88-4487-ae31-e1ce2bfdd6d1.png?crop=focalpoint&fit=crop&fp-x=0.9394&fp-y=0.1605&fp-z=2.7803&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=923&mark-y=329&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0xNTAmaD0xNTAmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)


### 29. Click on …
![Step 29 screenshot](https://images.tango.us/workflows/77564e19-90af-465f-8199-1769f76ab172/steps/def6fae4-74f4-4285-889f-e943f4aa7dbe/17e00e04-3fb5-432a-b40d-1e4bf46116f4.png?crop=focalpoint&fit=crop&fp-x=0.6036&fp-y=0.2083&fp-z=2.0283&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=365&mark-y=325&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz00NzEmaD0xMTUmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)


### 30. Type "Draw a digital painting of a kid flying though the clouds during sunset".
you can search for something called prompt Engineering.
![Step 30 screenshot](https://images.tango.us/workflows/77564e19-90af-465f-8199-1769f76ab172/steps/529ad56a-acb8-4410-8816-8d6288fbc3ad/7e7ebaf1-989b-454c-86b1-a2d0b806a327.png?crop=focalpoint&fit=crop&fp-x=0.4748&fp-y=0.3786&fp-z=1.0805&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=81&mark-y=342&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0xMDM4Jmg9NTYmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)


### 31. Click on Generate
![Step 31 screenshot](https://images.tango.us/workflows/77564e19-90af-465f-8199-1769f76ab172/steps/598f5831-7234-4f2e-92f3-ad95a242cf24/6940ba96-99c5-405f-a582-66d0f90bf0b3.png?crop=focalpoint&fit=crop&fp-x=0.9367&fp-y=0.3796&fp-z=2.7803&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=793&mark-y=378&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0zOTEmaD0xNTAmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)


### 32. Click on Draw a digital painting of a kid flying though the clouds during sunset
![Step 32 screenshot](https://images.tango.us/workflows/77564e19-90af-465f-8199-1769f76ab172/steps/eab5d204-0483-4b61-bebc-a30ec7ba6a4c/d4bb92e6-e8f2-4fc4-9a6b-7b044e54c728.png?crop=focalpoint&fit=crop&fp-x=0.2865&fp-y=0.6944&fp-z=1.5473&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=210&mark-y=156&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz02NDMmaD02NDMmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)

<br/>

***
Created with [Tango.us](https://tango.us?utm_source=markdown&utm_medium=markdown&utm_campaign=workflow%20export%20links)
