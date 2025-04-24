# Virtual-Private-Network-Setup

<p align="center">
<img width="199" alt="image" src="https://github.com/user-attachments/assets/1f307f11-da55-411d-8cc9-a391eb7b135a" />
</p>

<h1>Virtual Private Networking</h1>
In this tutorial, we will observe how a VPN Works:
1. Encryption – Your internet traffic is encrypted before it leaves your device, preventing third parties from intercepting your data.
2. IP Address Masking – The VPN routes your connection through a remote server, replacing your real IP address with one from another location.
3. Secure Connection – The encrypted tunnel protects your data from cyber threats, especially on public Wi-Fi networks. <br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Proton VPN

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Step 1 Observe your IP address from within your computer
- Step 2 Connect your computer to the Azure virtual machine
- Step 3 Observe your IP address from within the Azure virtual machine
- Step 4 Sign up for Proton VPN from within the Azure virtual machine
- Step 5 Connect your VM from within the Proton VPN
- Step 6 Observe your IP address from within the Azure citural machine

<h2>Actions and Observations</h2>

<p>
<img width="1440" alt="image" src="https://github.com/user-attachments/assets/779ae0f1-0d5b-43a0-b2cf-b34f3e651fe4" />
</p>
<p>
Browse to https://whatismyipaddress.com/ FROM WITHIN YOUR OWN MACHINE
</p>
<br />

<p>
<img width="653" alt="image" src="https://github.com/user-attachments/assets/f40a1f53-9969-4c35-b0c2-a42e2cf8a1c6" />
<img width="653" alt="image" src="https://github.com/user-attachments/assets/f59ab462-45a7-48e2-8368-142f64078b5d" />

</p>
<p>
    1. Log into the VM with Remote Desktop
    2. Browse to https://whatismyipaddress.com/ 
</p>
<br />

<p>
<img width="653" alt="image" src="https://github.com/user-attachments/assets/fd780c70-f97c-46c0-8ea5-c49e51e043e1" />
<img width="653" alt="image" src="https://github.com/user-attachments/assets/7822af61-af8c-4535-8f0e-e3647f97054d" />
<img width="653" alt="image" src="https://github.com/user-attachments/assets/221cfbd4-4aea-431a-8b2d-605c26e9f370" />
<img width="653" alt="image" src="https://github.com/user-attachments/assets/66c4a4df-8263-41c8-892b-70cf2a389754" />
<img width="653" alt="image" src="https://github.com/user-attachments/assets/0b12d0a6-442a-4a4d-b492-9a32f9245f49" />
<img width="653" alt="image" src="https://github.com/user-attachments/assets/7e2c62f7-52bd-4f96-8df0-44e26519d054" />

</p>
<p>
Sign up for ProtonVPN and test the VPN connection
4. On your actual computer, sign up for the free version of Proton VPN https://account.protonvpn.com/signup?plan=free&language=en  
5. Back within your VM, download the Proton VPN client
    1. Login to the VPN (https://account.protonvpn.com/login) and choose a VPN server in yet another country.
    2. Browse to https://whatismyipaddress.com/ 
</p>
<br />

<img width="981" alt="image" src="https://github.com/user-attachments/assets/cd8064c1-3903-4a8a-a35b-f214e284d168" />

</p>
<p>
Observe the new look for Google using the Proton VPN located in Japan
