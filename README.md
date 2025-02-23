<p align="center">
  <img src="images/unisa.png" height="70" width="70">
</p>

<h1 align="center">ConferenceManager-PSD-</h1>

<p align="center">
  <h3>A simple application that lets the user manage conferences, events, and such. This project is relevant to the Programming and Data Structures course.</h3>
</p>

<p>The application makes use of files, data structures, and the related algorithms to best manage the aforementioned events.</p>

<hr>

<p>The prgram is to be started by opening the <i>main.exe</i> file, once started, the program will display the following menu...</p>
<img src="images/menu.png">

<hr>

<p>The user can choose between three types of events, each of which must have a valid date and time. The user then has to choose which room the event will take place in.</p>
<img src="images/eventCreation.png">

<hr>

<p>If the user makes any mistakes in the event creation process, the program will notify the nature of the mistake and let the user try again.</p>
<img src="images/errorEvidence.png">

<hr>

<p>After the user has successfully created the event, the menu will be displayed again. Upon close, the program will either create (if not found) or update the <i>agenda.txt</i> file.</p>
<img src="images/fullAgenda.png">
<img src="images/fullAgendaOutput.png">

<hr>

<p>If the user wants to create a new event and there are no rooms left vacant, the event will be added to the queue and will be assigned to a room as soon as one is freed. <i>Note: The maximum number of rooms can be changed by modifying the MAXSTANZE constant in the <b>utils.h</b> file.</i></p>
<img src="images/noFreeRooms.png">
<img src="images/QueueOutput.png">
<img src="images/AgendaAndQueue.png">
