# Enriching Guest Registrant Data With OpenAI API

19-09-24

![alt text](../images/1/dash.png)

## Use Case

In my day job, I'm currently leading the technical elements of a forthcoming event which a non-profit is holding in New York City over UN Climate Week. 

Even small(ish) events can pose huge data challenges. Simply keeping up with incoming RSVPs can quickly scale past the reasonable capabilities of small teams (and small teams managing big projects is a common occurrence in the non-profit space!)

To assist with our preparations for this event, I built an Airtable base. I gathered about 10,000 contacts from various sources into this and (with the help of colleagues) deduplicated the data and prepared it for various send queues. 

RSVPs arrive via Typeform and are then passed to Airtable via Zapier. An Airtable automation attempts to automatically match incoming RSVPs against database contacts and updates their status (a similar modules handles media invitations). It's a hybrid CMS, media management, and event management internal tool. I used [NoLoco](noloco.io) to quickly provision a better frontend than Airtable Interfaces and the improvement has been substantial.