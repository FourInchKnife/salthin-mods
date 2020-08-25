# salthin-mods
Mod pack on Salthin’s private server. 

#### Basic Setup
Make sure to install forge from 
[the official Forge website](https://files.minecraftforge.net/maven/net/minecraftforge/forge/index_1.15.2.html "Minecraft Forge for 1.15.2")
and get at least version *31.2.36* (currently the latest version, not the recommended one)

Once you download and run the forge installer, set the version in the launcher
to Forge 1.15.2 and run the game. After the first run,
close the game and put the mods folder into your `.minecraft`
folder. In-depth instructions [here](https://minecraft.gamepedia.com/Mods/Forge#Forge_Modifications "Minecraft Gamepedia guide to modding").

If you are in the `New Game+` Discord server you can [view the IP](https://discordapp.com/channels/493574653797990420/745314060127436850/745330525253926983).

#### Slightly More Advanced Setup
For this you need either [Git](https://git-scm.com/) or [Git for Windows](https://gitforwindows.org/). If you are using Git for Windows, you need to install it 
in "Git Bash". Don't put it in PATH. Follow the instructions above to download and install [Forge](https://files.minecraftforge.net/maven/net/minecraftforge/forge/index_1.15.2.html "Minecraft Forge for 1.15.2")
and then open your launcher. Navigate to `installations > Forge 1.15.2` and click on the triple dot to change the game directory from `.../.minecraft/` to `.../.minecraft/salthin-mods/`.
While you're in this menu you may want to allocate more RAM by clicking the `Advanced Options` and changing `-Xmx#G` in `JVM Arguments` so that # is the amount of RAM in gigabytes
that you want to allocate. I'd recommend at least 4 gigabytes, but you need to make sure your system has at least 4 GB more than whatever you allocate.

Click save in that menu and run the `Forge 1.15.2` installation once before adding any mods. Open up either a `Terminal` window (Mac or Linux) or a `Git Bash` window (Windows). Use the `cd` command to navigate to 
a directory that you will remember, then run `git clone https://github.com/FourInchKnife/salthin-mods`. Using your file explorer, navigate into `salthin-mods/` and copy its contents into `.../.minecraft/salthin-mods/`.
Make sure you copy the folder called `.git/`. You may need show hidden files enabled to be able to see it. If you get a warning that says something like "the mods directory already exists" you should click confirm or overwrite.
Run the game to make sure all mods load.

To update your mods folder on Linux, use the command `cd ~/.minecraft/salthin-mods/ && git fetch && git clone` in Terminal. Update instructions for Windows will come later.
