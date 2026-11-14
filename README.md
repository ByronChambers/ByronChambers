<b>My Networking Journey</b>

<p>This is my projects page to show the experience I gain through my learning journey.
I could use AI to provide a perfect professional display of my work but I don't think that
would be very authentic to what I am trying to display on this page. So I will have 
my own simple outline for each of my projects that is more focused on my steps and what I 
learned through the process of each project.</p>

Each outline will follow a 5 Step outline policy.<br>

Project Title:<br>
Project Objective/Task/Goal:<br>
Project Tools/Equipment/Software:<br>
Project Detailed Steps:<br>
Project Lesson Learned:<br>
<br>

* These projects will be guided by Google Gemini chat to help me through my projects and to understand the core principles that I need to take away from the project. I am new to the IT/Network industry so these projects are not meant as a flex of my skill level but more of experience gained to enhance my knowledge and foundational skills I need to start a successful career. (I understand AI is not always 100% accurate)
<hr>
#1
Project Title:Hardware Level Security Key<br>
Project Objective/Task/Goal: Setup USB-C Security Key for Windows 11 Local Login<br>
Project Tools/Equipment/Software:Swissbit Ishield Key 2<br>
<br>
Project Detailed Steps: I downloaded OpenSC 64bit and OpenSSL lite. Installed them both. I ran the command prompt in administrator and Gemini provided command lines for me to generate a certificate. I ran CertMgr and exported my certificate to the desktop as a saved file. I imported that saved certificate file to my slot 9A on my Swissbit device. Finally I ran command lines provided by Gemini to backup and then map my certificate to windows.I then restarted my computer to attempt to login with the Swissbit. ( Failed ) So I decided to apply my windows login password to the Swissbit and use the touch function to enter my password at the login screen.<br>
<br>
Project Lesson Learned: This was a great opportunity to learn the steps it takes to create and map a certificate key for network login like through active directory. The standard local windows login does not have the functionality to seek out a key certificate registered to a hardware device and use it as authentication. <br>
<br>
#2
Project Title: PFsense Router Presetup for Starlink<br>
Project Objective/Task/Goal:Setup my Lenovo M920q mini with an installed Nic 2 port card as a PFsense Router for Starlink<br>
Project Tools/Equipment/Software: Lenovo M920q mini with installed 2 port NIC card/ PFsense Img on a usb drive.<br>
Project Detailed Steps: I powered on the Lenovo PC and entered the BIOS to ensure it would seek the USB drive as the initial start up. I encountered an error with the start up because BEOS was detecting the wireless Lan and I needed to disable it in the Bios. ( done ) During the install I learned that routing outgoing traffic through my intergraded Ethernet port wont slow down my internet speed because I asked Gemini why don't we use the other port on the NIC card I installed and it was explained to me.  ( Project paused... AI lies 😂 I need an internet connection to complete the setup process. Good thing i have my starlink kit..) Resuming now that I have setup starlink and got it going. I confirmed the partition and it is finally downloading and installing PFsense. Installation complete/restarted and we are all good.
<br>
Project Lesson Learned: I learned that my internet strength wont bottleneck from passing it through my integrated network card. I also was reminded to not trust Ai for the 50th time. 😂  
<!--
**ByronChambers/ByronChambers** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
