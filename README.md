<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>List of Prerequisites</h2>

- Install PHP Manager for IIS
- Install IIS URL Rewrite Module
- Install PHP
- Install osTicket
- Install Heidi SQL and configure with osTicket

<h2>Installation Steps</h2>


![Screen Shot 2024-03-23 at 8 30 14 PM](https://github.com/kennyfrantz/osticket-prereqs/assets/163783743/69b864b2-d498-4b1a-800b-74d81c4026c2)
<p>

</p>
<p>
I started off by installing PHP Manager for IIS to setup and configure PHP.  It was a pretty straightforward install.  
</p>
<p>
  
![Screen Shot 2024-03-23 at 8 30 35 PM](https://github.com/kennyfrantz/osticket-prereqs/assets/163783743/f355a947-a573-4d30-820f-d8815dbfc946)
<p>
  
</p>
<p>
Next I downloaded and installed the IIS URL rewrite module.
</p>
<br />

<p>

![Screen Shot 2024-03-23 at 8 39 55 PM](https://github.com/kennyfrantz/osticket-prereqs/assets/163783743/b913b5d4-c2ab-4680-aeb4-78ed3e33b10d)

<p>
<p>
Once the other steps were completed it was time to install PHP.  I created a directory for it on the C:\ drive then extracted the files into it.   
</p>
<br />

![Screen Shot 2024-03-23 at 8 49 40 PM](https://github.com/kennyfrantz/osticket-prereqs/assets/163783743/20880a06-eba0-42e8-b66f-e50bff6a27e0)

I installed osTicket and configured it in IIS using PHP Manager.

<p>


![Screen Shot 2024-03-23 at 8 56 34 PM](https://github.com/kennyfrantz/osticket-prereqs/assets/163783743/7ac5e1e4-50ea-4feb-8bc6-be76559b01eb)

The last step was to install Heidi SQL in order to connect to a database.  This was used  with osTicket in order to practice working help desk tickets.
