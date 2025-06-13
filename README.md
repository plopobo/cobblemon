# Cobblemon Instructions  
## Install Minecraft Launcher  
Download and Install the latest version of the Minecraft Launcher from [here](https://aka.ms/minecraftClientGameCoreWindows)  
> [!TIP]
> Need help? See: [How to Download and Install the Minecraft Launcher](https://help.minecraft.net/hc/en-us/articles/23907917790093-How-to-Download-and-Install-the-Minecraft-Launcher)  
<br/>  

## Installing Java  
### Check to see if Java is already installed  
1. Open the run window by pressing <kbd>Win</kbd> + <kbd>R</kbd>  
2. Type `cmd.exe` into the box that appears and click <kbd>OK</kbd>  
    ![RunCMD](https://github.com/user-attachments/assets/5eedcee4-04cb-436c-85c0-3b8191fbaac0)
3. Once you have opened the command prompt, type `java --version` and press Enter.  
    ![CMD_JavaInstalled](https://github.com/user-attachments/assets/816caa9a-b3f2-444e-a70a-efcbd17d4d8e)  
    :heavy_check_mark: If the command runs successfully and shows version 21 or higher, you're good to go! Skip ahead to [Install Neoforge](#install-neoforge).  
    :x: If the command fails or shows a version lower than 21, follow the steps below to install the correct version. 
> [!CAUTION]  
> Cobblemon requires Java 21 or higher. If you have an older version, you'll need to update.  
<br/>  

### Install Java  
We're going to install OpenJDK, an open-source version of Java. It works just like regular Java — it's modern, free, and perfect for Cobblemon!  
1. Download the latest OpenJDK 21 installer from [Microsoft](https://learn.microsoft.com/en-us/java/openjdk/download#openjdk-21).  
    - You'll want to download the Windows **<ins>`x64`</ins> <ins>`.msi`</ins>** version.  
2. Run the downloaded installer and follow the steps to install OpenJDK 21.  
3. When you reach the "Custom Setup" screen, make sure the following features are set to "Will be installed on local hard drive":  
    - `Modify PATH variable`  
    - `Associate .jar`  
![OpenJDK-Options](https://github.com/user-attachments/assets/850a61a6-4345-465c-b5fd-f385593210a9)  
4. Once you've done that, you can click <kbd>Next</kbd> and continue with the installation.  
> [!TIP]  
> Verify That Java 21 Is Installed installed by opening the command prompt again and typing `java --version`.  
<br/>  

## Install Neoforge
1. Go to the [NeoForge Download page](https://projects.neoforged.net/neoforged/neoforge)  
2. Under the `Select Version` section select Minecraft version `1.21.1`  
    - Neo version can be the latest.
    ![NeoForgeDownload](https://github.com/user-attachments/assets/d44efe5c-3bc5-45bb-afe0-a82424e30ecf)  
3. Click the `Download` icon  
4. Locate the downloaded file *(should be named something like neoforge-xx.x.xxx-installer.jar)*, right-click it, and choose `Open With` → `OpenJDK Platform Library`  
    ![NeoforgeOpenWith](https://github.com/user-attachments/assets/59aba43d-28a7-486c-b15e-b01cb2b6cd5c)  
5. The installer will attempt to install NeoForge into your vanilla launcher environment.  
6. Make sure `Install Client` is selected and click <kbd>Proceed</kbd>  
    ![NeoforgeInstaller](https://github.com/user-attachments/assets/22d06f41-bd06-49e7-b427-1278cb556c15)
> [!NOTE]  
> If you see a red box around the path make sure Minecraft is installed  
<br/>  

## Download Cobblemon + Kotlin Mods
Cobblemon requires the `Kotlin for Forge` mod to run.  
### Download Cobblemon Mod  
1. Navigate to the [Cobblemon Download Page](https://modrinth.com/mod/cobblemon?version=1.21.1&loader=neoforge) and download the latest version.  
2. Make sure to select:  
    - Game Version: `1.21.1`  
    - Platform: `NeoForge`
    
    ![CobblemonDownload](https://github.com/user-attachments/assets/9e3cec57-f202-4857-aff3-b46cf9f281cd)  
3. Then click the <kbd>Download</kbd> button to download.  
### Download Kotlin Mod  
1. Navigate to the [Kotlin Download Page](https://modrinth.com/mod/kotlin-for-forge/versions?version=1.21.1&loader=neoforge) and download the latest version.  
2. Make sure to select:  
    - Game Version: `1.21.1`  
    - Platform: `NeoForge`  
3. Then click the <kbd>Download</kbd> button to download.  
<br/>  

## Install The Mods  
1. Open the Minecraft Launcher.  
    - Select `Minecaraft: Java Edition` from the side menu.  
2. Click on the `Installations` tab.  
3. Click on the `Open Installations Folder` icon next to `NeoForge`  
![MinecraftLauncherNeoForge](https://github.com/user-attachments/assets/f1ddce55-2fa5-4bae-b362-320594cdb82d)  
4. Inside that folder, create a folder called mods if it doesn't already exist.  
5. Copy and paste both the Cobblemon and Kotlin .jar files into the mods folder.  
> [!TIP]  
> Your mods folder should look like this:  
> ![ModsFolder](https://github.com/user-attachments/assets/f73dc3c3-dff6-4389-bb3a-2681e10fa8d3)  
> *Note: version numbers in the filenames might be different.*  
<br/>  

## Launch the game!!  
Now you're ready to play with Cobblemon!  
1. Open the Minecraft Launcher.  
    - Select `Minecaraft: Java Edition` from the side menu.  
2. Click on the `Installations` tab.  
3. Click on </kbd>Play</kbd> next to `NeoForge` profile.  
4. The game will launch and install the mods — you're ready to go!  
