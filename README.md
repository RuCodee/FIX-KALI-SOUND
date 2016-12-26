# FIX-KALI-SOUND
ONCE TIME YOU LOG ON KALI LINUX FIX KALI SOUND


1. Turn on Kali Linux, open terminal and type '' sudo killall pulseaudio '' and hit enter.

2. type '' sudo apt-get purge pulseaudio pulseaudio-utils gstreamer0.10-pulseaudio paman pavumeter pavucontrol '' and hit enter.

3. type '' rm ~/ .pulse-cookie ''and hit enter.

4. type '' rm -r ~/ .pulse '' and hit enter.

5. type '' sudo apt-get install alsa-base alsa-tools alsa-tools-gui alsa-utils alsa-oss alsamixergui libalsaplayer0 '' and hit enter.

6. type '' apt-get install kmix ''and hit enter.

7. And now restart machine.

8. open terminal again and type '' apt-get install pulseaudio '' and hit enter.

9. type '' type apt-get install gnome-core '' and again hit enter.

10.Restart machine.

11. open terminal again and type '' systemctl --user enable pulseaudio && systemctl --user start pulseaudio '' and hit enter.

..::E N J O Y::.. 
