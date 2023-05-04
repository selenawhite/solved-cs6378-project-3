Download Link: https://assignmentchef.com/product/solved-cs6378-project-3
<br>
In this project, you are required to implement the same functionality as Project II, with the same number of servers (3) and clients (5), except for the following differences:

<ol>

 <li>The clients, numbered <em>C</em><sub>0 </sub>through <em>C</em><sub>4 </sub>execute Maekawa’s mutual exclusion algorithm among them (instead of the Ricart-Agrawala algorithm) to decide which client gets to enter the critical section to access a file.</li>

 <li>Quorum size is equal to three.</li>

 <li>Quorum of client <em>C<sub>i </sub></em>consists of the set {<em>C<sub>i</sub>, C</em><sub>(<em>i</em>+1)<em>mod</em>5</sub><em>, C</em><sub>(<em>i</em>+2)<em>mod</em>5</sub>}.</li>

 <li>Make sure to implement all messages for Maekawa’s algorithm, including ENQUIRE, YIELD and FAILED.</li>

</ol>