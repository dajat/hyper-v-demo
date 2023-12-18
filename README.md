<p align="center">
<img src="https://imgur.com/KBxgE5K.png" alt="Hyper-V"/>
</p>

<h1>Hyper-V</h1>
In this tutorial, we observe how to install Hyper-V and create a virtual machine. <br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Hyper-V

<h2>Operating Systems Used </h2>

- Windows 10
- Windows 11

<h2>High-Level Steps</h2>

- Step 1: Remotely Login to Virtual Machine
- Step 2: Enable Hyper-V on Windows
- Step 3: Download and Install Virtual Machine in Hyper-V
- Step 4: Launch Hyper-V Virtual Machine

<h2>Actions and Observations</h2>

<h2>Login to Virtual Machine</h2>
<p>
<img src="https://imgur.com/aAyXcl2.png" height="90%" width="90%" alt="Disk Sanitization Steps"/>
</p>
<p>
Assuming that you have already created a virtual machine in Microsoft Azure, login to the virtual machine by using a remote desktop connection (Windows) or Microsoft desktop (Mac).
</p>
<br />
<h2>Enable Hyper-V in Windows</h2>
<p>
<img src="https://imgur.com/eK3Yw94.png" height="90%" width="90%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, navigate to the "Control Panel" --> Click on "Programs" --> Click on "Turn Windows Features On or Off" --> Click on "Hyper-V" and ensure that each box is checked. Click OK to turn the feature on. This will prompt the virtual machine to restart.
</p>
<br />
<h2>Download and Install Virtual Machine in Hyper-V</h2>
<p>
<img src="https://imgur.com/jHKAQgS.png" height="90%" width="90%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once logging back in, open "Hyper-V Manager. Under Hyper-V Manager in the left hand corner, right-click on your computer name, hover over "New", and select "Virtual Machine"
</p>
<br />
<h2>Download and Install Virtual Machine in Hyper-V (cont.)</h2>
<p>
<img src="https://imgur.com/G84Yba8.png" height="90%" width="90%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the configuration wizard, you can name the virtual machine and choose to store the virtual machine files in a different location, if needed.
</p>
<br />
<h2>Download and Install Virtual Machine in Hyper-V (cont.)</h2>
<p>
<img src="https://imgur.com/Y0TJfSo.png" height="90%" width="90%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, you can choose the generation of the machine, which supports either 32 or 64-bit operating systems.
</p>
<br />
<h2>Download and Install Virtual Machine in Hyper-V (cont.)</h2>
<p>
<img src="https://imgur.com/4ucQRVe.png" height="90%" width="90%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, you can assign memory to your virtual machine. You can check how much memory is left on the PC by navigating to “Task Manager.” In this case, we have 13.5 GB available and can use less GB due to speed and performance.
</p>
<br />
<h2>Download and Install Virtual Machine in Hyper-V (cont.)</h2>
<p>
<img src="https://imgur.com/HWF3TSA.png" height="90%" width="90%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, you have the option to choose a network adapter. And configure to a virtual switch or can remain disconnected. In this demo, we can choose “default switch”
</p>
<br />
<h2>Download and Install Virtual Machine in Hyper-V (cont.)</h2>
<p>
<img src="https://imgur.com/2G35H5O.png" height="90%" width="90%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, you can choose where the storage is placed on a virtual hard disk or the location of your choice. You can check how much storage is on your PC under File Explorer.</p>
<br />
<h2>Download and Install Virtual Machine in Hyper-V (cont.)</h2>
<p>
<img src="https://imgur.com/Y7jGpUv.png" height="90%" width="90%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, you can choose to install the operating system now or later, since there is no operating system on the virtual machine. Click, Next and Finish.
</p>
<br />
<h2>Download and Install Virtual Machine in Hyper-V (cont.)</h2>
<p>
<img src="https://imgur.com/KgHducn.png" height="90%" width="90%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once you have finished the installation wizard for the virtual machine, right-click on the computer name under Hyper-V Manager and select “Quick Create” to choose an operating system.
</p>
<br />
<h2>Download and Install Virtual Machine in Hyper-V (cont.)</h2>
<p>
<img src="https://imgur.com/RrvEQHj.png" height="90%" width="90%" alt="Disk Sanitization Steps"/>
</p>
<p>
Select the operating system of your choice and click on virtual machine. Please keep in mind that this may take at least 30 minutes. Once the download is complete, click “Connect”.
</p>
<br />
<h2>Download and Install Virtual Machine in Hyper-V (cont.)</h2>
<p>
<img src="https://imgur.com/uekfcgm.png" height="90%" width="90%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the next screen, click “Start” to turn on the virtual machine and sync the Windows 11 operating system.
</p>
<br />
<h2>Download and Installation is Complete</h2>
<p>
<img src="https://imgur.com/c6Yklwr.png" height="90%" width="90%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once the login has finished loading, you will be able to access files and the web browser and have successfully set up the virtual machine in Hyper-V.
</p>
<br />
