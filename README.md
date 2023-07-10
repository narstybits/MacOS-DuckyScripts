<!DOCTYPE html>
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

<div align="center">

# 🔹 They are Plug & Play 🔹

</div>

## Acknowledgements

A big shoutout and huge thanks to these amazing contributors:
- [47LeCoste](https://github.com/grugnoymeme)
- [ClaraCrazy](https://github.com/ClaraCrazy)
- [0iphor13](https://github.com/0iphor13)
- [Hak5](https://github.com/hak5)
- [I-Am-Jakoby](https://github.com/I-Am-Jakoby)
- [UberGuidoZ](https://github.com/UberGuidoZ)

## Xremote (Cross Remote)

Check out the Xremote project by [leedave](https://github.com/leedave) to chain Infrared and SubGHz together! 📱

- [XRemote (BETA)](https://github.com/leedave/Leeds-Flipper-Zero-Fap-Files/tree/main/Xtreme)

## MacOs Flipper Zero Collection

- [![MacOs Flipper Zero Collection](https://img.shields.io/badge/-MacOs%20Flipper%20Zero%20Collection-brightgreen)](https://github.com/narstybits/MacOS-DuckyScripts)
- [![NEWEST FLIPPER Zero SCRIPT](https://img.shields.io/badge/-NEWEST%20FLIPPER%20Zero%20SCRIPT-blue)](https://github.com/narstybits/MacOS-DuckyScripts/blob/main/Goodusb/Git%20Repository%20Updater.txt)

## How 2 Flipper Guide

If you're a visual learner like me, check out this detailed tutorial by [wrenchathome](https://github.com/wrenchathome):

- [How 2 Flipper Guide](https://github.com/wrenchathome/flipperfiles/blob/main/_Guides/How2Flipper.pdf)

<div align="center">
  <h1>🔹 Step by Step Directions to Get You Up and Running 🔹</h1>
  <img alt="Coding" width="450" height="15" src="https://media.giphy.com/media/9JxkPTP3alOykb8PmQ/giphy.gif">
</div>

<div style="border: 2px solid #000000; padding: 10px;">
  <h3 style="font-size: 32px; margin: 0;">🔹 First, Always Read the Remarks</h3>
  <p>When working with the scripts, make sure to carefully read the REM (remark) lines. REMs explain the purpose of each line or provide instructions to the user. It's crucial to always read and understand the REMs!</p>
  
  <h4>The VendorID and ProductID Combination</h4>
  <pre><code>'ID 05ac:021e Apple:Keyboard'</code></pre>
  <p>This code helps the operating system identify the specific device (in this case, the Flipper Zero) and load the appropriate drivers or configurations, such as for an Apple keyboard.</p>
  
  <h4>The 'ignorespace' Option</h4>
  <pre><code>'echo -e "export HISTCONTROL=ignorespace\nunset HISTFILE" >> ~/.bashrc && source ~/.bashrc && exec bash'</code></pre>
  <p>This code enables the 'ignorespace' option for the command history, preventing commands with a leading space from being stored in the shell history. Special thanks to [FalsePhilosopher](https://github.com/FalsePhilosopher) for helping create this string!</p>
  
  <h4>Removing Specific Commands from History</h4>
  <pre><code>history -d $(history | tail -n 2 | head -n 1 | awk '{ print $1 }')</code></pre>
  <p>This code removes the specific command from the history, ensuring minimal traces are left behind and helping maintain discretion and privacy.</p>
</div>

<h1 align="center">🔹 Step by Step Directions 🔹</h1>

<ol>
  <li>
    <p>To upload the .txt files to your Flipper, you have two options:</p>
    <ul>
      <li>If you downloaded the .txt files, proceed to step 2.</li>
      <li>If you copied and pasted the code into a program, export or save the file as a .txt file on your desktop.</li>
    </ul>
  </li>
  <li>
    <p>Plug the Flipper into your computer and open the File Manager.</p>
    <p>Navigate to the SD card and open the BADUSB folder.</p>
    <p>Drag and drop the .txt files into the BADUSB folder.</p>
    <p>Close the Flipper desktop app when finished.</p>
  </li>
  <li>You are now ready to deploy your BADUSB DuckyScripts and take over the world! Enjoy!</li>
</ol>


  <h1 
   align="center">Support Narsty!
   

<h4 align="center"><em>If my work has brought a smile to your face or sparked joy in your heart, I wouldn't say no to a little digital love.</em></h4>

   <p></p>
    <p></p>
   
 <p align="center">
  <a href="https://www.blockonomics.co/pay-url/5106312c7ce343bb">
    <img src="https://www.opennode.com/blog/wp-content/uploads/2020/04/donate-button-small-1.png" alt="Donate with Bitcoin" width="290">
<div align="center">
  <img alt="Coding" width="283" height="15" src="https://media.giphy.com/media/9JxkPTP3alOykb8PmQ/giphy.gif"></div>

<p align="center">
  <img src="https://www.nist.gov/sites/default/files/2019-12/cyberattack-blogfeaturedimage-763.png" alt="Cyberattack Image">
</p>

<h2 align="center"><u><a href="https://github.com/narstybits/MacOS-DuckyScripts/blob/main/Warning%20%20Readme.md">!!!! EXERCISE CAUTION !!!!</a></u></h2>

<h2 align="center"><u>When executing code, double-check to ensure that you're targeting the correct directory/system and that the consequences are understood.</u></h2>

<h2 align="center">Deleting files and folders can have significant consequences!</h2>

<h1 align="center"><u><a href="https://github.com/narstybits/MacOS-DuckyScripts/blob/main/Warning%20%20Readme.md">!!! IMPORTANT DISCLAIMER !!!</strong></u></h1>

<h3 align="center">Please exercise caution and responsibility when using the scripts and tools in the "executions," "obscurity," "pranks," "GOODUSB," and "Recon" folders. These scripts are intended for educational and ethical purposes such as penetration testing, security testing, and network testing. However, it is important to note that unauthorized or malicious use of these tools can be illegal and may lead to severe consequences.</h3>

<p align="center">
    It is your responsibility to ensure that you have appropriate authorization, permissions, and legal rights to perform any security testing activities on computer systems or networks. Always respect the law, adhere to ethical guidelines, and obtain proper consent before conducting any tests or assessments.
</p>

<p align="center">
    Remember, it is crucial to prioritize legal and ethical practices, protect user privacy, and use these tools responsibly to improve security and protect against real-world threats.
</p>
