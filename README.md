<h1>Wireshark- Statistics</h1>


<h2>Description</h2>
Answering questions using the Statistics drop menu

<h2>Questions</h2>

- <b>Investigate the resolved addresses. What is the IP address of the hostname starts with "bbc"?</b>
- <b>What is the number of IPv4 conversations? </b>
- <b>How many bytes (k) were transferred from the "Micro-St" MAC address?</b>
- <b>What is the number of IP addresses linked with "Kansas City"</b>
- <b>Which IP address is linked with "Blicnet" AS Organisation?</b>


<h2>Languages and Utilities Used</h2>

- <b>Wireshark</b> 


<h2>Environments Used </h2>

- <b>TryHackMe VM</b> 

<h2>Program walk-through</h2>

<b>Answer the question below <br/>

Question 1: Investigate the resolved addresses. What is the IP address of the hostname starts with "bbc"?

<p align="center">
At the top of the Wireshark window, click on Statistics from the menu bar. In the drop-down, click on Resolved Addresses.: <br/>
<img width="1440" alt="Screenshot 2025-03-31 at 1 59 05 PM" src="https://github.com/user-attachments/assets/a80aef1c-2a04-4410-a472-6703ce2a9226" />


<br />
<br />
Resolved Addresses window will pop-up. At the top of this window is a search field labeled Search for entry. Type bbc into this search field.:  <br/>
<img width="1440" alt="Screenshot 2025-03-31 at 2 03 38 PM" src="https://github.com/user-attachments/assets/64c65c1a-ed79-44e1-b640-921ff43b0102" />


<br />
<br />
Answer is 199.232.24.81: <br/>





<h2>Program walk-through</h2>

<b>Answer the question below <br/>
What is the number of IPv4 conversations?

<p align="center">
Go to the Menu bar and click Statistics. Click on the Conversations option from the drop-down menu: <br/>
<img width="1440" alt="Screenshot 2025-03-31 at 2 13 54 PM" src="https://github.com/user-attachments/assets/400d3db0-5bf5-47e8-a5ac-2f65929ad900" />



<br />
<br />
The Conversations window will pop-up. You can see the different tabs at the top of this window. The tab that pertains to this question is the IPv4 tab. Look at the number on this tab, this is the answer to this question:  <br/>
<img width="1440" alt="Screenshot 2025-03-31 at 2 16 01 PM" src="https://github.com/user-attachments/assets/3c4be1d0-663f-4d14-8779-cf4834af5f10" />



<br />
<br />
Answer is 435: <br/>
