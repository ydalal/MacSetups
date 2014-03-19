MacSetups
=========
Setup NotePadpp as Default Editor in Mac

Download & Install Crossover

http://www.codeweavers.com/products/crossover-mac/download/

Install notepad++

Create file notepad in /usr/bin,

Add following line to it (Note, I have Cross Over 2, add appropriate path)

  /Applications/CrossOver\ 2.app/Contents/SharedSupport/CrossOver/bin/wine -cx-app notepad++.exe $1 &

Change Permission
  chmod 711 /usr/bin/notepad

Start Using notepad++
  notepad sample.sh
