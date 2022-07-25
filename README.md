# s1_usb_scan

Test python script to deploy service in Windows 10 that will automatically scan USB flash-drives.

1. Install python on Windows 10
2. Install the requirements:

pip install -r requirements.txt

3. Install "Auto Py to Exe" application and compile exe from python script:

https://pypi.org/project/auto-py-to-exe/

![alt text](https://github.com/kutumin/s1_usb_scan/blob/96f053e5ce281c10419998ffabed2ee67d9e01fe/images/Screenshot%202022-07-18%20at%2016.36.08.png)

4. Installed NSSM - the Non-Sucking Service Manager that can start a service from compiled exe file:

http://nssm.cc/download

![alt text](https://github.com/kutumin/s1_usb_scan/blob/96f053e5ce281c10419998ffabed2ee67d9e01fe/images/Screenshot%202022-07-18%20at%2016.38.04.png)


5. Checked and started the service (in my example the name is "S1_USB")

![alt text](https://github.com/kutumin/s1_usb_scan/blob/6d93095ec1e11d41bc7218698be737e6800eaf31/images/1.png)

6. Uploaded some samples on the USB drive and connected it for Windows 10 with an agent.
Service successfully got viruses from the USB drive right after connecting.

![alt text](https://github.com/kutumin/s1_usb_scan/blob/e886a7ffefbd8c4f7e8476f060d149db32b71185/images/Screenshot%202022-07-18%20at%2016.41.42.png)


