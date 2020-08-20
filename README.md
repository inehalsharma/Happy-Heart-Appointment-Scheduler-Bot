# Happy Heart Appointment Scheduler Bot

Dialogflow Agent that schedules an appointment for you at the Happy Heart Cardiovascular Clinic.

## Introduction

![Test Image 1](logo.png)

In this project, I have created a conversational agent that asks the user for his/her details and checks whether an appointment slot is available on the day and the time, the user has entered.If yes, the agent confirms the appointment, otherwise, it asks the user to input another time slot.The approved time slot is added on the Google Calander by the agent.
To experiment with different technolgoies and to increase the reach of the chatbot, I have also integrated the agent with:
i) Actions on Google(Conducted Beta Testing)
ii) Telephony Gateway
iii) Twilio Messaging Service
iv) Big Query on the Google Cloud Platform

A brief description of these integrations is explained in the following sections. I also designed a Figma protoype of the chatbot UI using minimal neomorphism design and conducted a UX evaluation study to evaluate the users perspective about this latest trend.

### Integration of Dialogflow with Google Calendar

In this section, I learnt how Dialogflow connects with backend systems to provide rich and dynamic responses to users questions. In the agent’s GCP project, I enabled Google Calendar API and a service account to access Google calendar. Then I created the fulfillment and used the credentials I generated for the calendar access to connect it with the fulfillment. Finally I tested to see if the calendar invites are being set up per user request.

### Integration of Dialogflow with Actions on Google 

Once the agent is built on Dialogflow, I used the one-click integrations to connect to various platforms such as google assistant and web. I integrated Dialogflow with Actions on Google to enable the chatbot as a Google Action on Google Home or Assistant. I conducted Beta Testing for the chatbot on Actions on Google.

### Integration of Dialogflow with Telephony Gateway

The Telephony Gateway feature provides a telephone interface to the Dialogflow agent.
It is used to build conversational IVR (interactive voice response) solutions that integrate with the rest of the call center network. Currently (the service is in beta), you can select a telephone number hosted by Google. The biggest advantage of the telephony gateway is that it can be used to create the agent for chat or messaging services and turn it into an IVR without much effort. You just assign a phone number to the chatbot that is already built and provide the same experience to users across the phone and web.

### Integration of Dialogflow with Twilio Messaging Service

In this section, I integrated Dialogflow with Twilio messaging service for SMS which allows to easily create Twilio bots with natural language understanding. Programmable SMS service from Twilio makes sending and receiving SMS easily. In order to test the agent and Twilio integration use text messaging on a phone. Send text message to the number that was assigned to the Twilio messaging service and chat with the agent.

### Integration of Dialogflow with BigQuery

I created a fulfillment using inline editor and integrated it with BigQuery. Using BigQuery,  the chats data can be stored in a a database and queried and visualized to draw useful insights.

### Demo of the Agent:

#### Web Based View:

![Alt Text](https://media.giphy.com/media/W64Hu7Z4kboJWDmv5y/giphy.gif)


#### Chat Window Based View:

![Alt Text](https://media.giphy.com/media/hT1XJXS5UNx2VLRKun/giphy.gif)

#### Dialogflow Tester Window Based View: 

![Alt Text](Img1.gif)

### Neomoprohic UX Prototype


