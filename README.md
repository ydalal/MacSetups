MacSetups
=========
Setup NotePadpp as Default Editor in Mac

0. Download & Install Crossover

1. http://www.codeweavers.com/products/crossover-mac/download/

2. Install notepad++

3. Create file notepad in /usr/bin,

4. Add following line to it (Note, I have Cross Over 2, add appropriate path)

  /Applications/CrossOver\ 2.app/Contents/SharedSupport/CrossOver/bin/wine -cx-app notepad++.exe $1 &

5. Change Permission

  chmod 711 /usr/bin/notepad

6. Start Using notepad++

  notepad sample.sh
