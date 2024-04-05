<h1>Azure Sentinel Lab</h1>

 ###
<h2>Description</h2>
 Project includes the setup Azure Sentinel (SIEM) and its' connection to a live virtual machine, acting as a honey pot. I observed live attacks (RDP Brute Force) from all around the world. I used a custom PowerShell script (provided by Josh Madakor) to look up the attackers Geolocation information and plot it on the Azure Sentinel Map.
Also thanks to Nirakar Sapkota for the query script. 

<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Azure Sentinel</b> 

<h2>Environments Used </h2>

- <b>Windows 10</b>
- <b>Microsoft Azure</b>

<h2>Program walk-through:</h2>

<p align="center">
In Azure; Creating our honeypot VM <br/>
<img src="1 - Creating Virtual Machine.PNG" height="80%" width="80%" alt="DC and Client Walkthrough"/>
<img src="https://github.com/vonagle/ActiveDirectoryLab/blob/main/jmadakorhomelab.4.PNG" height="80%" width="80%" alt="DC and Client Walkthrough"/>
<br />
<br />
In Azure; Creating our Log Analytics Work Space <br/>
<img src="2 - Log analytics Work space creation.PNG" height="80%" width="80%" alt="DC and Client Walkthrough"/>
<br />
<br />
Connecting the VM to the Log Analytics Work Space <br/>
<img src="3 - connecting log analystic to VM.PNG" height="80%" width="80%" alt="DC and Client Walkthrough"/>
<br />
<br />
Remoting from our desktop into our VM and providing configurations <br/>
<img src="4 - remoting into VM.PNG" height="80%" width="80%" alt="DC and Client Walkthrough"/>
<br />
<br />
Creating custom logs for our analytics work space <br/>
<img src="5 - Creating custom logs for our analytics and checking.PNG" height="80%" width="80%" alt="DC and Client Walkthrough"/>
<br />
<br />
Generating a query to extract custom fields from the existing raw data field <br/>
<img src="6 - generating query to extract custom fields from rawdata.PNG" height="80%" width="80%" alt="DC and Client Walkthrough"/>
<br />
<br />
Running the query <br/>
<img src="7 - running our query.PNG" height="80%" width="80%" alt="DC and Client Walkthrough"/>
<br />
<br />
Creating a Workbook in Sentinel to provide a visualisation of the honeypot attacks <br/>
<img src="8 - creating workbook with query.PNG" height="80%" width="80%" alt="DC and Client Walkthrough"/>
<br />
<br />
Map of attacks <br/>
<img src="9 - creating visualisation of map.PNG" height="80%" width="80%" alt="DC and Client Walkthrough"/>
<br />

 
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
