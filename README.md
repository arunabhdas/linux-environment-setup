# linux-environment-setup

1) Copy .vimrc to $HOME

==> cp dotfiles/vimrc.txt $HOME

2) Copy .Xmodmap to $HOME
Please note that this steps is only necessary for remapping Super to Ctrl
==> cp dotfiles/Xmodmap.txt $HOME

3) Ensure ~/.Xmodmap is sourced in .bashrc as follows

==> echo "source ~/.Xmodmap" >> ~/.bashrc

4) Install Android Studio as described here :
https://developer.android.com/studio/install.html
