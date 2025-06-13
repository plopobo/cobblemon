# Cobblemon Instructions  
## Install Minecraft Launcher  
Download and run the latest version of the installer from [here](https://aka.ms/minecraftClientGameCoreWindows)
<br>
## Installing Java
> [!TIP]
> Check to see if Java is already installed
1. Open the run window by pressing <kbd>Win</kbd> + <kbd>R</kbd>  
2. Type `cmd.exe` into the box that appears and click <kbd>OK</kbd>  
    ![RunCMD](https://github.com/user-attachments/assets/5eedcee4-04cb-436c-85c0-3b8191fbaac0)
3. Once you have opened the command prompt, type `java -version` and press Enter.  
    ![CMD_JavaInstalled](https://github.com/user-attachments/assets/816caa9a-b3f2-444e-a70a-efcbd17d4d8e)  
    If the command runs successfully, you will see something like this. You can continue to [Install Neoforge](#install-neoforge).  
    If the command failed, proceed to the [next step](#install-java).  
> [!WARNING]
> You'll need at least Java 21 installed. If this command displays any version lower than 21, you'll need to update your existing Java installation.  
<br/>  
### Install Java
1. Download the installer from [Microsoft](https://learn.microsoft.com/en-us/java/openjdk/download#openjdk-21).  
    > You'll want to download the Windows x64 .msi version.  
2. Run the downloaded installer and follow the steps to install Java 21.  
3. When you reach this page, you should set the following features to "Will be installed on local hard drive":  
    > `Modify PATH variable`  
    > `Associate .jar`  
    > ![OpenJDK-Options](https://github.com/user-attachments/assets/850a61a6-4345-465c-b5fd-f385593210a9)  
4. Once you've done that, you can click <kbd>Next</kbd> and continue with the installation.  
> [!TIP]
> Verify That Java 21 Is Installed installed by opening the command prompt again and typing `java --version`.  
<br/>  
## Install Neoforge
1. Go to the [NeoForge Download page](https://projects.neoforged.net/neoforged/neoforge)  
2. Under the **Select Version** section select Minecraft version 1.21.1  
    > [!TIP]
    > You can select the Latest version for the **Neo Version**  
    > ![NeoForgeDownload](https://github.com/user-attachments/assets/d44efe5c-3bc5-45bb-afe0-a82424e30ecf)  
3. Find the downloaded installer file, right-click it and choose `Open With` > `OpenJDK Platform Library`  
    ![NeoforgeOpenWith](https://github.com/user-attachments/assets/59aba43d-28a7-486c-b15e-b01cb2b6cd5c)  
4. The installer will attempt to install NeoForge into your vanilla launcher environment.  
    > [!NOTE]
    > If you see a red box around the path make sure Minecraft is installed  
5. Make sure `Install Client` is selected and click <kbd>Proceed</kbd>  
    ![NeoforgeInstaller](https://github.com/user-attachments/assets/22d06f41-bd06-49e7-b427-1278cb556c15)  
<br/>  
## Download Cobblemon + Kotlin Mods
> [!NOTE]
> Cobblemon requires NeoForge and the Kotlin for Forge Mod.
### Download Cobblemon Mod  
1. Navigate to the [Cobblemon Download Page](https://modrinth.com/mod/cobblemon?version=1.21.1&loader=neoforge) and download the latest version.  
2. Make sure to select:  
    > Game Version: 1.21.1  
    > Platform: NeoForge  
    > ![CobblemonDownload](https://github.com/user-attachments/assets/9e3cec57-f202-4857-aff3-b46cf9f281cd)  
3. Then click the <kbd>Download</kbd> button to download.  
### Download Kotlin Mod  
1. Navigate to the [Kotlin Download Page](https://modrinth.com/mod/kotlin-for-forge/versions?version=1.21.1&loader=neoforge) and download the latest version.  
2. Make sure to select:  
    > Game Version: 1.21.1  
    > Platform: NeoForge  
3. Then click the <kbd>Download</kbd> button to download.  
<br/>  
## Install The Mods  
1. Open the Minecraft Launcher.  
    > Make sure **Minecaraft: Java Edition** is selected from the left hand menu.  
2. Click on the **Installations** tab.  
3. Click on the ***Open Installations Folder** icon next to **NeoForge**  
  ![MinecraftLauncherNeoForge](https://github.com/user-attachments/assets/f1ddce55-2fa5-4bae-b362-320594cdb82d)  
4. Create a new folder called `mods` if one isn't already there.  
5. Copy and Paste the two mod files for Cobblemon and Kotlin into the mods folder.  
<br/>  
> [!TIP]
> Your mods folder should look like this:  
> ![ModsFolder](https://github.com/user-attachments/assets/f73dc3c3-dff6-4389-bb3a-2681e10fa8d3)  
> *Note: The versions in the filenames may be different*  
<br/>  
## Launch the game!!  
Once the mods have been loaded into the NeoForge `mods` folder, you can launch NeoForge and let the mods install.  
1. Open the Minecraft Launcher.  
    > Make sure **Minecaraft: Java Edition** is selected from the left hand menu.  
2. Click on the **Installations** tab.  
3. Click on </kbd>Play</kbd> next to **NeoForge**  
4. Allow the mods to install and you're ready to play!  
