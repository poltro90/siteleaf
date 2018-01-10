---
title: Interview with Rosalind Picard — Behind Empatica’s Research
date: 2018-01-10 08:16:00 Z
permalink: "/posts/interview"
Author: Mario Rossi
---

![1_2bssTsiLN-sAEUp_U8nzBw.jpeg](/uploads/1_2bssTsiLN-sAEUp_U8nzBw.jpeg)

Dear supporters,

Today we want to share with you one of the most interesting webinars hosted so far: the Ask Me Anything with Dr. Rosalind Picard, Empatica’s Chief Scientist and MIT Professor. During the recording of the webinar we were impressed by the quality and quantity of the questions received, so we decided to transcribe the answers and make them available for everyone on our blog. Make yourself comfortable, this is a long post.

#### ***Please remember that Embrace is a medical product for seizure monitoring only in Europe so far — the discussion below about seizures pertains to our ongoing scientific work and to the detection algorithm. For users in the United States, that is available only as part of a clinical trial using the Alert app.***

Yes, you read correctly: Embrace is a medical device in the European Union!

#### **How does Embrace’s seizure detection work?**

The Embrace measures three main kinds of data: movement, electrodermal activity (shortened as EDA — represents the electrical changes on the surface of the skin not necessarily involving sweat) and peripheral temperature. You can [read more about Embrace specifications here](https://www.empatica.com/embrace-watch-technology#specifications).

Devices on the market usually use two pieces of information: how strong and how long you’re moving. Instead Embrace uses more complex information, combining a lot of aspects of the movement, and completely novel information, electrodermal activity variations that start when regions deep in your brain are activated in an atypical way (as with seizures). Our algorithm uses advanced machine learning methods, and it is trained on data collected in epilepsy monitoring units in hospitals in order to recognize the complex patterns of movements and electrodermal activity that are most likely to accompany a convulsive seizure.

![1__OWRTXPMjIXj7xBhL3wMMg.jpeg](/uploads/1__OWRTXPMjIXj7xBhL3wMMg.jpeg)

**How accurate is the Embrace’s seizure detection algorithm?**

We’re committed to presenting our work in top scientific meetings and journals. Most recently we presented results in posters ([you can download here](https://www.researchgate.net/publication/308625338_Improving_convulsive_seizure_detection_by_exploiting_data_from_outpatient_settings_using_the_Embrace_wristband)) at the Partners Against Mortality in Epilepsy (PAME) Meeting in Virginia and at the Annual Epilepsy Meeting in Prague. We will be presenting new case study results at the American Epilepsy Society meeting in December in Houston.

To test the accuracy of our seizure detection algorithm we use a dataset of hundreds of verified seizures from epilepsy monitoring units. Using this set we can observe different rates of sensitivity, namely the percentage of correctly detected seizures. One challenge is that the more sensitive a method is to detect true seizures, the higher chance it will also detect false alarms (things that look like a seizure to the sensors, but aren’t). Thus, the higher range of sensitivity we set, the more false alarms we have to be willing to tolerate. In the PAME meeting we obtained up to 100% sensitivity with an average false alarm rate of less than one a day. At the Prague meeting, testing on a different set of data, we showed that we were able to reach 90% sensitivity of convulsive seizure detection with an average of 1 false alarm/day, and 95% sensitivity with an average of 2 false alarms a day. When we pushed the sensitivity higher (to 100%) then, on average, there were 5.7 false alarms/day. In other work with new data at Empatica, we are reaching 95% sensitivity with fewer than 2 false alarms over ten days, on average. **Results can thus vary a lot: for some people false alarms are rare, while for others they may occur more frequently throughout their day.**