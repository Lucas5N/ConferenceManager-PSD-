<p align = "center"> <img src = "images/unisa.png" height = 70 wifth = 70></p>
<h1 align = "center">ConferenceManager-PSD-</h1>
<p align = "center"><h3>A simple application that lets the user manage conferences, events and such. This project is relevant to the Programming and data structures course.</h3></p>
<p>The application makes use of files, data structures and the related algorithms to best manage the aforementioned events. </p>

---

<p>Upon start the program will display the following menu...</p>
<img src = "images/menu.png">
---
<p>The User can choose between three types of event, each of which must have a valid date and time, the user then has to choose which room the evetn will take place in</p>
<img src = "images/eventCreation.png">
---
<p>If the user makes any mistake in the event creation process, the program will proceed to notify the nature of the mistake and let the user try again</p>
<img src = "images/errorEvidence.png">
---
<p>After the user has succesfully created the event the Menu will be displayed again. Upon close the program will either create if not found or update the <i>agenda.txt</i> file </p>
<img src = "images/fullAgenda.png">
<img src = "images/fullAgendaOutput.png">
---
<p>If the user wants to create a new event and there are no rooms left vacant, the event will be added to the queue and it will be added to a room as soon as it is freed, <i>note: The maximum amount of rooms can be changed by modifying the MAXSTANZE constant in the <b>utils.h</b> file</i></p>
<img src = "images/noFreeRooms.png">
<img src = "images/QueueOutput.png">
<img src = "images/AgendaAndQueue.png">
---
