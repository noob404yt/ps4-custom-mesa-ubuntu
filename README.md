# Custom Mesa for PS4 running Ubuntu and Ubuntu-based distros
This custom-built Mesa fixes image distortion on many games like Cyberpunk running on PS4 (PlayStation 4) through Wine, especially on the latest versions of Ubuntu.

## Using the custom Mesa script on PS4 Ubuntu
1. Open terminal and run `sudo apt install libz3-4`
2. Download the latest .tar.xz and .sh from the Releases section.
3. Extract the archive into the folder - /home/noob404/. If your distro doesn't have one, make the folder - noob404 with proper permissions.
4. Open terminal and run `source mesa.sh` and make sure you change the path of the mesa.sh according to your location. 
5. Run wine or any other launcher command on the same terminal to launch your game.

## Notes
1. The version numbers don't mean an incremental upgrade. So, v2 might not have a more later version of Mesa than v1. In most cases, it would be the opposite.
2. Read the description of the release to find the purpose. Mostly, they are to run specific games or applications.

If you need a more comprehensive tutorial or a video tutorial checkout my [article](https://ps4linux.com/image-distortion-cyberpunk-ps4-linux-fix/).
