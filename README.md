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


### Integration of Dialogflow with Telephony Gateway

### Integration of Dialogflow with Twilio Messaging Service

### Integration of Dialogflow with BigQuery

### Neomoprohic UX Prototype
![Alt Text](Img1.gif)

