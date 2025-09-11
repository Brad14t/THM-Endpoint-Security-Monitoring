# THM-Endpoint-Security-Monitoring
This will be my process through answering the Try Hack Me Endpoint Security Monitoring modules.

**1. What is the normal parent process of services.exe?**

`wininit.exe`

**2. What is the name of the network utility tool introduced in this task?**

`tcpview`

**3. Where do the Windows Event logs (.evtx files) typically reside?**

`C:\Windows\System32\winevt\Logs\`

**4. Provide the command used to enter OSQuery CLI.**

`osqueryi`

**5. What does EDR mean? Provide the answer in lowercase.**

`endpoint detection and response`

**6. Provide the flag for the simulated investigation activity.**

For this I just went through and picked what I thought was malicous, and ended uo getting the flag `THM{3ndp01nt_s3cur1ty!}`


**7. What PID should System always be?**

`4`

<img width="663" height="50" alt="Screenshot 2025-09-08 140558" src="https://github.com/user-attachments/assets/763dfb44-32cc-45d5-a7da-4608207aaea3" />

**8. side from csrss.exe, what process does smss.exe spawn in Session 1?**

<img width="723" height="124" alt="Screenshot 2025-09-08 140856" src="https://github.com/user-attachments/assets/d3a800a6-270f-4bd2-a40d-c6de75658a47" />

**9. What was the process which had PID 384 and PID 488?**

`smss.exe`

<img width="635" height="90" alt="Screenshot 2025-09-08 141134" src="https://github.com/user-attachments/assets/f750e2f4-c53b-4ed2-aa7c-f47d739a9341" />

**10. Which process might you not see running if Credential Guard is not enabled?**

`lsaiso.exe`

<img width="696" height="118" alt="Screenshot 2025-09-08 141318" src="https://github.com/user-attachments/assets/dee95e3a-8201-49d0-9284-b1fcd4336757" />

**11. How many instances of services.exe should be running on a Windows system?**

`1` There should only ever be 1 instance.

**12. What single letter parameter should always be visible in the Command line or Binary path?**

`k`

<img width="666" height="123" alt="Screenshot 2025-09-08 141717" src="https://github.com/user-attachments/assets/30f34b0e-4403-4d74-8365-bddaac077c91" />

**13. What is the parent process for LSASS?**

<img width="681" height="373" alt="Screenshot 2025-09-08 141846" src="https://github.com/user-attachments/assets/49387684-fae7-4955-abd8-6452591335cc" />

**14. What is the non-existent parent process for winlogon.exe?**

<img width="731" height="113" alt="Screenshot 2025-09-08 141952" src="https://github.com/user-attachments/assets/29ebe607-a821-445e-818a-a0147c156e64" />

**15. What is the non-existent process for explorer.exe?**

<img width="714" height="169" alt="Screenshot 2025-09-08 142104" src="https://github.com/user-attachments/assets/968a6a64-2be4-4bb1-bc8e-59f2cb71f632" />

<img width="1133" height="456" alt="Screenshot 2025-09-08 142126" src="https://github.com/user-attachments/assets/7e5c69cf-c1a3-433a-bae2-052653094a68" />

# Sysinternals

**16. When did Microsoft acquire the Sysinternals tools?**

`2006`

<img width="659" height="143" alt="Screenshot 2025-09-09 134016" src="https://github.com/user-attachments/assets/0b77fa14-e7f2-40e8-ace7-f8796c9a860a" />

**17. What is the last tool listed within the Sysinternals Suite?**

`Zoomit`

<img width="943" height="710" alt="Screenshot 2025-09-09 134441" src="https://github.com/user-attachments/assets/b7084b6d-a5bb-4ff7-9642-0e4c17da01bd" />

**18. What service needs to be enabled on the local host to interact with live.sysinternals.com?**

`webclient`

<img width="689" height="235" alt="Screenshot 2025-09-09 134741" src="https://github.com/user-attachments/assets/5f3b2436-ce13-4b6c-85f6-240ec5fa9425" />

**19. There is a txt file on the desktop named file.txt. Using one of the three discussed tools in this task, what is the text within the ADS?**

First I use 1 of the utlities that was provided `streams file.txt`

Then `./file.txt:ads.txt`

<img width="616" height="400" alt="Screenshot 2025-09-09 135658" src="https://github.com/user-attachments/assets/7901cbdb-6adb-4b07-b1e0-1a58d97d9b39" />

<img width="294" height="138" alt="Screenshot 2025-09-09 135650" src="https://github.com/user-attachments/assets/00525b76-4c48-4f53-a283-66d7e0392659" />

**20. Using WHOIS tools, what is the ISP/Organization for the remote address in the screenshots above?**

`Microsoft Corporation`

<img width="683" height="128" alt="Screenshot 2025-09-09 142430" src="https://github.com/user-attachments/assets/16375bb1-2e3e-43ac-a5a8-7a95c03eb844" />

<img width="565" height="351" alt="Screenshot 2025-09-09 142414" src="https://github.com/user-attachments/assets/71d9ad99-ae81-4bb1-81e6-4a5bf350a350" />

**21. What entry was updated?**

First I run `autoruns`

Then I see which entry was updated.

<img width="368" height="90" alt="Screenshot 2025-09-09 143152" src="https://github.com/user-attachments/assets/6c3ce4d6-81b5-45b5-ba44-bd35bd2009e6" />

**22. What is the updated value?**

<img width="282" height="300" alt="Screenshot 2025-09-09 144303" src="https://github.com/user-attachments/assets/dae98fc9-5c43-4881-ac37-4728ef37a733" />

**23. Run the Strings tool on ZoomIt.exe. What is the full path to the .pdb file?**

`strings ZoomIt.exe`

Then `.\ZoomIt.exe | findstr /i .pdb`

<img width="851" height="451" alt="Screenshot 2025-09-09 145143" src="https://github.com/user-attachments/assets/d1e2d497-fed1-4b5b-8afc-a0e9af90f1d5" />




















