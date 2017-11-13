# WEMHydrationKit
Hydration Kit for Citrix Workspace Environment Management

Initial Release 07.10.17

Update Release 13.11.17 - The Hal Lange Set, Foxit Reader, Windows Snipping Tool, Office 365 Online Apps, Azure Services and Management URL's

Master Config List - All Actions

### Applications
		#Microsoft Office 2010
			Word 2010
			Excel 2010
			PowerPoint 2010
			Outlook 2010
			OneNote 2010
			Visio 2010
			Project 2010
		#Microsoft Office 2013
			Word 2013
			Excel 2013
			PowerPoint 2013
			Outlook 2013
			OneNote 2013
			Project 2013
			Visio 2013
		#Microsoft Office 2016
			Word 2016
			Excel 2016
			PowerPoint 2016
			Outlook 2016
			Access 2016
			OneNote 2016
			Visio 2016
			Project 2016
			Skype 2016
		#Libre Office
			LibreOffice Calc
			LibreOffice Writer
			LibreOffice Impress
		#OpenOffice
			OpenOffice Calc
			OpenOffice Writer
			OpenOffice Impress			
		#Browsers
			Chrome
			Internet Explorer
			Firefox
		#Media Players
			VLC
			Quicktime
			Windows Media Player
		#Utilities
			Notepad++
			7zip
			filezilla
			winscp
			KeePass
			Foxit Reader (Courtesy of Hal Lange)
			Windows Snipping Tool
		#Graphics Programs
			Gimp
			Paint.Net
			MS Paint
		#Adobe
			Adobe Reader DC
		#Citrix
			WEM RSOP Agent
			WEM Agent Log Parser
			WEM App Management
			WEM Printer Management
			WEM UI Agent
		#Windows Actions
			LogOff
			Explorer
			Calculator
			cmd
			Server Manager
			RDP
		#Office 365 Apps
			Microsoft Outlook Online
			Microsoft Word Online
			Microsoft Excel Online
			Microsoft PowerPoint Online
			Microsoft OneDrive Online (Need custom edit)
			Microsoft Teams
			Microsoft Yammer
			Microsoft Flow
			Microsoft Delve
			Microsoft Forms
			Microsoft PowerBI
			Microsoft Stream
			Microsoft Sway
			Microsoft MyApps
		#Azure Services and Management URL's
			Azure Password Reset
			Azure Security Verification (MFA)
			Microsoft Company Portal
			Microsoft Office 365 Service Health
			Azure Management Portal
			Microsoft 365 Admin portal
			Microsoft Accounts Portal

### Configuration Tweaks
		#Internet Explorer Easy List
			Registry Keys
			File Actions (Requires path customisation)
			
		#Windows Explorer / Environment Control
			Taskbar Icon Size - small
				Registry Key
			Desktop Icon Size - small
				Registry Key
			Hide Drives in My Computer (A,B,C,D,E)
				Registry Key
			WinX - To deal with UPM killing right click options on start menu in some environments
				File System Operation
			Microsoft Vault Store
				File System Operation
			Microsoft Inet Cache Creation - to deal with certain environments with UPM and office/javavm memory errors
				File System Operation
				
		# Logon Performance
			Serialize / Startup Delay - Assist with speeding up Logons
				Registry Key 
		
		#The Hal Lange Set
			Control Panel - Icon View - Show Icons in Control Panel
				Registry Key
			Control Panel - Startup View - Show Icons as Startup in Control Panel
				Registry Key
			Start Menu - Hide Run - Proper way to hide Run from Start Menu
				Registry Key
			Start Menu - Hide Default Programs - Proper way to hide Default Programs from Start Menu
				Registry Key
			Start Menu - Hide Personalized Folders - Proper way to hide User Folder from Start Menu
				Registry Key
			Start Menu - Disable Search of Files - This will stop the Start Menu from searching files
				Registry Key
			Start Menu - Disable Pictures Folder - This will disable the Pictures folder link on the Start Menu
				Registry Key
			Start Menu - Disable Music Folder - This will disable Music folder from the Start Menu
				Registry Key
			Start Menu - Disable My Computer - This will disable My Computer from showing in Start Menu
				Registry Key
			Start Menu - Disable Devices and Printers - This will remove Devices and Printers from Start Menu
				Registry Key
			Start Menu - Disable Admin Tools - This will disable Administrative Tools on the Start Menu
				Registry Key
			Start Menu - Disable Videos Folder - This will disable the Videos folder link on the Start Menu
				Registry Key
			Start Menu - Disable Downloads Folder - This will disable the Downloads folder link on the Start Menu
				Registry Key
			Start Menu - Disable Recent Items - This will disable the Recent Items menu from the Start Menu
				Registry Key
			Windows Explorer - Disable Registry - Disable the Use of the Registry Tools UI
				Registry Key
			Windows Explorer - Disable CMD - Disable the Windows CMD Prompt
				Registry Key


