**Multi server, multi user distributed chat application in JAVA**
School project to build from the ground up a fault tollerent distributed chat application which uses the CAP theroem to optimize user performance.


**Introduction (from paper)**

The project improved upon our first iteration of a distributed group com- munication system. The new system is designed to provide availability and eventual consistency in the presence of server failures and network partition- ing. The main protocols implemented were

- Replication of Message Queue and a global clock from the server side to achieve eventual delivery of messages in the order they were sent.
- Failure protocol to reconnect partitioned servers and continue sending replicated Message Queues.
- Recongifure login, so that users can login from anywhere


We achieved a functioning scalable and dynamic distributed application. Providing high availability and eventual consistency in its message passing service. The messages have a guarantee to be sent to all members connect to the network at that time. Additionally messages sent from a client will be delivered to receivers in the order they were sent.
