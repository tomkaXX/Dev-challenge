# 🤖 [AI Bots Academy](#)  
### Build your bot using NLP and integrate it with Facebook  Messenger!
### 🏆 Toby Bot - Winners of the AI challenge at HackZurich 2020 
###### || Developers: Tamara Koliada, Developer Circles Lead from Kiev and Marlen Gonzalez, AI Developer. ||
###### ||Resources: [DF](#), [Messenger Docs](https://developers.facebook.com/docs/messenger-platform/getting-started/quick-start/), [FB Open Source code of conduct](https://engineering.fb.com/codeofconduct/)||
###### ||FB Community Challenge 2020 🌎 || 

Toby bot is virtual assistant that rewards through our AI Loyalty program, all your purchase of products such as: food, beverage and many others products. This project was selected Winner of the AI Challenge at HackZurich 2020: https://devpost.com/software/toby-bot

#### Let's start!

> Step 1:

Go to [DF](https://dialogflow.cloud.google.com/#/login)

> Step 2:

 🤖 Create new agent and [import our project](https://github.com/tomkaX/tomkaX/blob/main/TobyBotSample.zip) 

<br>
<div align ="center">
  <img width="800" height="400" src="https://media.giphy.com/media/2aHg9z5shHnulTX5eN/giphy.gif">
</div>

> Step 3:

Go to DF integrations:

<br>
<div align ="center">
  <img width="800" height="400" src="https://media.giphy.com/media/Lb4DbVjbhNVbOMY5lb/giphy.gif">
</div>


> Step 4:

Turn on the Facebook Messenger service 

> Step 5:

Now go to https://developers.facebook.com

<br>
<div align ="center">
  <img width="800" height="400" src="https://media.giphy.com/media/putDpToOBrGEpAXMMZ/giphy.gif">
</div>

> Step 6

Create an app on FB console > chose manage bussiness integration > add display name 
Add purpose > Select ypu bussiness manager account > And this will create your app id

> Step 7: 

Select the Messenger configuration (set up):

<br>
<div align ="center">
  <img width="800" height="400" src="https://media.giphy.com/media/MHiWZK6IoVYsLIQPSb/giphy.gif">
</div>


> Step 8: 🤖

Create or add a Fan page for Toby Bot 

<br>
<div align ="center">
  <img width="800" height="400" src="https://media.giphy.com/media/1G28uDOVJRjlRVU3zZ/giphy.gif">
</div>

> Step 9

Generate access token > get this access token to dialogflow:  
> Then create a verify token in DF ("helloworld" in our case),
> Now copy the Callback url provided by DF,
> And Finally, Click on "start bot" ✅

> Step 10 

Add the Callback URl from DF to Facebook for Developers console 
> Also copy/paste the verify token created on DF to Facebook Console 
> Click on verify and save ✅

> Step 11

In the FB Messenger set up, add the following subscriptions to the webhooks (messeges):

```
- messages
- messaging_postbacks
- message_deliveries
- message_reads
```
And Click on Save it ✅

> Step 12 

Try your bot inegration> Go to your fan page > And click on the Get started button 

<br>
<div align ="center">
  <img width="800" height="400" src="https://media.giphy.com/media/DOA84CQhuVx5HSV4X9/giphy.gif">
</div>


> Step 13

At Facebook developer console go to basic settings and add:
- your app domain 
- privacy policy url , 
- your terms of service URL,
- Add you App icon 
- Chose an category > Messenger bot for a bussines 
- Finally add a platform > website > add your website URL and 
- save changes ✅

<br>
<div align ="center">
  <img width="800" height="400" src="https://media.giphy.com/media/8fRMgJe9GYKwbbggHy/giphy.gif">
</div>

> Step 14: App Review

Go to app review > Click on request permissions and features 
Now go to pages_messaging > Request advanced access 
> Go back to Requests and provide the folloving information - Complete App verification 

Provide detailed step-by-step instructions on how a reviewer can test your integration and how you are using the requested permissions or features. Include any testing credentials required to access your integration.

> Step 15

 Edit your request permission features 

```
Please provide a detailed description of how your app uses the permission or feature requested, how it adds value for a person using your app, and why it's necessary for app functionality. 
```


Select your page
 
```
Provide a detailed step-by-step video walkthrough of how your app will use this permission or feature so we can confirm it is used correctly and does not violate our policies
```

Click > If approved I agree... and accept terms! ✅ 

> Step 16

🤖 Submit your for Bot for the App Review and to be Available for everyone. 


Resources: 
-  [Getting started with Messenger Platform](https://developers.facebook.com/docs/messenger-platform/getting-started/quick-start/)
-  [Sending Messages](https://developers.facebook.com/docs/messenger-platform/send-messages)
-  [Submission Process](https://developers.facebook.com/docs/messenger-platform/submission-process)
-  [Policy & Usage Guidelines](https://developers.facebook.com/docs/messenger-platform/policy)
