<p align="center">
<img src="https://i.imgur.com/3IiTnEf.png" alt="peppermint.sh logo"/>
</p>

<h1>Self Host Helpdesk - Peppermint.sh</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system Peppermint.sh.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: host your own HelpDesk](https://www.youtube.com/watch?v=Kq0BMVhbFkA&t=5s)

<h2>Environments and Technologies Used</h2>

- Linode (Virtual Machines/Compute)
- Docker
- CLI

<h2>Operating Systems Used </h2>

- Ubuntu 20.04 LTS</b> (21H2)

<h2>List of Prerequisites</h2>

- Linode Account

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/a4nR9RT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/GTLiXoD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/GUxNfmg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<img src="https://i.imgur.com/VVhSMbi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<img src="https://i.imgur.com/6eFJ99o.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go to Linode and make a free account. Free account will give you $100 credit for 60 days. Once that is created you will then go to create Linode. Go to marketplace. Search and select Peppermint. After selected you will configure the linode. Use Ubuntu 20.04 LTS. As for plan select anywhere from 2GB to 8GB I run it with 4GB just fine.
</p>
<br />

<p>
<img src="https://i.imgur.com/YAQsidf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/XDBpbql.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/AT4zNzR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/Mhk3Q1h.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/0iPkZJG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next you will want to open the LISH console and login to the root ssh. Or you can simply use your own built in terminal. That is what I prefer. After getting root into the ssh. Run the command docker ps. This will show you that your docker container is running and what port it will be on. Which is 5001. You will find your reverse DNS in the network tab on linode website. Copy that. Paste in your browser bar with :5001 behind it or whatever port you are given. You will then put in the default information. Admin@admin.com and  password will be 1234. 
</p>
<br />

<p>
<img src="https://i.imgur.com/kx8RLCV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/OADMRdk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/cybKkor.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://imgur.com/a/gg58GoW" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
At this point you will be able to; create tickets, users to assign the tickets to. Clients as well to mimic someone putting a ticket request. Its quite simple yet effective at building a foundation for understanding the SLA's. Have fun and be creative.
</p>
<br />
