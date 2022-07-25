# s1_usb_scan

Test python script to deploy service in Windows 10 that will automatically scan USB flash-drives.

1. Installed python on Windows 10
2. Installed the requirements:

pip install -r requirements.txt

3. Install "Auto Py to Exe" application and compile exe from python script



4. Installed NSSM - the Non-Sucking Service Manager that can start a service from exe file:

http://nssm.cc/download

Screenshot 2022-07-18 at 16.38.04.png

5. Checked and started the service (in my example the name is "S1_USB")
6. Uploaded some samples on the USB drive and connected it for Windows 10 with an agent.
Service successfully got viruses from the USB drive right after connecting.

Screenshot 2022-07-18 at 16.41.42.png

