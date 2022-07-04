# Gshade for Crossover Mac
Simple guide for getting Gshade installed in to your Crossover Mac games.

<h3>Prerequisites:</h3>
- Latest Mac Crossover installed (download Mac CX here: https://www.codeweavers.com/)<br>
- A working Windows 64-bit executable game within Mac Crossover that uses DirectX 9 or 11. <br>
- Knowledge of working directories inside MacOS.<br><br>

<i>(This isn't a Crossover game setup guide)</i><br>
<hr>
Support inside the <b>XIV on Mac</B> discord in #support-gshade text channel: https://xivmac.com/discord
<hr>

<h3>Setup:</h3>

Choose one of 2 Download options:<br>
1)  <b>(RECOMMENDED)</b> Download/clone this github<br>
2)  or Download "gshade_installer.sh" from https://github.com/HereInPlainSight/gshade_installer<br><br>


<img src="/gh images/first.png"></a> </p>

Type "sh" space, and drag either "manual_gshade.sh" or "gshade_installer.sh" into terminal. <br><br>

Example:<br><br>
<img src="/gh images/kik.gif"></a> </p><br>


You should now see install options in terminal after the script has loaded:
<img src="/gh images/install1.png"></a> </p>


Type "2" to Install to a custom game.<br>

<img src="/gh images/customgame.png"></a> </p>

When <b>"Install with dxgi?</b> prompt comes up,<br>

Type "Y" if your game is a DirectX 11 64-bit game <br>
or "N" if your game is a DirectX 9 64-bit game<br><br>

<b>Sims 4 players choose "N" here!</b><br><br>

If prompted what api to use, only choose dx9 or dx11. <b>(Sim 4 users choose DX9)</b>
<img src="/gh images/dx.png"></a> </p>

Next we need to locate the WINEPREFIX where drive_c is at for your Crossover installed game and copy the directory path after the terminal prompt.<br><br>
You can easily find this by using Mac's Finder and going to ```~/Library/Application Support/Crossover/Bottles/```<br><br>
Here is an example of my Crossover bottle (Custom Wine Mac Game):
<img src="/gh images/drivec.png"></a> </p>


Next, copy your games bottle folder directly into the terminal prompt, in my example the "Custom Wine Mac Game" bottle folder. This will complete the folder path automatically for you. You can then press enter.
<img src="/gh images/drivecpath.png"></a> </p>


Next, you will be prompted to find the game's .exe. Locate your games ".exe" within the "drive_c" folder and copy that ".exe" over to the terminal prompt as so. You can now press enter again to complete Gshade install.

<img src="/gh images/exe.png"></a> </p>


If you followed the instructions correctly and have all the correct parameters, gshade should now load next time you run the game.<br><br>
Shift+F2 or FN+Shift+F2 on Macbook to enter gshade settings.<br><br>
Preview of Trine 3 (DX9 64-Bit game) running gshade in Crossover Mac: 

<img src="/gh images/trine2.png"></a> </p>

Sims 4 users please continue to next section below!

<h2>Sims 4 in Crossover special intructions:</h2><br>

Inside Crossover, make sure <b>"DXVK backend for dx11"</b> is turned OFF!<br><br>
<img src="/gh images/sims4.png"></a> </p>

<hr>

<b>Thanks to:</b><br> 
https://gposers.com/gshade <br>
https://github.com/HereInPlainSight/ for his Linux script<br>
https://github.com/marzent for his PR's and making Gshade more Mac friendly.
