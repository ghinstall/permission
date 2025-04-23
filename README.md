<div align="center">
<img width="280" alt="logo" src="https://github.com/user-attachments/assets/2f9504e3-5801-42fe-ac77-ecf5ce243468" />  
<h3>Permission file for ghinstall</h3>
<hr>

<p>ghinstall is a GitHub-based CLI tool that installs repositories via a public permission system.<br>
<strong>Documentation at: <a href="https://ghinstall.readthedocs.io/en/latest/">ghinstall.readthedocs.io/en/latest/</a></strong></p>
<hr>

<p>ghinstall checks for install permission from the <i>permission.txt</i> file via GitHub Pages.</p>
<hr>

<p>The <i>permission.txt</i> file may contain:</p>
<table>
  <tr>
    <th>Content</th>
    <th>Action</th>
  </tr>
  <tr>
    <td><code>Permission [GRANTED] - ok to install</code></td>
    <td>Gives all permissions</td>
  </tr>
  <tr>
    <td><code>Permission [DENIED] - do not install</code></td>
    <td>Disables the tool</td>
  </tr>
  <tr>
    <td><code>Permission [DENIED] - under maintanence</code></td>
    <td>Sends out "under construction"</td>
  </tr>
</table>
<hr>

<footer>
<p><small>Built with ♡ by Andrew Baki. Copyright (C) 2025.<br>
Licensed under GNU Generic Public License. All rights reserved.</small></p>
</footer>
</div>
