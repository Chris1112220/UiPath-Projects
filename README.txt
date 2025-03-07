VPN Login setup instructions

These instructions include to activities the User must do prior to running this program. 




					Mapping your Cisco VPN path location to your individual UiPath application

1) Click the search button at the bottom left.

2) In the search function type Cisco to bring up the options for the Cisco AnyConnect Secure Mobility Client

3) Click on open file location

4) In the file path at the top of the screen, click in the white space and copy the file path. It should looks something like the example below "C:\ProgramData\Microsoft\Windows\Start Menu\Programs\Cisco\Cisco AnyConnect Secure Mobility Client"

5) In UiPath, on the far most right side of your screen, click the icon that says Data Manager.

6) Where it says Variables, click the dropdown for the variable winCiscoVariable

7) Where it says default Value, click the plus button and click text.

8) Paste the file path you got from in step 4, and click ok.  



					Setting up your Credentials in the Credential Manager

1) In UiPath, go to activity 3.1 Get Username/Password

2) Under Saved Credentials, yours should be blank unless you have created one prior. 

3) click on the Key icon to add your credentials.  

4) Click on the Add Credentials button on the bottom left

5) Set app or site to VPN in all caps

6) Type your username and password in the respective locations case sensitive and press ok



Congrats you are done with the setup
	
Test and run you application to see if it works!!





