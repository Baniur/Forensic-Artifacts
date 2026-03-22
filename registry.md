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

<ul>
  <li>Recently accessed files/folders:</li>
  <ol><code>HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\RecentDocs</code></ol>
</ul>

<ul>
  <li>Network Shares and Mapped Drives</li>
  <ol><code>HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\MountPoints2\</code></ol>
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
<li>Timezone:</li>
<ol><code>HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\TimeZoneInformation\TimeZoneKeyName</code></ol>
</ul>

<ul>
<li>ShimCache:</li>
<ol><code>HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\AppCompatCache</code></ol>
</ul>

__

#### Network settings

<ul>
<li>Network Interfaces:</li>
<ol><code>HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\Tcpip\Parameters\Interfaces</code></ol>
<ol><code>HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\Tcpip6\Parameters\Interfaces</code></ol>
</ul>

<ul>
<li>MAC address for network interface:</li>
<ol><code>HKEY_LOCAL_MACHINE\SYSTEM\ControlSet001\Control\NetworkSetup2\Interfaces\{INTERFACE_GUID}\Kernel</code></ol>
</ul>

<ul>
<li>Network interfaces installed on the system:</li>
<ol><code>HKEY_LOCAL_MACHINE\SYSTEM\ControlSet001\Control\Class\{4d36e972-e325-11ce-bfc1-08002be10318}</code></ol>
</ul>

<ul>
<li>Connected networks:</li>
<ol><code>HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\NetworkList\Profiles\</code></ol>
<ol><code>HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\NetworkList\Profiles\Signatures\*\</code></ol>
</ul>

<ul>
<li>Proxy server settings:</li>
<ol><code>HKEY_LOCAL_MACHINE\Software\Policies\Microsoft\Windows\CurrentVersion\Internet Settings\</code></ol>
<ol><code>HKEY_LOCAL_MACHINE\Software\Microsoft\Windows\CurrentVersion\Internet Settings\</code></ol>
<ol><code>HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Internet Settings\</code></ol>
</ul>

__

#### Firewall settings

<ul>
<li>Domain network profiles:</li>
<ol><code>HKEY_LOCAL_MACHINE\SYSTEM\ControlSet001\Services\SharedAccess\Parameters\FirewallPolicy\DomainProfile</code></ol>
</ul>

<ul>
<li>Private network profiles:</li>
<ol><code>HKEY_LOCAL_MACHINE\SYSTEM\ControlSet001\Services\SharedAccess\Parameters\FirewallPolicy\StandardProfile</code></ol>
</ul>

<ul>
<li>Public network profiles:</li>
<ol><code>HKEY_LOCAL_MACHINE\SYSTEM\ControlSet001\Services\SharedAccess\Parameters\FirewallPolicy\PublicProfile</code></ol>
</ul>

<ul>
<li>Windows firewall rules:</li>
<ol><code>HKEY_LOCAL_MACHINE\SYSTEM\ControlSet001\Services\SharedAccess\Parameters\FirewallPolicy\FirewallRules</code></ol>
</ul>

<ul>
<li>Firewall rules for HyperV:</li>
<ol><code>HKEY_LOCAL_MACHINE\SYSTEM\ControlSet001\Services\SharedAccess\Parameters\FirewallPolicy\HyperVRules</code></ol>
</ul>

__

