<h1># i3-stuff</h1>
My stuff from i3 wm
This is where I keep my i3 configs and tweaks. Use at your own risk, not that I believe there will be any damage... but just in case :)
<pre>
My System: Mackbook Pro (2011)
OS: Debian 9.5 stretch
Kernel: x86_64 Linux 4.9.0-8-amd64
Shell: bash 4.4.12
Resolution: 1280x800
WM: i3
CPU: Intel Core i5-2415M CPU @ 2.9GHz
GPU: Mesa DRI Intel(R) Sandybridge Mobile 
RAM: 1.4GB / 16GB
</pre>
<h2>Preparing</h2>
git clone https://github.com/mauricioph/i3-stuff/i3-stuff.git <br />
Do it in the $Home/.config the folder should be at $HOME/.config/i3 <br />

<p>Then get the systemd service file copied to the system folder.<br />
cp $HOME/.config/i3/systemd/wakelock.service /etc/systemd/system/</p>
[code]
sudo systemctl enable wakelock.service
[/code]

