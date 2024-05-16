<h1 id="Applications">Applications</h1>

<ul>
<li><a href="#anydesk">AnyDesk</a></li>
<li>Google Chrome</li>
<li><a href="#microsoft-edge-chromium">Microsoft Edge (Chromium)</a></li>
<li>Mozilla Firefox</li>
<li><a href="#notepad-plus-plus">Notepad++</a></li>
<li><a href="#remote-desktop">Remote Desktop</a></li>
<li><a href="#stickynotes">Sticky Notes</a></li>
<li><a href="#sublime-text">Sublime Text</a></li>
<li><a href="#teamviewer">TeamViewer</a></li>
<li><a href="#microsoft-windows-10-11-notifications">Microsoft Windows 10/11 Notifications</a></li>
<li><a href="#microsoft-windows-defender">Microsoft (Windows) Defender</a></li>
<li>Microsoft Windows 11 Notepad</li>
</ul>

<h2 id="anydesk">AnyDesk</h2>

<ul>
<li>%USERPROFILE%\AppData\Roaming\AnyDesk\ad.trace</li>
</ul>

How to open: <strong>text editor</strong>

<h2 id="microsoft-edge-chromium">Microsoft Edge (Chromium)</h2>

<ul>
<li>%USERPROFILE%\MicrosoftEdgeBackups\backups\MicrosoftEdgeBackup<strong><i>YYYYMMDD</i></strong>_dbh<strong><i>hhmmss</i></strong>\DatastoreBackup\spartan.edb</li>
</ul>

How to open: <strong>ESEDatabaseView (Nirsoft)</strong>

<h2 id="notepad-plus-plus">Notepad++</h2>

<ul>
<li>%USERPROFILE%\AppData\Roaming\Notepad++\session.xml</li>
<li>%USERPROFILE%\AppData\Roaming\Notepad++\backup</li>
</ul>

How to open: <strong>text editor</strong>

<h2 id="remote-desktop">Remote Desktop</h2>

<ul>
<li>%USERPROFILE%\AppData\Local\Microsoft\Terminal Server Client\Cache\bcache*.bmc</li>
<li>%USERPROFILE%\AppData\Local\Microsoft\Terminal Server Client\Cache\cache????.bin</li>
</ul>

How to open: <strong>bmc-tools</strong> and <strong>RdpCacheStitcher</strong>

<h2 id="stickynotes">Sticky Notes</h2>

<ul>
<li>%USERPROFILE%\AppData\Local\Packages\Microsoft.MicrosoftStickyNotes_8wekyb3d8bbwe\</li>
</ul>

<h2 id="sublime-text">Sublime Text</h2>

<ul>
<li>%USERPROFILE%\AppData\Roaming\Sublime Text 3\Local\Session.sublime_session</li>
</ul>

How to open: <strong>text editor</strong>

<h2 id="teamviewer">TeamViewer</h2>

<ul>
<li>%USERPROFILE%\AppData\Roaming\TeamViewer\Connections.txt</li>
<li>%systemdrive%\Program Files\TeamViewer\Connections_incoming.txt</li>
<li>%systemdrive%\Program Files\TeamViewer\TeamViewerXX_Logfile.log (XX - version)</li>
<li>%systemdrive%\Program Files (x86)\TeamViewer\Connections_incoming.txt</li>
<li>%systemdrive%\Program Files (x86)\TeamViewer\TeamViewerXX_Logfile.log (XX - version)</li>
</ul>

How to open: <strong>text editor</strong>

<h2 id="microsoft-windows-10-11-notifications">Microsoft Windows 10/11 Notifications</h2>

<ul>
<li>%USERPROFILE%\AppData\Local\Microsoft\Windows\Notifications\wpndatabase.db</li>
</ul>

How to open: <strong>DB Browser for SQLite</strong>, <strong>SQLiteStudio</strong>

<h2 id="microsoft-windows-defender">Microsoft (Windows) Defender</h2>

If the attacker was able to clear *Microsoft Windows Defender* <strong>event logs</strong> then files listed below could still help you:

<ul>
<li>%systemdrive%\ProgramData\Microsoft\Windows Defender\Support\MPDetection-*.log</li>
<li>%systemdrive%\ProgramData\Microsoft\Windows Defender\Support\MPDeviceControl-*.log</li>
<li>%systemdrive%\ProgramData\Microsoft\Windows Defender\Support\MLog-*.log</li>
<li>%systemdrive%\ProgramData\Microsoft\Windows Defender\Support\MpScanSkip-*.log</li>
</ul>

How to open: <strong>text editor</strong>
