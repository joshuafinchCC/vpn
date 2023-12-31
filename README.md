<p align="center">
<img src="https://github.com/joshuafinchCC/vpn/assets/155266044/5e274b98-bb25-4323-97cd-ae909e59b270" height = 60% width = 80%/>
</p>

<h1 align = "center">Understanding and Installing Virtual Private Networks</h1>
A Virtual Private Network (VPN) is a service that creaties a secure, encrypted connection between your device and the internet, giving you more privacy and security. It acts as a tunnel that encrypts the data you send and receive, making it difficult for foreign parties to monitor or intercept your online activities. This tutorial shows how to install a free VPN on an Azure Virtual Machine environment (tutorial for Virtual machine setup <a href ="https://github.com/joshuafinchCC/VM-VN-RDC">here</a>)

<br />

<h2>Environments and Technologies Used</h2>
<ul>
  <li>Microsoft Azure (Virtual Machines)</li>
  <li>Remote Desktop</li>
  <li>Internet Browser of your choice</li>
  <li>Proton VPN</li>
</ul>

<br />

<h2>Operating Systems Used</h2>
<ul>
  <li>Windows 10 Pro (21H2)</li>
</ul>

<br />

<h2>Installing Proton VPN</h2>

<h3>Setting up Resources and Citing IP Addresses</h3>

<p>
  <ul>
    <li>Before setting up, we can navigate to <a href ="https://whatismyipaddress.com/">What Is My IP Address</a> and take note of your IPv4 Address on your virtual machine. This gives us a starting reference for where our machine is located and should be based somewhere close to the region you selected upon creation. Notice we are starting in Arizona!</li>
    
  <p align="center">
        <img src="https://github.com/joshuafinchCC/vpn/assets/155266044/a240ee92-7ee3-447d-b326-ed7c16e49f18" height="80%" width="80%"/>
  </p>
    
   <li> Next we will go to <a href ="https://protonvpn.com/download">Proton VPN</a> and install Proton VPN on the virtual machine. Install and register a free account, afterwards we can select "Quick Connect" to use whatever fastest VPN tunnel is available. In this case its transfering us to Japan</li>
   
   <p align="center">
        <img src="https://github.com/joshuafinchCC/vpn/assets/155266044/63c0694b-3ae6-4935-9ed8-76ba6839a4b6" height="80%" width="80%"/>
  </p>
   <li>You'll notice after connecting to the VPN, if you browse the web, your languages may appear a little...different</li>
  </ul>

  <p align="center">
        <img src="https://github.com/joshuafinchCC/vpn/assets/155266044/93da2ec6-6f6e-4c1b-b041-bf53e5ff2cf2" height="80%" width="80%"/>
  </p>
</p>

<br />

<h3>Verifying our VPN is working</h3>

<p>
  <ul>
    <li>Finally, if we navigate back to <a href ="https://whatismyipaddress.com/">What Is My IP Address</a> you'll see that our IP started in the United States, and is now in Vietnam!</li>
  </ul>
</p>

 <p align="center">
        <img src="https://github.com/joshuafinchCC/vpn/assets/155266044/ca1061a7-b7d7-4038-a751-51064e3bd998" height="80%" width="80%"/>
  </p>

<br />
