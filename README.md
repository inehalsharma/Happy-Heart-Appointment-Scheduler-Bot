# Happy Heart Appointment Scheduler Bot

![Test Image 1](logo.png)

## Introduction

## Goal
Design a Dialogflow agent that schedules an appointment for you at the Happy Heart Cardiovascular Clinic.

## Glossary
Before diving into the project, it would be good to have ome basic knowledge about the key terminoogies used in the project:
i)[Agents](https://cloud.google.com/dialogflow/es/docs/agents-overview)
ii)[Intents](https://cloud.google.com/dialogflow/es/docs/intents-overview)
iii)[Entities](https://cloud.google.com/dialogflow/es/docs/entities-overview)
iv)[Context](https://cloud.google.com/dialogflow/es/docs/contexts-overview)

## Tasks Accomplished and Technologies Used
In this project, I have created a conversational agent that asks the user for his/her details and checks whether an appointment slot is available on the day and the time, the user has entered.If yes, the agent confirms the appointment, otherwise, it asks the user to input another time slot.The approved time slot is added on the [Google Calander](#integration-of-dialogflow-with-google-calendar) by the agent.
To experiment with different technolgoies and to increase the reach of the chatbot, I also integrated the agent with:
i)[Telephony Gateway](#integration-of-dialogflow-with-telephony-gateway)
ii)[Twilio Messaging Service](#integration-of-dialogflow-with-twilio-messaging-service)
iii)[Big Query on the Google Cloud Platform](#integration-of-dialogflow-with-bigquery)
iv)[Integrated the bot with Google Vision API]

A brief description of these integrations is explained in the following sections. To experiment with the UI of the bot, I designed a simple [front-end] for the bot using Django framework. I also designed a [Figma protoype](#neomoprohic-ux-prototype) of the chatbot UI for mobile applications using the minimal neomorphism design. 

### Integration of Dialogflow with Google Calendar

In this section, I learnt how Dialogflow connects with backend systems to provide rich and dynamic responses to users questions. In the agent’s GCP project, I enabled Google Calendar API and a service account to access Google calendar. Then I created the fulfillment and used the credentials I generated for the calendar access to connect it with the fulfillment. Finally I tested to see if the calendar invites are being set up per user request.

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

#### Appointments Booked on the Google Calender:  

![Alt Text](CalView.png)

### Neomoprohic UX Prototype

Protoyped the UI of the agent using neumorphic design in Figma.A few screens of the prototype are given below:

![Alt Text](UI.png)

The working prototype can be viewed at the following link: (Click on the mic icon at the bottom of the screen to navigate to the next screen)

https://www.figma.com/proto/q5Nw4E4Vu2hdenZ7jBKknb/Neumorphism-UI-Kit?node-id=91%3A231&scaling=scale-down


