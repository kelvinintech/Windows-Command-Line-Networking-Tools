# Windows-Command-Line-Networking-Tools



<p>
Windows operating systems can be managed using the command prompt instead of the graphical user interface(<a href="https://blog.hubspot.com/website/what-is-gui">GUI</a>).
  </p>

  <p>In this project I'll show you the  commonly used Windows command line tools.</p>

  

<h3>You ready?</h3>

![hacker gif](https://github.com/kelvinintech/Windows-Command-Line-Networking-Tools/assets/110644520/1b713340-6fd6-4db3-b59a-aaf2210898b0)


<p>
  Click Start and type the following: <b>cmd</b>
</p>



 <p>Right-click <b>Command Prompt</b> and select <b>Run as administrator.</b></p>

![Screenshot 2024-03-30 162619](https://github.com/kelvinintech/Windows-Command-Line-Networking-Tools/assets/110644520/158a07df-97a3-441a-a26e-321a33f23bb6)

<p>If prompted, Click <b>Yes</b> in the User Account Control pop-up window.</p>

<img width="442" alt="say yesScreenshot 2024-04-04 134025" src="https://github.com/kelvinintech/Windows-Command-Line-Networking-Tools/assets/110644520/35255272-7458-45d4-b6a7-e3d4b38c1904">


<p>Type the following in the Administrator: Command Prompt window and press <b>Enter</b></p>

![Screenshot 2024-03-30 162806](https://github.com/kelvinintech/Windows-Command-Line-Networking-Tools/assets/110644520/0e2e8cc0-bd41-4fe5-9667-d168e9ad4b40)

![pause](https://github.com/kelvinintech/Windows-Command-Line-Networking-Tools/assets/110644520/1c693fcc-f40f-421a-84c4-008f3967459b)



<p>Lets look at this command in further detail</p>

<p><b>netsh</b>: This is a command-line utility in Windows operating systems that allows you to configure and manage various network settings. It stands for "network shell.
</p>

<p><b>interface</b>:  Specifies that the following operation should be applied to a network interface.
</p>


<p><b>ipv4</b>: Specifies that the following operation should be applied to the IPv4 configuration of the network interface.
</p>


<p><b>set </b>: This subcommand is used to modify configuration settings.
</p>


<p><b>dnsservers</b>: Specifies that the operation being performed is related to DNS (Domain Name System) servers.
</p>


<p><b>Ethernet</b>: This is the name of the network interface for which the DNS server settings are being modified. It could be different on your system depending on your network setup.
</p>

<p><b>Static</b>:
   Specifies that the DNS server addresses provided in the command will be set statically, meaning they won't change unless you modify them again.
</p>

<p><b>Static</b>:
   Specifies that the DNS server addresses provided in the command will be set statically, meaning they won't change unless you modify them again.
</p>

<p>
  <b>
    192.168.255.13
  </b>
  This is the IP address of the DNS server you want to set as the primary DNS server for the specified network interface.
</p>

<p>
  <b>
    Primary
  </b>
  Indicates that the DNS server specified (192.168.255.13 in this case) should be set as the primary DNS server. This means it will be used primarily for DNS resolution, and if it fails, alternative DNS servers configured on the system may be used.
</p>



<p>
<b>By executing the command, the DNS server IP address configuration for the device was changed. The graphical user interface can be used to achieve the same outcome but will take more time.</b>
</p>

<p>
  The new DNS Server IP address that was configured can be seen in the output. Circled in blue.
</p>

![Screenshot 2024-03-30 163700](https://github.com/kelvinintech/Windows-Command-Line-Networking-Tools/assets/110644520/857b784d-6069-4aea-804a-a0298608c143)
