**Completion Status:**

Mobile App:

-   Alpha Mobile App completed

-   A new device can be registered in the mobile app and can be
    controlled

-   Signup/Login accounts can be created with the mobile app

Server side:

-   Alpha Server Application completed

-   Application will accept requests from users to change device state
    and will update the database accordingly

-   Application can respond to client request with information and/or
    actions

Device functionalities:

-   Based on the action command from server, device can control a
    specific output. Example: LED brightness

-   Device is registered using local Wi-Fi/Hotspot

-   Prototype humidifier is completed. Users can control intensity of
    the humidifier via the mobile app

-   First prototype uses a board-to-board communication system, where a
    Raspberry Pi is used to fetch internet data, and then serial
    communication is used to provide the information to an Arduino,
    which then controls the humidifier

**Work in Progress:**

-   Working on adding Apple HomeKit, Google Home, and Amazon Alexa
    compatibility to the humidifier

-   Working on developing alternative, more efficient, and
    cost-effective methods to control humidifier intensity

-   The above research is ongoing because the avoidance of having to use
    two separate boards (Raspberry Pi and Arduino) makes adjusting
    settings faster (as communication via serial is prevented), and is
    less expensive

**Future Goals:**

-   Develop a more efficient and cost-effective model

-   Find ways to order components in bulk and develop a production-ready
    humidifier

-   Register a business and ship devices to consumers

-   Develop more devices using similar methods to the humidifier

-   Add software to implement automations which allows users to create
    interactions between multiple devices within the same user account

-   Make automations feature publicly available

**Example UI Elements from the Mobile Application:**

![page3image39158800](vertopal_92ca7ee26afa4628b7ff391517958562/media/image1.jpeg)

Above: UI for signing up/logging in to a user's account.

![page3image39159424](vertopal_92ca7ee26afa4628b7ff391517958562/media/image2.jpeg)

Above: UI elements used to connect to a hotspot the humidifier is
hosting. This hotspot is used to connect to the device directly so Wi-Fi
information can be exchanged.

![page3image39159008](vertopal_92ca7ee26afa4628b7ff391517958562/media/image3.jpeg)![page3image39159216](vertopal_92ca7ee26afa4628b7ff391517958562/media/image4.jpeg)

Above: UI elements used to control the intensity of a particular
humidifier.

**Humidifier Prototype Development**

![A picture containing person, indoor Description automatically
generated](vertopal_92ca7ee26afa4628b7ff391517958562/media/image5.png)

Above: retrofitting an existing humidifier with new IoT technology

![](vertopal_92ca7ee26afa4628b7ff391517958562/media/image6.png)

Above: development of software for controlling the humidifier, plus
testing of the finished product

**Project Demo Video:**

<https://youtu.be/2ThjjeAwD_k>
