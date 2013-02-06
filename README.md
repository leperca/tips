# restart xorg
setxkbmap -option terminate:ctrl_alt_bksp
# set gnome-time-bar show date
gsettings set org.gnome.desktop.interface clock-show-date true
# exclude kernel update in yum update
in /etc/yum.conf: exclude=kernel* or  yum --exclude=kernel* update
# something about install mayavi(Enthghout inc.) 
maybe it's need vtk and vtk-devel and easy_install it again.
