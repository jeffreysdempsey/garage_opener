# garage_opener
Garage door opener with video feed: hybrid Ember-Cordova app with video feed and Raspberry Pi server.


**Submission Materials**
1. A problem statement identifying the problem your product addresses.
2. Project goals and objectives in a numbered or bulleted list that you will undertake to address the identified problem.
3. The merit of accomplishing the project goals and objectives in terms of how it helps end users, society, or particular industries/sectors.
Have you ever needed to easily open your garage door and found yourself unable to do so? This is where Open Sesame, an in-development Android app comes in. Open Sesame allows a user to control their garage doors via bluetooth as well as visually verify the status of the garage door. There are plenty of hardware IOT and dedicated bluetooth devices with companion apps on the market which either control a garage door or provide a webcam live feed. Open Sesame does both, is open source, and for now, is DIY friendly, using a Raspberry Pi as the central control device, which the user interfaces.

I will develop an Android app, that controls two garage door openers and provides a video feed to check the open/close status of the doors. I am developing this app in particular to better learn how to make a hybrid Ember-Cordova app. The web side of the app will be served on a Raspberry Pi. The Pi will also serve as the video feed source with a camera module and serve a live video feed sans audio to the app. Additionally, the Pi will interface with the garage door openers themselves through relays (one relay per opener).
Develop an Apache Cordova server to host webview for hybrid app on the Raspberry Pi.


**Project timeline**


**Define the major tasks and expected time to completion**
**Create and submit a Gantt chart**

**Project-oriented risk list - What could go wrong in the project and why?**
|Risk name (value)  | Impact     | Likelihood | Description | Mitigation |
|-------------------|------------|------------|-------------|------------|
|Bluetooth range limited (40) | 7 | 4 | Bluetooth (not BLE) range is 100m | Monitor it by doing...|

**User stories**
  * As someone who has a garage, I want to open and close my garage door(s) using my phone, which I always have on me, instead of a dedicated remote.
  * As a worrier, I want to visually verify the status of my garage doors remotely.
  * As a forgetful person, I want to close my open garage door away from home.

**Misuser stories**
  * As a aspiring home invader, I want to connect to the opener to gain unauthorized access to the garage/home.
  * As an incompetent neighbor, I want to connect to the wrong device and block .
  * As a power interruption or outage, I will shut off the server.

**Discussion - Talk to Dr. Hale about your idea**
To Discuss:
 * Bluetooth integration.
 * Authenticate pairing?
 * Automatic pairing?
