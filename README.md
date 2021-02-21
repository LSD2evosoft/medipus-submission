# Medipus - Hack & Heal submission

## Introduction

Hi! We are a team of 4 engineers from evosoft Hungary:

- **L**illa Juhász
- **S**oma Zsják
- **D**ániel Vidó
- **D**ávid Vadászi

Together we formed LSD², to have fun solving medical related challenges in a much-much more agile way than we usually do!

## Chosen challenge

We have chosen the MSD challenge, to develop an online platform which helps individuals understand the importance of early screening and helps them conveniently get screened in the state healthcare system.

## Solution

We are developing a web based solution, that will

- Help ease users into participating in prevention rather than treatment
- Give them the nudge when they need it the most
- Provide useful information in a human-digestable way

Our product, *Medipus* will be available as a web- and smartphone app, and as a kind & helpful chatbot.

Other than providing a working prototype, we will explore the possibilities of integrating with existing healthcare systems as well as ways to deliver our content to the target audience.

## Availability

Our source code is available in two repositories:

- Meta repository (this one): <https://github.com/LSD2evosoft/medipus-submission>
- Website source: <https://github.com/LSD2evosoft/medipus-web>
- Android source: <https://github.com/LSD2evosoft/medipus-android>

Our demo products can be visited as well by the following addresses:

- Submission video: <https://www.youtube.com/watch?v=ORIF1vLcnT4>
- Website: <https://medipus-5c569.web.app/>
- Chatbot (standalone): <https://www.m.me/medipusbot>

## Chat bot

The Medipus Facebook Messenger chat bot was developed with Chatfuel. It has 3 main features: list the necessary screenings based on the answers given for age and gender, give detailed information about specific examinations and a quiz which allows users to collect Health Score. Besides the structured flows the user can input any question. The bot can handle open questions like "What is colonoscopy?", "What is the purpose of medical screening?" or questions about its personality like "What is your age?" or "Where do you live?". 
Please note that we are using the free version of Chatfuel, so it will reply to the first 50 users only. 
You can try the chat bot here: <https://www.m.me/medipusbot>

## Health Score 

Health Score keeps users motivated and acts like a percentage, but can go higher than 100, so users are able to "overfill" it. Every time users attend a necessary screening, take a monthly quiz on the chat bot or unlock an achievement they gain Health Score. In order to the keep the users motivated we also take some points from them over time. Health Score decreases by 5 points monthly in case of inactivity (not logging in, not attending examinations etc.). In case there is an overdue recommended examination for the user the Health Score decreases faster, by 10 points monthly. Detailed description can be found here:
<https://github.com/LSD2evosoft/medipus-web/blob/main/docs/Medipus_scoring_v2.xlsx>
