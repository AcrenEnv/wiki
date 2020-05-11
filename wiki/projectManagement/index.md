<h1> Project Management</h1>

<div style="background-color:black;color:white;padding:20px;">
  <h2>Current status: Step 1</h2>
  <p>---</p>
</div> 
<br>


<p>Our project management is based on 8 steps:</p><br>


<dl>
  <dt>Define Goals</dt>
  <dd>State the goal of the system, write one or two sentences summarizing the goal, and post it in a place that is visible to all developers.</dd>
  <dt>Identify actors</dt>
  <dd>Identify the actors which interact with the system (human roles and external systems/devices). Here you can possibly apply the idea of determining the trust/untrust between actors, to assess.</dd>
  <dt>Define system user-stories</dt>
  <dd>Write the system requirements in term of user stories or features. In this phase, the system to be developed should be considered as a whole. The fact that it will be developed using a Blockchain or a set of servers in a cloud is not important.</dd>
  
  <dt>Design of the SC subsystem</dt>
  <dd><li>Redefine the actors and the user stories, like those described in steps 2 and 3, considering only those directly interacting with the SC subsystem, and possible external SCs used;</li>
  <li>Define the decomposition in SCs (one or more); define the used libraries and external SCs; design the inheritance structure, and the usage of interfaces;</li>
  <li>Define the connections and the flow of messages and Ether transfers; define the state diagram (if needed);</li>
  <li>Define the data structure, the external interface (ABI) and the events;</li>
  <li>Define the internal functions and the modifiers;</li>
  <li>Define the tests and the security assessment practices.</li></dd>

  <dt>Design of the SC subsystem</dt>
  <dd><li>Redefine the actors and the user stories, like those described in steps 2 and 3, but adding the new (passive) actors represented by the SC system; define the acceptance tests of the subsystem;</li>
  <li>Decide the broad architecture of the system, taking into account the server and client application, the Blockchain node(s) to use;</li>
  <li>Define the User Interface of the relevant modules, including the apps;</li>
  <li>Perform an analysis of the system, defining the decomposition in modules, the flow of messages, the structure and storage of permanent data, including those anchored to the Blockchain through hash digest memorization, the data or class structure of the application(s); the connections and data flows between participants, including the SCs must comply with the analysis of step 5.3;</li>
  <li>Define the state diagrams (if needed), the detailed interfaces of the various modules, the response to the events raised by SCs;</li>
  <li>Perform a security assessment of the external system.</li></dd>


  <dt>Code and test the systems; in parallel:</dt>
  <dd><li>Write and test the SCs, starting from their data structure and functions;</li>
  <li>Implement the USs of external subsystem with an agile approach (Scrum or Kanban);</li></dd>


</dl>

<p>Our project management is based on the concept of Michele Marchesi, Lodovica Marchesi and Roberto Tonelli. Details on the individual process steps can be found in  "An Agile Software Engineering Method to Design Blockchain Applications".</p>
<p>Everyone who is interested in participating in the Acren project can actively participate according to this scheme.</p>




