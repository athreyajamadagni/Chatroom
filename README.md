# Chatroom
This project is a simple chat server that allows users to join and leave groups, send messages and share files (without a file size limit and compression). 

THEORY:
TCP: Transmission Control Protocol (TCP) is a standard that defines how to establish and maintain a network conversation by which applications can exchange data.
![image](https://github.com/athreyajamadagni/Chatroom/assets/75878205/74b6a336-5cab-4143-a0e2-689657987d8f)

 
SOCKET PROGRAMMING: A socket is a communications connection point (endpoint) that you can name and address in a network.
![image](https://github.com/athreyajamadagni/Chatroom/assets/75878205/7e357826-e2a8-4e46-bf9d-13bf37639fe0)

PROCEDURE:
SERVER:
1.	Open a terminal window in the directory containing server.py and run the following command:
2.	Replace localhost with your IP and 8000 with a TCP port number of your choice.
3.	The server console will display logs for:
•	New group creation
•	User connection
•	User disconnection
•	User kick
•	Join request
•	Join request approval
•	File transfer


CLIENT:
1.	Open a terminal window in the directory containing client.py and run the following command:
python client.py localhost 8000
2.	Replace localhost with SERVER IP and 8000 with a TCP port number of your choice.
3.	A prompt to enter a username will appear. Enter a username and press enter.
4.	Next, a prompt to enter a group name will appear. Enter a group name and press enter.
5.	If a group with the specified name does not exist, a new group is automatically created with the current user as admin. Otherwise, a join request is sent to the current group admin.
6.	Type anything to send a message or use the following commands:
7.	
Command		Behaviour
/1	View pending join requests**
/2	Approve pending join requests**
/3	Disconnect
/4	View all group members
/5	View group admin
/6	Kick member**
/7	Send a file to group
** = Admin only action	


 

