# VirtualSensor

Program simulates smart electric sensors which count electricity consumption. 
If there is a case, like too huge consumption, the sensor sends information to server which sends e-mail message to it's owner.
The server is connected to MariaDB database and sensor sends to it data in every 30 seconds, about his status of being online. 
If server won't get status from sensor for 2 minutes it changes status in database to offline.
It's part of team project and will be developed in the future.
