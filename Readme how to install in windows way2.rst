HOW TO INSTALL WHICH WINDOWS WAY 2
---------
We are going to use ubuntu bash on windows

Settings -> Update & security -> For developers, and activate "Developer mode"

Turn Windows Features on or off 

.. code-block:: console

      & C:\Windows\System32\OptionalFeatures.exe
      
Activate "Windows Subsystem for Linux"

Wait for the download

Try to open the "Windows PowerShell(Admin)" and type "bash" if don't work, download "Ubuntu" from "Microsoft Store".
Wait for the dowload, and open the "Windows PowerShell(Admin)" and type "bash"; 
(if don't work restart computer...)

Download 42
Put 42 folder in C:\

or open a terminal:

.. code-block:: console

     & bash
     & sudo apt install git
     & git clone https://github.com/Eloypripan/42.git 
     & sudo apt update
     & exit
     & exit

Instal `Xming <https://sourceforge.net/projects/xming/>`_ on windows

(Restart computer)

Open terminal

.. code-block:: console

      & bash
      & sudo apt update
      & sudo apt-get install vim-gtk
      & sudo apt install gcc
      & DISPLAY=:1 gvim #check that opens a xming display window   
      & sudo apt-cache search glut 
      & sudo apt-get install freeglut3-dev
      & cd 42 #use the route where 42 folder is install
      & make
      & DISPLAY=:1 ./42 #execute the 42

REFERENCES:
-------
`Ubuntu bash on windows <https://www.xataka.com/aplicaciones/asi-es-usar-la-consola-bash-de-ubuntu-en-windows-10/>`_

`How to Run Graphical Linux Desktop Applications from Windows 10’s Bash Shell <https://www.howtogeek.com/261575/how-to-run-graphical-linux-desktop-applications-from-windows-10s-bash-shell/>`_

`Open GL Glut libraries <https://askubuntu.com/questions/96087/how-to-install-opengl-glut-libraries/>`_

AUTHOR:
-----
Eloy Pieto Panadero

Github: `@Eloypripan <http://github.com/Eloypripan/>`__

Twiter: `@eloypripan <https://twitter.com/eloypripan/>`__

Instagram: `@eloypripan <https://instagram.com/eloypripan/>`__  

Facebook: `@Eloy Prieto Panadero <https://www.facebook.com/eloypripan/>`__ 

Creative Commons License: https://creativecommons.org/licenses/by-sa/4.0/
