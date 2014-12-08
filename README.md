# Create `NeD_base`

1. Install lubuntu 14.04
2. Clone & navigate to this repo in terminal `git clone https://github.com/NestedData/HardwareSetup && cd HardwareSetup`
3. Execute "bash run.sh"
4. Set all energy settings to never
	Menu -> Preferences -> Light Locker Settings
		both sliders = Never
		enable LL = OFF
	Menu -> Preferences -> Power Manager
		General
			when pwr btn pressed = shutdown
		On AC
			Actions: slider = never
			Monitor: both sliders = never
		Extended
			uncheck lock screen
5. Configure TeamViewer
	Autostart on boot
	Disable windows on boot 
6. Reboot into NeD_base

# Clone `NeD_base` to another drive

# Install `NeD_base` image to a NUC

# Upgrade `NeD_base` to `NeD_XXX#`

1. Open terminal
2. Clone & navigate to this repo in terminal `git clone https://github.com/NestedData/HardwareSetup && cd HardwareSetup`
3. Execute "bash run.sh"
4. Navigate to `http://socialdrizzle.com/sign-in` and sign in

# Developers

To freeze pip requirements

`pip freeze > requirements.txt` from within the root of the hardwaresetup repo while in the appropriate virtualenv

