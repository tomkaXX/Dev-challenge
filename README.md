# 🤖 [AI Bots Academy](#)  
### Build your bot using NLP and integrate it with Facebook  Messenger!
### 🏆 Toby Bot - Winners of the AI challenge at HackZurich 2020 
###### || Developers: Tamara Koliada, Developer Circles Lead from Kiev and Marlen Gonzalez, AI Developer. ||
###### ||Resources: [DF](#), [Messenger Docs](https://developers.facebook.com/docs/messenger-platform/getting-started/quick-start/), [FB Open Source code of conduct](https://engineering.fb.com/codeofconduct/)||
###### ||FB Community Challenge 2020 🌎 || 

Toby bot is virtual assistant that rewards through our AI Loyalty program, all your purchase of products such as: food, beverage and many others products. This project was selected Winner of the HackZurich 2020: https://devpost.com/software/toby-bot

#### Let's start!

> Step 1:

step 1 - go  https://dialogflow.cloud.google.com/#/login
add default intent - responses an facebook messenger at dialog flow

> Step 2:

step 2 - create new agent - create new project 

<br>
<div align ="center">
  <img width="800" height="400" src="https://media.giphy.com/media/2aHg9z5shHnulTX5eN/giphy.gif">
</div>

> Step 3:

step 3 - go to integrations

<br>
<div align ="center">
  <img width="800" height="400" src="https://media.giphy.com/media/Lb4DbVjbhNVbOMY5lb/giphy.gif">
</div>


> Step 4:

step 4 - turn on facebook messenger 

> Step 5:

step 5 - Now go to developers.facebook.com

<br>
<div align ="center">
  <img width="800" height="400" src="https://media.giphy.com/media/putDpToOBrGEpAXMMZ/giphy.gif">
</div>

> Step 6

: step 6 - create an app > chose manage bussiness integration > add display name 
Add purpose 
select ypu bussiness manager account 
This is going to create your app id

> Step 7: 

step 7 - select Messenger configuration

<br>
<div align ="center">
  <img width="800" height="400" src="https://media.giphy.com/media/MHiWZK6IoVYsLIQPSb/giphy.gif">
</div>


> Step 8: 

Step 8 - create or add a fan page for toby bot 

<br>
<div align ="center">
  <img width="800" height="400" src="https://media.giphy.com/media/1G28uDOVJRjlRVU3zZ/giphy.gif">
</div>


> Step 9

: step 9 - generate access token 
get access token to dialogflow 
 - verify token -(hello worl in our case) 
and copy back that verify url
Click on "start"

> Step 10 

:  step 10 - add Callback URl at facebook for develoeprs 
paste verify token 
at facebook console 

> Step 11 

: step 11 come to facebook developer console - add callback url 
verify tocken we created on dialogflow - click on verify and safe 

> Step 11

 step 11 - add subscriptions to the webhooks select messeges 
```
messages
messaging_postbacks
message_deliveries
message_reads
```
Click on Save it

> Step 12 

step 12 
- try your bot inegrations
Go to your fun page and sent a message 
Get sterted button

<br>
<div align ="center">
  <img width="800" height="400" src="https://media.giphy.com/media/DOA84CQhuVx5HSV4X9/giphy.gif">
</div>



> Step 13

: step 13 - at facebook developer console go to basic settings and add your app domain and 
privacy policy url , your terms of service URL

add also an icon 
chose an category 
nessenger bot for a bussines 
finally add a platform > website > add your website URL and save changes 
once you do it -

> Step 14

 - go to app review on requests 
Click on request permissions and features 
on pages_messing > Request advanced access 

Go back to Requests and give an folloving information - complete App verification 

Provide detailed step-by-step instructions on how a reviewer can test your integration and how you are using the requested permissions or features. Include any testing credentials required to access your integration.

> Step 15

 Edit your request permission features 
```
Please provide a detailed description of how your app uses the permission or feature requested, how it adds value for a person using your app, and why it's necessary for app functionality. 
```


Select yout page 
```Provide a detailed step-by-step video walkthrough of how your app will use this permission or feature so we can confirm it is used correctly and does not violate our policies
```

Click if approved I agree... and accept terms 

> Step 16

Submit for review so your bot could be a public!
