
# Lab 2
### Code: 

![Image](Lab3Code.png)  

### Output:

![Image](Lab3SS1.png)  
![Image](Lab3SS2.png)  

The main method is called to run the code, it has implementation of the Handler class that deals with specific message requests.
Relevant arguments include handleRequest(URI url) taking a URI argument in order to get information of path and query string. A relevant field is the "messages" field where it stores and updates new message request while tracking the count. The messages field checks that the request path is "/add-message" and that the query string starts with "s=". Then, the query string is extracted and the web shows and output of the message. 

### Terminal:
![Image](Lab3Terminal.png)  

Something I learned in week 2 and week 3 is remote servers. I thought it was interesting that they can access my personal laptop from far away. I learned that remote servers can remotely do tasks such as hosting websites. Additionally, I learned that accessing remote servers is public so it is important to have private authentication to them as well.







