<h1>Instalation:</h1> <br/><br/>

<h2>For MultiMC users (http://multimc.org/)</h2> <br/>
1. Create new instance in MultiMC<br/>
2. Select Import Modpack<br/>
3. Paste URL: https://github.com/vinterdo/Crashality/releases/download/v1.1/Crashality.zip<br/>
4. Click OK and wait for MultiMC to download and install modpack<br/>
5. ...<br/>
6. Profit<br/>
![Example instance](https://www.dropbox.com/s/vav8qaoa1c60hsi/multimcModpackInstall.PNG?raw=1 "Example instance")
</br>
<h2>For others (better download this MultiMc...)</h2> <br/>
1. Download Clear Vanilla 1.7.10 minecraft
2. Install Forge 10.13.4.1448 (windows installer: <a href=http://adfoc.us/serve/sitelinks/?id=271228&url=http://files.minecraftforge.net/maven/net/minecraftforge/forge/1.7.10-10.13.4.1448-1.7.10/forge-1.7.10-10.13.4.1448-1.7.10-installer-win.exe> here </a><br/>
3. Download file https://github.com/vinterdo/Crashality/releases/download/v1.1/Crashality.zip<br/>
4. Extract it <br/>
5. Paste all content from minecraft folder to your Minecraft directory (your mod files should be in .minecraft/mods/ directory) <br/>
6. If you done everything properly, modpack should work. If not, install MultiMC </br>
<br/>
<br/>
<h1> Java version and commands</h1><br/><br/>
It's required to use 64bit version of Java<br/>
It's recomended to use Java 8, Java 7 will also work<br/>
<h2> Minimal memory </h2><br/>
2048M of ram: <br/>
-Xmx2048m <br/>
<h2> Recomended memory </h2><br/>
3072M of ram: <br/>
-Xmx3072m <br/>
<h2> PermGen </h2><br/>
(only if Java 7 or lower) <br/>
-XX:MaxPermSize=256m <br/>
<h2> Other Commands</h2><br/>
Increased performance of Garbage Collector - it may remove freeze-lags <br/>
-XX:+UseConcMarkSweepGC -XX:+UseParNewGC -XX:+CMSIncrementalPacing -XX:ParallelGCThreads=2 -XX:+AggressiveOpts </br>

![Example settings](https://www.dropbox.com/s/rm56v2benjqlyqb/multimcModpackInstall2.PNG?raw=1 "Example settings")
