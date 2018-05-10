# How to Connect to TestConnect24
The scripts for the revived WC24 Channels. The scripts aren't here yet but they will be here soon!

How to connect to TestConnect24 (currently):

If you want to connect to TestConnect24 service, you need:

- Windows Computer

- Nintendo Wii

- Internet Connection

**Steps:**

1. First download a program called [fiddler](https://www.telerik.com/download/fiddler/fiddler4) your computer. 

Click [here](https://www.telerik.com/download/fiddler/fiddler4) to download.

2. Run "FiddlerSetup" and once installed, open Fiddler 4

3. Open "AutoResponder" and click "Add Rule".

4. Click the "StringToMatch" and type this in "Rule Editor"

Request URL Pattern: http://miicontest.wapp.wii.com/first/XX.ces

Local file to return or *Action to execute: https://testconnect24.ml/first/XX.ces

5. Repleace the "XX.ces" with your region.

`79.ces is europe`

`49.ces is USA`

6. Now, click save and go into tools, options, then connections.

7. Check everything except "Use PAC Script"

> "Capture FTP Requests" is optional but uses most of your CPU.

9. Restart fiddler by closing it and running it again.

10. Now, head over to your Wii.

**Wii Setup:**

1. Go into Wii options, then Wii settings.

2. Go to Wii System Settings, then go to page 2 and click Internet.

**If you already have a connection setup, skip "For Wireless and For Wired Steps"**

3. Pick an available connection and connect to the internet.

**For Wireless**

1. Click "Wireless Connection" and click "Search for an Access Point".

2. Then pick your WiFi and enter your WiFi password.

3. Now do a connection test and see if your connection was successful.

4. If the connection test was successful, click "No" to skip performing a Wii system update.

**For Wired**

1. You are going to need a "USB to LAN adapter".

2. Click wired connection and do a connection test to see if it can connect.

3. If the coonnection test was successful, click "No" to skip performing a Wii system update.

**Wii Setup: Continued**

4. Now, click your connection #, click change settings, and turn right until you see "Proxy Server".

5. Click "Use" and then click "Advanced Settings".

6. Click "Proxy Server" and type in your IP Address.

**If you don't know your IP Address**

1. Head over to your computer and go into cmd.exe (command prompt)

2. Type in `ipconfig`.

> Your IPv4 Address should be the IP Address you use. The Wii doesn't support IPv6 Addresses.

**Wii Setup: Continued Again**

7. For the port, type "8888".

8. Then click "Confirm" and click "Save".

9. Do a connection test and if the connection test is successful, click "No" to skip performing a Wii system update.

10. GO back on your computer and check "Enable rules".

11. Now to make sure it works, click on Check Mii Out Channel and click "Start".

12. Now, if successful. It should give you this error code:

`Error Code: 258404`

Instead of:

`Error Code: 252102`

That's it! You're now officially connected to TestConnect24!

Thanks for join our service! 
