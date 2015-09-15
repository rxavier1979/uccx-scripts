#ITAPS

**Install:**

1.	Create new prompt folder called "ITAPS"
2.	Unzip prompts to folder called "ITAPS" 
3.	Install TAPS AAR as you normally would. This is required so that the JAR files get loaded onto UCCX. (Might need to restart engine if you are just now installing this AVR)
4.	Upload ITAPS.aef script into script repository
5.	Update TAPS application (built by TAPS AVR) to use the ITAPS.aef script
6.	Specify CUCM IP Address and PIN

**Prompts:**

pr_Welcome: Welcome to the Telephony Auto Provision System.

pr_EnterPIN: Please enter your PIN followed by the pound or hash key. 

pr_EnterDN: Please enter the directory number that should be assigned to this phone followed by the pound or hash key. 

pr_EnterDNagain: Please enter the directory number again followed by the pound or hash key.

pr_EntryDoesNotMatch: Those entries do not match. Please try again.  

pr_ErrorDuplicate: The directory number entered is on a shared line. To identify the device, enter the phone number mask followed by the pound or hash key.

pr_ErrorWithCode: The error code reported was...

pr_Success: Operation successful. The phone will reboot now. 

pr_Invalid_Entry: Invalid entry or time out. Please try again.

pr_Error: There was an error performing this operation. 

pr_Goodbye: Goodbye
