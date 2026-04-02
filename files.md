<h1 id="files">Files</h1>

- [Master File Table (MFT)](#mft)
- [Update Sequence Number Journal (USN) Journal](#usnjrnl)
- [Windows-gather](#windows-gather)

<h2 id="mft">Master File Table (MFT)</h2>

<ul>
<li><code>%systemdrive%\$MFT</code></li>
</ul>

<h2 id="usnjrnl">Update Sequence Number Journal (USN) Journal</h2>

<ul>
<li><code>%systemdrive%\$Extend\$UsnJrnl</code></li>
</ul>

<h2 id="windows-gather">Windows-gather</h2>

System database file used by Microsoft Windows for its search indexing feature.

<ul>
<li><code>%ProgramData%\Microsoft\Search\Data\Applications\Windows</code></li>
  <ol><code>windows-gather.db</code> (SQLite database)</ol>
  <ol><code>windows-gather.db-shm</code></ol>
  <ol><code>windows-gather.db-wal</code></ol>
</ul>
