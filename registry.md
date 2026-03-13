<h1 id="Applications">Registry</h1>

<ul>
<li><a href="#HKCU">HKEY_CURRENT_USER (HKCU) - NTUSER.DAT</a></li>
<li><a href="#HKLM_SAM">SAM (HKEY_LOCAL_MACHINE\SAM)</a></li>
<li><a href="#HKLM_SOFTWARE">SOFTWARE (HKEY_LOCAL_MACHINE\SOFTWARE)</a></li>
<li><a href="#HKLM_SYSTEM">SYSTEM (HKEY_LOCAL_MACHINE\SYSTEM)</a></li>
</ul>

<h2 id="HKCU">HKEY_CURRENT_USER (HKCU) - NTUSER.DAT</h2>

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

<h2 id="HKLM_SAM">SAM (HKEY_LOCAL_MACHINE\SAM)</h2>

<h2 id="HKLM_SOFTWARE">SOFTWARE (HKEY_LOCAL_MACHINE\SOFTWARE)</h2>

<ul>
<li>Possible Persistence:</li>
  <ol><code>HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Run</code></ol>
  <ol><code>HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\RunOnce</code></ol>
  <ol><code>HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\RunServicesOnce</code></ol>
  <ol><code>HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\RunServices</code></ol>
</ul>

<h2 id="HKLM_SYSTEM">SYSTEM (HKEY_LOCAL_MACHINE\SYSTEM)</h2>

<ul>
<li>ComputerName:</li>
<ol><code>HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\ComputerName\ComputerName</code></ol>
</ul>

<ul>
<li>Network Interfaces:</li>
<ol><code>HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\Tcpip\Parameters\Interfaces</code></ol>
<ol><code>HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\Tcpip6\Parameters\Interfaces</code></ol>
</ul>

<ul>
<li>ShimCache:</li>
<ol><code>HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\AppCompatCache</code></ol>
</ul>

<ul>
<li>Timezone:</li>
<ol><code>HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\TimeZoneInformation\TimeZoneKeyName</code></ol>
</ul>
