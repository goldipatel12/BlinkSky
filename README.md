##Why BlinkWay and what is that?

Global Payments gateways and solutions in general are lagging behind digital transformation and the digital economy, while users are looking for a complex digital financial experience, companies fail to provide even the most basic methods of global payments digitally. At the same time there is no better way enable the immediate movement of value to anywhere in the world.

Hence was born **BlinkWay**

**_An End-to-end global digital payment platform that will disrupt the way digital payments are served to people around the world by leveraging the power of BlinkSky APIs and providing the people of world a better way enable the immediate movement of value as Digital payments, in the form of gift cards, donations and incentives to anywhere in the world ._**

##How it works?

The BlinkWay ecosystem was built on top of BlinkSky APIs. It utilises different BlinkSky  Issuing and Disburse features to provide an all-around personal finance experience. BlinkWay uses Firebase as its backend, augmenting the BlinkSky APIs into features such as the Movement of Gift cards around the globe, enabling micro to macro donation to any part of the world. At the same time, Firebase Cloud Functions are listening to Blink webhook calls to store and mutate user-specific information into a Firebase Realtime Database. As the application has to be available only for registered users, authentication was implemented using Firebase as well. 

The app itself was developed with React Native, the perfect framework for quick prototyping in projects like BlinkWay. This way the application is natively available on both iOS and Android. To speed up the development of BlinkSky features, a custom module was built that transforms a BlinkSky APIs collection into a Javascript callable SDK class. This allowed us to avoid heavily repeated code segments and resulted in much cleaner code. A simple proxy server was also created to handle the BlinkSky authentication requirements.


##What’s included in BlinkWay?

We like your enthusiasm! 🙌

BlinkSky was developed specifically for the Blinkathon and now we are planning for beta testing. When we are satisfied with the performance of the application we make sure you are going to be among the first ones to be notified.



##What’s next?

Although BlinkSky is completely functional, we already see areas ready for improvement. More complex error handling, wider region support, performance improvements and in general, deeper testing for edge cases are required



