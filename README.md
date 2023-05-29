# Server1
This is my first server and it is hosted on port 8080. It was made using Golang followiung a tutorial (https://blog.logrocket.com/creating-a-web-server-with-golang/). Feel free to modify it, make it better, (or just make a monstrosity), and show me. 

Modifications:
  Added some notes when booting in the console

Note: It doesn't actually record the name field and the address field

List of pages:

(IP Here or localhost):8080
  
(IP Here or localhost):8080/hello
  
(IP Here or localhost):8080/form.html
  
(IP Here or localhost):8080/form (/form.html leads here)
   
   
Note: 8080 is not fixed, just modify some code to change it. 


Windows Users using Windows Defender Firewall:
  Issue: Windows Defender Firewall likes blocking the server when booting.
  
  Fix: DO NOT host on Public Networks, as it is a good way to invite hackers. 
  
  Reasoning: Windows Defender Firewall has good reasoning for blocking it. Bots scanning for vulnerablilites will see it, and start attacking you. This can lead to all sorts of nasty things
  
