
# Kerjamin-Captone C22-PS306

This is our repositoritory for capstone project. 

## Our members
- Gabriel Asael Tarigan (M2233G2125)- Machine Learning - Universitas Katolik Soegijapranata
- Raihan Digo Saputra (M2214F2000)- Machine Learning - Universitas Islam Indonesia
- Susan Yulianti (A2351F2893) - Mobile Developer - Universitas Catur Insan Cendekia
- Gemilang Cahyaning Adi (C2312F2683) - Cloud Computing - Universitas Sebelas Maret
- Naomi Halimun (C7312F2687) - Cloud Computing - Universitas Sebelas Maret

## About Kerjamin

Kerjamin is a place for costumers to search capable freelancers and also for freelancers to get job opportunities. Freelancers can register themselves to an admin, by providing identities such as name, NIK, etc. Then an admin can create accounts for freelancers who registered before. Now, a client can search the nearest freelancers by their categories, such as electrician, builder, or the others. This app provides a list of the freelancers by their ratings and sentiment analysis score from their review. Clients are also capable of seeing the freelancer’s summary from the review to decide if they are sure to choose a freelancer or not. The client can choose and order a freelancer. At the same time, the freelancer also receives a notification if they get an order. A client can monitor the status of freelancer’s work through the app and decide if their work is already done.

This is the architecture of our apps. 
![Untitled Diagram drawio](https://user-images.githubusercontent.com/83566398/179150097-ba1b9838-2089-4d4f-823f-6490fbb4805c.png)

#### Machine learning (Rest API)
- Sentiment analysis API https://github.com/KerjaminCapstone/sentiment-analysis-api
  Provides a score for each or overall freelancer's review. This score will be used for freelancers ranking parameters besides distance. 
- Worlcloud API https://github.com/KerjaminCapstone/model_wordCloud
  Provides a list of word, represents a summary of freelancer's review.

#### Android app
- Client App https://github.com/KerjaminCapstone/Kerjamin
  An Android app for client. Client can register an account from this app, then order a freelancer from this app. 
- Freelancer app https://github.com/KerjaminCapstone/kerjamin-freelance-app
  An Android app for freelancer. After receiving a generated account from admin, freelancer can get order from this app. This app also provides a map to show direction from freelancer's current location to client's location. 

### Cloud Computing
- Main API (main back-end) https://github.com/KerjaminCapstone/kerjamin-api
  This our main back-end, where all process includes authentication, order processing, and data storing happens.
- Main API Documentation https://github.com/KerjaminCapstone/kerjamin-swagger 
- Database and admin website https://github.com/KerjaminCapstone/kerjadmin-gce
  This is our database migration and our admin website.

