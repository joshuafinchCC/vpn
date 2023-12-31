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
        <img src="" height="80%" width="80%"/>
  </p>
    
   <li> Next we will go to <a href ="https://whatismyipaddress.com/">What Is My IP Address</a> and install Proton VPN on the virtual machine. Install and register a free account, afterwards we can select "Quick" connect to use whatever fastest VPN tunnel is available. In this case its transfering us to</li>
   <li></li>
  </ul>
</p>

<br />

<h3>Signing up and configuring Proton VPN</h3>

<p>
  <ul>
    <li>Sign up for a free version of <a href ="https://account.protonvpn.com/signup?plan=free&language=en">Proton VPN</a></li>
    <li>Head back to your VM, download the Proton VPN client</li>
    <li>After installing, log in to Proton VPN and choose a VPN server to connect to outside of your VM's region</li>
    <li>After connecting to a VPN Server, go to What Is My IP Address and notice the IPv4 Address is different</li>
    <li>Attempt to browse websites such as Google or Amazon and notice the differences related to  your VPN Server (such as seeing Hangul is connected to a VPN server in South Korea)</li>
  </ul>
</p>

<br />
