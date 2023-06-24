[![Image Description](https://imgur.com/dGFm5SP.png)](https://github.com/narstybits/MacOS-DuckyScripts)
<div align="left">
  



</div>





<h1 
 align="center"><u>This repository is EXCLUSIVE to MacOs BADUSB Scripts <img src="https://media.giphy.com/media/3oKIPic2BnoVZkRla8/giphy.gif" alt="Giphy Image" style="margin-left: 10px; width: 50px; height: auto;" align="center">
 
   <img alt="Coding" width="1473" height="18" src="https://media.giphy.com/media/9JxkPTP3alOykb8PmQ/giphy.gif">
</div>



  <div>
 <img src="https://media.giphy.com/media/tR8stUDuzhgAHrr2i8/giphy-downsized-large.gif" alt="Giphy Image" style="width: 300px; height: auto;">
</div>




  <h1 align="center"><u> 🔹They are Plug & Play🔹 </u></h1>
</div>
 

<h2 align="center"><u>Big shoutout and huge thanks to <a href="https://github.com/grugnoymeme">47LeCoste</a> <a href="https://github.com/ClaraCrazy">ClaraCrazy</a> <a href="https://github.com/0iphor13">0iphor13</a> <a href="https://github.com/hak5">Hak5</a> <a href="https://github.com/I-Am-Jakoby">I-Am-Jakoby</a> and <a href="https://github.com/UberGuidoZ">UberGuidoZ</a></u></h2>

<h2 align="center">Check Out the Xremote (Cross Remote) by <a href="https://github.com/leedave">leedave</a> to Chain Infared and SubGHz Together! 📱 

  



  <p>
    <a href="https://github.com/leedave/Leeds-Flipper-Zero-Fap-Files/tree/main/Xtreme" style="font-size: 18px;">XRemote<a>(BETA)<h2>

  <p align="center">
  <a href="https://github.com/narstybits/MacOS-DuckyScripts">
    <img src="https://img.shields.io/badge/-MacOs%20Flipper%20Zero%20Collection-brightgreen">
  </a>
<a href="https://github.com/narstybits/MacOS-DuckyScripts/blob/main/RECON/Infinite%20Reverse%20Shell.txt">
    <img src="https://img.shields.io/badge/-NEWEST%20FLIPPER%20Zero%20SCRIPT-blue">
  </a>
    </div>
      
<h2 align="center">    If you're a visual learner like me, check out this detailed tutorial: <a href="https://github.com/wrenchathome/flipperfiles/blob/main/_Guides/How2Flipper.pdf" style="text-decoration: none;">How 2 Flipper Guide



<p align="center">Thanks to <u><a href="https://github.com/wrenchathome">wrenchathome</a></u></h2>
<ol>

 <h1 
  align="center"><p>Step by Step Directions to get you up and running will be posted Below! <p>
  <div align="center">
  <img alt="Coding" width="450" height="15" src="https://media.giphy.com/media/9JxkPTP3alOykb8PmQ/giphy.gif">
</div>
 
<h3  
  <div style="border: 2px solid #000000; padding: 10px;">
    <p style="font-size: 32px; margin: 0;">
     <p>
  <span style="font-size: 0;"></span>🔹 First, always read the Remarks. You will see "REM," which is used to explain the purpose of each line or provide instructions to the user. It's very important to always READ the REMs!
</p>
<p>
  <span style="font-size: 0;"></span>🔹 Here are a few strings you will normally see in my scripts as well as their function/purpose:
</p>

<h4>
  The VendorID and ProductID combination helps the operating system identify the specific device and load the appropriate drivers or configurations.
</p>
<pre>
<code>
'ID 05ac:021e Apple:Keyboard'
</code>
</pre>

<p>
 This code enables the `ignorespace` option for the command history, preventing commands with a leading space from being stored in the shell history. Additionally, it removes the specific command from the history, ensuring minimal traces are left behind. This helps maintain discretion and privacy.
 Big shoutout to <a href="https://github.com/FalsePhilosopher">FalsePhilosopher</a> for helping me create this string!
</p>
<pre>
<code>
'echo -e "export HISTCONTROL=ignorespace\nunset HISTFILE" >> ~/.bashrc && source ~/.bashrc && exec bash
history -d $(history | tail -n 2 | head -n 1 | awk '{ print $1 }')'
</code>
</pre>

 <h1 
  align="center"
<span style="font-size: 0;"></span>🔹 Step by Step Directions <p>
        
  
</div><h3
        <span style="font-size: 0;"></span>1. To upload the .txt files to your Flipper, you will need to Download(Easiest method) or copy and paste the raw code into the MacOs application "TextEdit" or whichever program you prefer (TextEdit is also easy).</p>
   <div align="left">
  <img alt="Coding" width="1473" height="5" src="https://media.giphy.com/media/RH27Uw1IFGfIs/giphy.gif">
</div>
    <p style="font-size: 12px; margin: 0;">2. (If you Downloaded the .txt you can skip these next two steps) Once you've copied and pasted the code into your preferred program, you will need to export or save the file to your desktop as a .txt file!</p>
   <div align="left">
  <img alt="Coding" width="1473" height="5" src="https://media.giphy.com/media/RH27Uw1IFGfIs/giphy.gif">
</div>
    <p style="font-size: 12px; margin: 0;">3. You can type .txt after the file name, and it will prompt you to save the file as a .txt.</p>
    <div align="left">
  <img alt="Coding" width="1473" height="5" src="https://media.giphy.com/media/RH27Uw1IFGfIs/giphy.gif">
</div>
    <p style="font-size: 12px; margin: 0;">4. Now, you can plug the flipper in and open up the File Manager, navigate to the SD card, and open up the BADUSB file within the SD card.</p>
    <div align="left">
  <img alt="Coding" width="1473" height="5" src="https://media.giphy.com/media/RH27Uw1IFGfIs/giphy.gif">
</div>
    <p style="font-size: 12px; margin: 0;">5. This is where you can drag and drop your .txt files, and once you are done, close out of the Flipper desktop app.</p>
    <div align="left">
  <img alt="Coding" width="1473" height="5" src="https://media.giphy.com/media/RH27Uw1IFGfIs/giphy.gif">
</div>
    <p style="font-size: 12px; margin: 0;">6. You are now ready to deploy your BADUSB DuckyScripts and take over the World! ENJOY :)</p>
  </div>
</li>
 <div align="left">
  <img alt="Coding" width="1473" height="5" src="https://media.giphy.com/media/RH27Uw1IFGfIs/giphy.gif">
</div>     
<div style="display: flex; flex-direction: column; align-items: center; justify-content: center; height: 100vh;">
  <h1 
   align="center">Support Narsty!
   <div align="center">
  <img alt="Coding" width="283" height="15" src="https://media.giphy.com/media/9JxkPTP3alOykb8PmQ/giphy.gif">
</div>
  <p align="center">
  <a href="https://www.blockonomics.co/pay-url/5106312c7ce343bb">
    <img src="https://www.opennode.com/blog/wp-content/uploads/2020/04/donate-button-small-1.png" alt="Donate with Bitcoin" width="290">
  </a>
</p>





      





  </li>
</ol>
<p align="center">
  <img src="https://www.nist.gov/sites/default/files/2019-12/cyberattack-blogfeaturedimage-763.png" alt="Cyberattack Image">
</p>
<h2 align="center"><u><a href="https://github.com/narstybits/MacOS-DuckyScripts/blob/main/Warning%20%20Readme.md">!!!! EXERCISE CAUTION !!!!</a></u></h3>
<h2 align="center"><u>When executing code, double-check to ensure that you're targeting the correct directory/system and that the consequences are understood.</u></h2>
<h2 align="center">Deleting files and folders can have significant consequences!</h2>
<h1 align="center">
<h1 align="center"><u><a href="https://github.com/narstybits/MacOS-DuckyScripts/blob/main/Warning%20%20Readme.md">!!! IMPORTANT DISCLAIMER !!!</strong><br>
   <h3 Please exercise caution and responsibility when using the scripts and tools in the "executions," "obscurity," "pranks," "GOODUSB," and "Recon" folders. These scripts are intended for educational and ethical purposes such as penetration testing, security testing, and network testing. However, it is important to note that unauthorized or malicious use of these tools can be illegal and may lead to severe consequences.
</p>
<p align="center">
    It is your responsibility to ensure that you have appropriate authorization, permissions, and legal rights to perform any security testing activities on computer systems or networks. Always respect the law, adhere to ethical guidelines, and obtain proper consent before conducting any tests or assessments.
</p>
<p align="center">
    Remember, it is crucial to prioritize legal and ethical practices, protect user privacy, and use these tools responsibly to improve security and protect against real-world threats.
</p>

