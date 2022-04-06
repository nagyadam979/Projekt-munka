# Projects
----- Összefoglaló és konklúzió ----- 
 
Az első fejezetben az adatokról vizuális módszerek segítségével megállapítottunk pár olyan kulcs kérdést, 
  mint a minták csoporosulása (klaszterek, esetleges alkatrész típusok), az összefüggés lehetséges monomiális alakja,
  illetve a vizuálisan megállapított "hibák" megkérdőjelezhetősége. 
Vizsgáltuk a klaszterezés létjogosultságát, ahol azt találtuk (Jmax-hoz viszonyítás), hogy lehetséges elvégezni a klaszterezést,
  s ezek után a meghatározott klaszterekkel végeztük a számításokat. 
Ezek után elvégeztük a lineáris regressziót, amiből meg tudtuk állapítani a klasztereinket jellemző paramétereket. 
Majd az összefüggéseket tovább bontva megkaptuk a Ps függését nem csak a Jmax-tól, hanem a frekvenciától is.

További lehetőségek:
Még érdekes lehet a hibák összefüggése is a frekvenciával a Jmax-al, illetve a többi paraméterrel.
A hibák egyik forrása lehet, hogy valójában nem monomiális az összefüggés, hanem polinomiális, így az egyik lnehetséges javítása
  a modelljeinknek, hogy nem a logaritmizált és csoportosított adatatokra végzünk lineáris regressziót, hanem minden egyes 
  'sample'-re készítünk polinomilleszést, esetleg az így kapott paramétereket vizsgáljuk.
