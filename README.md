This file has the answer to the XLMRat_Lab exercise from Cyberdefenders

Q1
The attacker successfully executed a command to download the first stage of the malware. 
What is the URL from which the first malware stage was installed?

Anwser

First, you must open the zip file with Wireshark. Once you are in Wireshark, you can see the first HTTP requests.
Then you right-click on it and then press follow. Then Wireshark will open a separate file, and you can look at the contents 
of the HTTP request. Once you decode the letters, you can see that the answer is http://45.126.209.4:222/mdm.jpg.


Q2
Which hosting provider owns the associated IP address?

Anwser

Once you have located the IP address from Q1, you can enter it into the website https://www.iplocation.net/ip-lookup.
This site will provide you with the answer to the question, which is Reliablesite.net.
