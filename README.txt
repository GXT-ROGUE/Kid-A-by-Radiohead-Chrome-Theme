To install a custom or unofficial Chrome extension (one not from the Web Store), you must use Developer Mode. This process is often called "loading an unpacked extension". 

1. Prepare Your Extension Files
	Download or Create: Ensure you have the extension’s folder. If it is a .zip file, you must unzip/extract it first.
	Verify Contents: The folder must contain a file named manifest.json. This is the core file Chrome uses to recognize the extension.
	Permanent Location: Move the folder to a permanent location (like a "Documents" subfolder). If you delete or move the folder later, the extension will stop working. 
2. Enable Developer Mode 
	Open Google Chrome.
	In the address bar, type chrome://extensions/ and press Enter.
	In the top-right corner, find the Developer mode toggle and switch it On. 
3. Load the Extension
	Click the Load unpacked button that appears in the top-left.
	Navigate to and select the folder containing your extension files (the one with manifest.json).
	Click Select Folder (Windows) or Open (Mac).
	The extension will now appear in your list and is ready to use. 
4. Manage and Troubleshoot
	Pin for Access: Click the Extensions (puzzle piece) icon next to your profile picture and click the Pin icon to keep the custom extension visible.
	Errors: If the extension doesn't load, check for an "Errors" button on the extension's card in the manager. This usually indicates a syntax error in the manifest.json file.
	Updates: If you change the code in your custom extension folder, you must click the Reload (circular arrow) icon on the extension's card to apply the changes. 
