<h2 id="HKCU">HKEY_CURRENT_USER (HKCU) - NTUSER.DAT</h2>

<ul>
<li>AppSwitched (tracks every time a user switches focus between applications, specifically through Taskbar clicks):</li>
<ol><code>HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\AppSwitch</code></ol>
</ul>

<ul>
<li>Possible Persistence:</li>
  <ol><code>HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Run</code></ol>
  <ol><code>HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\RunOnce</code></ol>
  <ol><code>HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\RunServicesOnce</code></ol>
  <ol><code>HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\RunServices</code></ol>
</ul>

<ul>
  <li>History of commands entered into the Run dialog box</li>
  <ol><code>HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\RunMRU</code></ol>
</ul>

<ul>
  <li>History of searches performed using the Windows File Explorer search bar</li>
  <ol><code>HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\WordWheelQuery</code></ol>
</ul>

<ul>
  <li>History of paths typed into the File Explorer address bar</li>
  <ol><code>HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\TypedPaths</code></ol>
</ul>

<ul>
  <li>UserAssist (execution for .lnk files or PE files that have a GUI component):</li>
  <ol><code>HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\UserAssist</code></ol>
</ul>

<ul>
  <li>Remote Desktop Connections:</li>
  <ol><code>HKEY_CURRENT_USER\Software\Microsoft\Terminal Server Client\Servers</code></ol>
</ul>

<ul>
  <li>Recently accessed files/folders:</li>
  <ol><code>HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\RecentDocs</code></ol>
</ul>

<ul>
  <li>Network Shares and Mapped Drives</li>
  <ol><code>HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\MountPoints2\</code></ol>
</ul>
