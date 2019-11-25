# plymouth-anonymous

[![Watch the video](/preview.png)](https://youtu.be/n090S82D32M)

## HOW TO:
  1. `cd /usr/share/plymouth/themes/`
  2. `sudo svn export https://github.com/FabrizioFubelli/plymouth-anonymous.git/trunk/anon`
  3. `sudo plymouth-set-default-theme -R anon`
  4. `sudo update-initramfs -u`
  5. `sudo update-grub2`
