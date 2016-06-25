# Komodo-TortoiseSVN
TortoiseSVN snippets collection for Komodo edit / ide.   

## Usage

The default path of TortoiseSVN is set to `C:\Program Files\TortoiseSVN\`.
If you have TortoiseSVN in another directory, right click on snippet and change it with correct path **WITH** a trailing slash.
You also need to remember to escape the backslash (`\\` instead of `\`).

The menu contains:

<table><thead>
<tr>
<th>Menu</th>
<th>Command</th>
</tr>
</thead><tbody>
<tr>
<td>Clean up this project</td>
<td><code>svn cleanup</code></td>
</tr>
<tr>
<td>Commit all files currently open</td>
<td><code>svn commit -m "Message" file1 file2 ...</code></td>
</tr>
<tr>
<td>Commit current file</td>
<td><code>svn commit -m "Message" currentFile</code></td>
</tr>
<tr>
<td>Commit current file's directory</td>
<td><code>TortoiseProc /command:commit /path:"currentFilePath"</code></td>
</tr>
<tr>
<td>Commit current project</td>
<td><code>TortoiseProc /command:commit /path:"currentProjectPath"</code></td>
</tr>
<tr>
<td>Show diff with previous version</td>
<td><code>svn di currentFile</code></td>
</tr>
<tr>
<td>Update current project</td>
<td><code>svn update currentProjectPath</code></td>
</tr>
</tbody></table>

	
### Search for Snippet
By hitting <kbd>ctrl</kbd> + <kbd>shift</kbd> + <kbd>k</kbd> a search window will popup, when you type `TortoiseSVN` all the Tortoise snippets will be shown.
This is a fast way to search inside your snippets.

### Setting up key bindings
You can add a key binding to a snippet by right clicking on a snippet, go to properties and you will see here a tab key binding,
here you can set your key binding for the snippet.
