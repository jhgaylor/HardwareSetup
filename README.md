# Create `NeD-XXX-###`

1. Install lubuntu 12.04

	`Your Name: SocialDrizzle`

	`Computer Name: NeD-XXX-###`
		
		- XXX = School Initials
	
		- ### = NeD serial number
		
			- ex. ned-MSU-100
	
	`User Name: socialdrizzle `
	
	`Password: S9@rx4L`

	Enable auto login
	
2. Go to [Hardware Setup](https://github.com/NestedData/HardwareSetup), download, and extract to `~`

	
3. Open terminal execute 

	`cd HardwareSetup-master && sudo bash NeD_Startup.sh`
	
# The installer will prompt you to configure this
	
* Set all energy settings to never

	Menu -> Preferences -> Screen Saver
	
		Mode -> Disable Screen Saver
		
	Menu -> Preferences -> Power Manager
	
		General
		
			when pwr btn pressed = shutdown
			
			uncheck boxes
			
		On AC
		
			Actions: slider = never
			
			Monitor: both sliders = never
			
		Extended
		
			uncheck lock screen

* [Click this link to sign in as NeD's user at SD](http://socialdrizzle.com/sign-in) or go to  http://socialdrizzle.com/sign-in

* Configure TeamViewer:	
	Extras -> options
	
		check "Start teamviewer with system"
	
	
# When Finished

Close web browser and reboot into NeD


# Developers

To freeze pip requirements

`pip freeze > requirements.txt` from within the root of the hardwaresetup repo while in the appropriate virtualenv

