This is a LabVIEW toolkit that replaces the experiment execution engine of the MIT ELVIS LabServer.

It performs the following actions:

- looks for queued experiments
- If found dequeues the experiment
- parses the experiment specification XML document
- handles the parameters over to the specific LV VI
- executes the experiment and writes the experiment result into the database to be retrieved by the Service Broker. 

It was designed for the MIT ELVIS Lab Server, but it should work work as a general solution for any batched lab.