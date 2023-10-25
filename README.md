

1. First let's download the [64-bit Windows Server 2019 ISO](https://www.microsoft.com/en-us/evalcenter/download-windows-server-2019) 
<img src="https://i.imgur.com/PL4imJQ.png" height="80%" width="80%"/>

2. Create a new virtual machine (VM) and use the downloaded ISO file as the installation source. Make sure that you select the "Attended installation" method when prompted to have more control of what goes into the settings.
<img src="https://i.imgur.com/ZddkcRh.png" height="80%" width="80%"/>

3. Let's give an appropriate amount of hardware resources to the VM. I recommend a configuration with 3 processor cores and 4 GB of RAM. If you find your PC can't handle this load you can always give it less resources later. 
<img src="https://i.imgur.com/tj9BNrW.png" height="80%" width="80%"/>

4. Allocate a storage capacity of 50 GB and finalize the VM setup.
<img src="https://i.imgur.com/UnyKSQ0.png" height="80%" width="80%"/>

5. Given that this VM serves as an Active Directory (AD) and Domain Controller (DC) intended for internal user connectivity, it is important to configure two network adapters, one designated as a Router/NAT and the other as an Internal Network interface.
<img src="https://i.imgur.com/scdT5QH.png" height="80%" width="80%"/>
<img src="https://i.imgur.com/KkIyZhq.png" height="80%" width="80%"/>
