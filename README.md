# PersonCountingRaspberry_WebsiteVersion

+ After creating a project that detect persons, I decided to make a simple website and host it on amazon s3
<img width="1440" alt="Screenshot 2020-05-22 at 03 42 03" src="https://user-images.githubusercontent.com/40724965/82622601-8a168c80-9bde-11ea-93f7-122e816372fa.png">

>When your click on Click me !! button, a fucntion will be triggered to retrieve the data from aws DynamoDb database and display it 

<img width="1440" alt="Screenshot 2020-05-22 at 03 42 14" src="https://user-images.githubusercontent.com/40724965/82622587-7ec36100-9bde-11ea-9ef4-e71ca2a5e593.png">

+First we need to create our Table on DynamoDb with an id & value that gonna be updated each time the raspberry detect a person

>DynamoDb Table
<img width="1440" alt="Screenshot 2020-06-16 at 13 57 02" src="https://user-images.githubusercontent.com/40724965/84774351-fb7b0c80-afdd-11ea-9e3b-596a2a4832f3.png">

+We need to update our Lambda function so it can access to DynamoDb Table

<img width="1275" alt="Screenshot 2020-06-16 at 14 26 17" src="https://user-images.githubusercontent.com/40724965/84774375-059d0b00-afde-11ea-82e7-f2365d30d9c4.png">

+As a result we get a simple website like this 
>Our website refreach itself every 2 seconds using setTimeout() HTML function

<img width="1437" alt="Screenshot 2020-06-16 at 13 55 52" src="https://user-images.githubusercontent.com/40724965/84774465-29f8e780-afde-11ea-9ab3-760e2481d0d6.png">
>Since we still in lockdown I can only test it on myself 

<img width="1440" alt="Screenshot 2020-06-16 at 13 55 26" src="https://user-images.githubusercontent.com/40724965/84774593-57459580-afde-11ea-84d9-560418994acd.png">
