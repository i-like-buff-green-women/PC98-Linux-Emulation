# PC98-Linux-Emulation
This is a based on the instructions found in SmupsBR's video [https://www.youtube.com/watch?v=aOD_bGNtuFY&amp;t=331s](https://www.youtube.com/watch?v=aOD_bGNtuFY&amp;t=331s) - I wanted to document this in case the video ever went down, and hopefully expand on it.  Please note that I am a bit of a n00b and quite new to emulating this, so please excuse me if I am not able to assist in deeper troubleshooting.
<br>
<br>
You will need these packages:
<br>
```wine```
<br>
```winetricks```
<br>
```unrar``` [Or your preferred ```.rar``` extractor]
<br>
I am running off of a Debian-based distro, and needed ```lib32z1``` in order for this to run.  This may or may not apply to you, depending on your distro, but I received a ``` ia32 panic``` error without it.
<br>
<br>
1.Download the ```'PC-98 pack (v1.3).rar'``` file from [https://drive.google.com/file/d/1jYGmTF04bUeVAj0eDAzL5Ktz3cmBYQXk/view](https://drive.google.com/file/d/1jYGmTF04bUeVAj0eDAzL5Ktz3cmBYQXk/view) and extract at your preferred location [```unrar e 'PC-98 pack (v1.3).rar'```].  This comes with a lot of preloaded things.
<br>
2.Navigate to ```/PC-98 pack (v1.3)/Neko Project 21W rev62``` and run ```wine np21x64w.exe``` [let it install whatever it says it needs]
<br>
3.It will throw an error after the first start, just click ```OK```
<br>
4.Click on the ```Emulate``` tab and click ```Reset```
<br>
5.After it boots, you should see a few lines, one being in red, just press the ```R``` key to bypass.  You will need to do this everytime on boot. 
<br>
6.Click on the ```Harddisk``` tab and navigate to ``` IDE #0>Open``` and open ```GameHDD.nhd``` in the root ``` PC-98 pack (v1.3)``` dir.
<br>
7.From here, you should have the emulator running, and see a screen with menu options, which are numbered on a column to the far left.
<br>
8.Using the arrow keys and ```Enter``` key, navigate to option 003 ```Filemmtn file manager (test mode + wallpaper)``` or 004 ```Filemtn file manager (graphical mode, no wallpaper)``` depending on your preference.
<br>
9.Navigate to ```games```
<br>
10.From here, navigate to the folder of the game you are interested in.
<br>
11.Navigate over to the ```start.bat``` file and hit ```R``` to run, then ```Enter``` to confirm.
<br>
12.Your game should be loaded and playable.
<br>
<br>
[Optional] 
<br>
You can insert a config file for performance tweaks if you run into issues
<br>
1.At the home menu, press ```F11```
<br>
2,Navigate to the ```Emulate``` tab and select ```Load VM config``` and open the ```VMCONFIG.npcfg``` file.
<br>
<br>
At this time, I do not have further instructions or recommendations, but will add more as I learn.
