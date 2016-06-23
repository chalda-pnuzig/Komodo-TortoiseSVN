# Komodo-TortoiseSVN
TortoiseSVN snippets collection for Komodo edit / ide.   

## Usage

The default path of TortoiseSVN is set to `C:\Program Files\TortoiseSVN\`.
If you have TortoiseSVN in another directory, right click on snippet and change it with correct path **WITH** a trailing slash.
You also need to remember to escape the backslash (`\\` instead of `\`).

The menu contains:

	Menu  | Command 
	----- | ------- 
	Clean up this project | `svn cleanup`
	Commit all files currently open | `svn commit -m "Message" file1 file2 ...` 
	Commit current file |  `svn commit -m "Message" currentFile`  
	Commit current file's directory | `TortoiseProc /command:commit /path:"currentFilePath"` 
	Commit current project | `TortoiseProc /command:commit /path:"currentProjectPath"` 
	Show diff with previous version | `svn di currentFile` 
	Update current project |  `svn update currentProjectPath`

	
### Search for Snippet
By hitting <kbd>ctrl</kbd> + <kbd>shift</kbd> + <kbd>k</kbd> a search window will popup, when you type `TortoiseSVN` all the Tortoise snippets will be shown.
This is a fast way to search inside your snippets.

### Setting up key bindings
You can add a key binding to a snippet by right clicking on a snippet, go to properties and you will see here a tab key binding,
here you can set your key binding for the snippet.
