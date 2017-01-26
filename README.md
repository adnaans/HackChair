# HackChair
Forked from original repository that I worked on: https://github.com/kvfrans/HackChair

The Hack Chair is a creative analytical tool that is built from a chair. We used an ordinary plastic chair, cardboard, duct tape, 2 iPhones, a muse headband, and empty nacho boxes.

First, the Hack Chair uses an iPhone's gyroscope to detect how far back a chair is titled. This is useful to keep the students safe. Of the 7,000 schoolchildren admitted to hospital each year as a result of chair-related accidents, 70% were rocking back dangerously, according to the analysis of government statistics by a south London teacher. By measuring when the user reaches a tilting hazard, we give an immediate notification that also suggests other alternative chairs. This feature used the Target API.

The muse brain-sensing headband on the user is used to check how sleepy a student is based on their eye movements and how the chair is positioned. Using the iPhones that we used for other features, we were able to vibrate the user if they fell asleep. This feature used the muse SDK.

The Hack Chair uses the camera as a proximity sensor on the iPhone to detect how good a student's posture is when sitting on a chair. When the posture of the user is bad, Hack Chair will constantly remind the user to have a good posture. This can prevent medical problems such as scoliosis.

Also, arm of the Hack Chair has a camera that allows teachers and other students to collaborate. This tool can also help prevent academic dishonesty. This feature used the Moxtra API.

At the end, we wrapped together the whole project into a Javascript Library called “hackchair.js” so that anyone could use our technology to find analytics of their chair.
