<h1>Cross Site Scripting Simulation Elgg</h1>



<h2>Description</h2>
Cross-site scripting (XSS) is a vulnerability often present in web applications that allows attackers to insert malicious code, such as JavaScript, into a victim's web browser. This malicious code enables attackers to steal sensitive information, like session cookies, from users. The security mechanisms used by browsers, such as the same-origin policy, can be circumvented through XSS vulnerabilities.

To illustrate the potential of XSS attacks, we have set up a web application called Elgg in our pre-configured Ubuntu virtual machine. Elgg is a widely-used open-source platform for social networking, which includes several countermeasures against XSS threats. However, for demonstration purposes, we have disabled these protections in our installation, making Elgg vulnerable to XSS attacks. Without these safeguards, users can post any arbitrary content, including JavaScript code, to user profiles.

In this project, vulnerability is to conduct an XSS attack on the modified Elgg installation. The attack should mimic the infamous Samy worm created by Samy Kamkar, which affected MySpace in 2005. The objective of this attack is to propagate an XSS worm among users so that anyone who views an infected profile becomes infected and automatically adds the attacker to their friend list.

<br />


<h2>Languages and Utilities Used</h2>

- <b>Python</b> 
- <b>Ununtu 20.04 VM</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

Task 1: Posting a Malicious Message to Display an Alert Window<br>
Task 2: Posting a Malicious Message to Display Cookies<br>
Task 3: Stealing Cookies from the Victim’s Machine<br>
Task 4: Becoming the Victim’s Friend<br>

<embed src a href="https://drive.google.com/file/d/1uCxoX4KH4VHQnJwIdMl1H1Zu7jlkE_vg/view" alt=""></a> </embed>



