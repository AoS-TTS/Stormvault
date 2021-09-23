<div align="center">
  <img src="https://raw.githubusercontent.com/AoS-TTS/Stormvault/main/stormvault_logo.png">
  <hr style="height:1px;border:center;;" />
</div>
<div align="center">

Welcome to AoS Stormvault, a curated collection of Age of Sigmar Models for Tabletop Simulator.<br/><br/>
    function setModifiedDate() {
      if (document.getElementById('last-modified')) {
        fetch("https://api.github.com/repos/{{ site.github.owner_name }}/{{ site.github.repository_name }}/commits?path={{ page.path }}")
          .then((response) => {
            return response.json();
          })
          .then((commits) => {
            var modified = commits[0]['commit']['committer']['date'].slice(0,10);
            if(modified != "{{ page.date | date: "%Y-%m-%d" }}") {
              document.getElementById('last-modified').textContent = "Last Modified: " + modified;
            }
          });
      }
    }
</div>
<hr style="height:1px;border:center;;" />

KNOWN BUG - Warscrolls sometimes do not scroll ingame. You can get around this by clicking the top-left button on the scroll to pop out the window.

# Installation Instructions:

**Video Guide**
https://youtu.be/eSh2c2qBSqE

Please note that there is currently no automatic updating version of Stormvault. If we release a new update, you need to download the zip file again and extract and replace the files on your computer. Alternatively, if you are familiar with Github, you can clone the respository and set up automatic fetching through the Github Desktop application.

**Manual Installation (Windows OS)**
1. Download the Stormvault Zip file.
2. Locate your Saves folder under /Your Computer/My Documents/My Games/Tabletop Simulator
3. Drag/Extract the Stormvault folder from the downloaded Zip file and place into your Saves folder in your Tabletop Simulator directory mentioned above. If updating, overwrite when prompted.
4. Open Tabletop Simulator and make a room. The mod folders should be found in Save/Load.

**Manual Installation (Mac OS)**

1. Download the Stormvault Zip file.
2. Locate your **Library\Tabletop Simulator
3. Drag/Extract the Stormvault folder from the downloaded Zip file and place into your Saves folder in your Tabletop Simulator directory mentioned above. If updating, overwrite when prompted.
4. Open Tabletop Simulator and make a room. The mod folders should be found in Save/Load.

**Manual Installation (Linux)**
1. Download the Stormvault Zip file.
2. Locate your Saves file under /home/<username>/.var/app/com.valvesoftware.Steam/.local/share/Tabletop\ Simulator/Saves/
3. Drag/Extract the Stormvault folder from the downloaded Zip file and place into your Saves folder in your Tabletop Simulator directory mentioned above. If updating, overwrite when prompted.
4. Open Tabletop Simulator and make a room. The mod folders should be found in Save/Load.

  
# Discord Channel:  <br/> 
If you have any questions or wish to report errors, please submit them here.  

<a href="https://discord.gg/fCZyysjK5k">https://discord.gg/fCZyysjK5k</a>
  

# Modder Credits:<br/>
**Stormvault Admins**<br/>
  Quoeiza<br/> 
  TheFraggDog<br/> 
  Mothman_Zack<br/> 
  
**Stormvault Contributors**<br/>
  Quoeiza<br/> 
  TheFraggDog<br/> 
  Nylon<br/> 
  Inquisitorz<br/> 
  Flition<br/> 
  Kupp<br/> 
  
**Photogrammetrists and 3D Modellers**<br/>
  Quoeiza<br/> 
  TheFraggDog<br/> 
  Nylon<br/> 
  Zerg<br/> 
  Ringil<br/> 
  eternal3blade<br/> 
  DarkTrinity<br/> 
  PhilipRikoZen<br/>
  TheBestEGirl<br/>
  DaSNation<br/>

If you have contributed resources to the project and your name is not listed above, please send us a message on Discord.

Thankyou to everyone who made this mod project possible. It has been a long journey, and we're very proud to be a part of it.
