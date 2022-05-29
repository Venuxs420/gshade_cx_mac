# Gshade for Crossover Mac games
Simple guide for getting Gshade installed in to your Crossover Mac games.

<h3>Prerequisites:</h3>
- Latest Mac Crossover installed (download Mac CX here: https://www.codeweavers.com/)<br>
- A working Windows 64-bit executable game within Mac Crossover that uses DirectX 9 or 11. <i>(This isn't a Crossover game setup guide)</i><br>
- Knowledge of working directories inside MacOS.<br>
<h3>Setup:</h3>

Clone this github <b>(RECOMMENDED)</b><br>
or click unsigned <b>"gshade_mac script"</b> from the release section to the right.<br>
<img src="/gh images/release.png"></a> </p>

Download "gshade_mac.zip" and extract the "gshade_mac" folder.

<img src="/gh images/download.png"></a> </p>

Open the "gshade_mac" folder and click "install.command"<br>
The release is not signed and will prompt gatekeeper message, you can control+click "install.command" to bypass it.<br>

<img src="/gh images/install1.png"></a> </p>


Type "2" to Install to a custom game.<br>

<img src="/gh images/customgame.png"></a> </p>

When <b>"Install with dxgi?</b> prompt comes up,<br>

Type "Y" if your game is a DirectX 11 64-bit game <br>
or "N" if your game is a DirectX 9 64-bit game.

If prompted what api to use, only choose dx9 or dx11.
<img src="/gh images/dx.png"></a> </p>

Next we need to locate the WINEPREFIX where drive_c is at for your Crossover installed game and copy the directory path after the terminal prompt.<br>
You can easily find this by using finder and going to ```~/Library/Application Support/Crossover/Bottles/```
