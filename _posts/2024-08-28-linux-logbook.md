---
layout: post
title: "Linux logbook"
date: 2024-08-28
---
<p>
I've recently needed to re-install my ubuntu. It makes me have to built everyhting from scratch packages I need to optimize my productifity. Accordingly, I decided to create this thread 
as my archive and for future references if I end up need to do it again. This can also be found helpful for those who want to install package(s) that is relevant with their needs.
</p>
<h2> Ubuntu </h2>
<p>
ISO file for the updated version: https://ubuntu.com/download
</p>
<p>
Creating bootable USB stick: https://etcher.balena.io/
</p>
<p>
To begin installation, restart the computer and eneter to BIOS system by pressing F1 during the first booting. Change the booting priority and restart the computer. Access the USB installation 
by pressing F12 in the first booting process. For step by step installation: https://ubuntu.com/tutorials/install-ubuntu-desktop#5-installation-setup .
</p>
<h2> LaTeX </h2>
<p>
It is recommended to update the system: sudo apt-get update
</p>
<p>
Start installation: sudo apt-get install texlive-full
</p>
<p>
I prefer TexStudio for my editor: sudo apt-get install texstudio
</p>
<h2> Jupyter-notebook </h2>
<p>
For setting all things up: https://jupyter.org/install
</p>
<p>
However, I my system adopted <href=https://peps.python.org/pep-0668/><PEP 668>. I realized that it is already available in the repository. It can be installed by: sudo apt install jupyter-notebook
</p>
<h2> Note: </h2>
<p>
This logbook will be updated whenever I install a new package in my system.
</p>
