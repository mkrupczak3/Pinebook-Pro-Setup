# Pinebook Pro Setup

So, I've been loving my [Pinebook pro](https://www.pine64.org/pinebook-pro/) so far, but my biggest issue with [Manjaro](https://www.pine64.org/pinebook-pro/) [arch](https://www.archlinux.org/) has been that there's no keyboard shortcut to open up a terminal!

Thankfully, Manjaro is the first linux distro (outside of Ubuntu) where I would be comfortable setting up my grandma with it (actually usable graphical user interfaces), but I still like having a terminal close at hand. 

This is where [yaquake](https://wiki.archlinux.org/index.php/Yakuake) came in for me. It works pretty well for that. 

I'm used to being able to open a terminal quickly with CTRL-ALT-T in Ubuntu, but with Yaquake I was able to bind this key combo to have a simple one drop down from the top of the screen. This was the easiest way I could find to get a button combo to launch a termnial in Manjaro, and I really like the look and feel of it.

My next big task is to optimize performance of this laptop with [page table compression](https://haydenjames.io/pinebook-pro-my-first-impressions-and-setup-tips/)

[More Pinebook Pro Setup and usage tips](https://louisabraham.github.io/articles/pinebook-pro-setup.html)

[More about this laptop](https://youtu.be/EoIfSnFCs84)

------------------------------------------------------

I've found a workaround for an Emacs crash bug with KDE [here](https://discuss.getsol.us/d/5252-undefined-color-window-foreground-doom-emacs), potentially making this computer one step closer to being  a fully usable laptop!

```
I have the same problem with normal Emacs on Solus. This is what worked for me: create a file named .Xresources in your home directory and put the following line in it (depends on your theme): *.WINDOW_FOREGROUND: white
After that execute xrdb ~/.Xresources in a Terminal.

If you are able to start Emacs after this, you have to make sure xrdb ~/.Xresources is executed on every startup by creating a corresponding startup application.
```

I've had a very, very good experience with the default KDE apps, and I've had a great experience using KMail, Kontact, and Kleopatra for email.
