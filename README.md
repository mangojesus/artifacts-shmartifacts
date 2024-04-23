things to try - the obvious
============================

Uninstall and Reinstall GPU Drivers:

Use the "Add or Remove Programs" or "Apps & Features" menu in Windows to uninstall your current GPU drivers.
Then, download the latest drivers from NVIDIA's website and install them.

Check for Hardware Conflicts:

Ensure that there are no other hardware conflicts or issues with your system. 
You can use a tool like HWMonitor to check for any voltage, temperature, or other hardware-related problems.

More depth and log collection:
==============================

    • Reboot into Safe Mode:
    • Restart your computer 
    • As your computer is booting up, press the F8 key repeatedly 
    • Select "Safe Mode" from the options and let your computer boot up 
    
    • Check Device Manager:
    • While in Safe Mode, right-click on the Windows Start button 
    • Select "Device Manager" 
    • Look for your RTX 2070 GPU in the list 
    • Right-click on it and select "Properties" 
    • Make sure the device is working properly and the driver is installed correctly 
    
    • Run DXDIAG:
    • Press the Windows key + R to open the Run dialog 
    • Type "dxdiag" and press Enter 
    • In the DirectX Diagnostic Tool, check the "Display" tab for any errors or warnings related to your GPU 
    
    • Uninstall and Reinstall GPU Drivers:
    • Open the Start menu and search for "Add or Remove Programs" 
    • Find the NVIDIA graphics driver in the list and click "Uninstall" 
    • Once the uninstall is complete, go to the NVIDIA website and download the latest driver for your RTX 2070 GPU 
    • Install the new driver 

    • Open an Elevated Command Prompt:
    • Press the Windows key + R to open the Run dialog 
    • Type "cmd" and press Ctrl + Shift + Enter to open an elevated command prompt (run as administrator) 

    • Run the System File Checker:
    • In the elevated command prompt, type the following command and press Enter: 
    • sfc /scannow
    • This will scan your system files and try to repair any corrupted or missing files. 
    
    • Collect GPU-Z Logs:
    • Download and install GPU-Z from the official website: https://www.techpowerup.com/download/gpu-z/ 
    • Open GPU-Z and click on the "Save" button to generate a log file. 
    • This log file can provide valuable information about your GPU that can help with troubleshooting.
    
    • Check Event Viewer Logs:
    • In the elevated command prompt, type the following command and press Enter: 
    • eventvwr
    • This will open the Event Viewer application. 
    • Navigate to the "Windows Logs" section and look for any error or warning events related to your GPU or graphics drivers. 
    
    • Collect System Information:
    • In the elevated command prompt, type the following command and press Enter: 
        ◦ systeminfo
        ◦ This will provide a detailed report of your system's hardware and software configuration, which can be helpful for troubleshooting. 


        
After running these commands, you should have the following logs and information gathered:

    • GPU-Z log file 
    
    • Event Viewer logs 
    
    • System information report 
    
Please provide these logs and information, and I'll be happy to continue troubleshooting the issue with your RTX 2070 GPU.




Re: GPU buying
==============

“You wont need a new gpu ever again”
https://www.youtube.com/watch?v=J_s8JZgs-Vw

do not buy new gpus
https://www.youtube.com/watch?v=MT3GWasw2ew

please do not buy new gpus
https://www.youtube.com/watch?v=NnQfoZwjZh0


good luck
