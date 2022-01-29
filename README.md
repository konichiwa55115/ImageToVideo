# Dependencies
You will need both **ffmpeg** and **python** installed for the script to work and **curl** for the installation to work.

# Install
**Before running this in your terminal please read [Installation](https://github.com/JustCoww/ImageToVideo/blob/main/Installation.md) to understand what this does.**


**Arch Based**
  ```
  sudo pacman -S curl ffmpeg python3 && sudo curl https://raw.githubusercontent.com/JustCoww/ImageToVideo/main/imagetovideo -o /usr/bin/imagetovideo && sudo chmod a+rx /usr/bin/imagetovideo && sudo ln /usr/bin/imagetovideo /usr/bin/itv
  ```
  
  
**Debian Based**
  ```
  sudo apt install curl ffmpeg python3 && sudo curl https://raw.githubusercontent.com/JustCoww/ImageToVideo/main/imagetovideo -o /usr/bin/imagetovideo && sudo chmod a+rx /usr/bin/imagetovideo && sudo ln /usr/bin/imagetovideo /usr/bin/itv
  ```
  
  
**Other**

Just make sure you have curl, ffmpeg and python3 installed and run this.
  ```
  sudo curl https://raw.githubusercontent.com/JustCoww/ImageToVideo/main/imagetovideo -o /usr/bin/imagetovideo && sudo chmod a+rx /usr/bin/imagetovideo && ln /usr/bin/imagetovideo /usr/bin/itv
  ```

  # Usage
Just run '**itv**' or '**imagetovideo**' in your terminal and follow the instructions.
  ```
  itv
  ```

# Uninstall

**To uninstall the script just run**
  ```
  sudo rm /usr/bin/itv && sudo rm /usr/bin/imagetovideo
  ```
**This will remove the script from your system**


# Demo video
https://user-images.githubusercontent.com/68345611/147878721-0bd197ac-8c00-4ae9-b35a-85d0db6a9b79.mp4

