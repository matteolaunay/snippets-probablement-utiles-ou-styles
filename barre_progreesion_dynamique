import time
donnes_totales = 500

for donnes_telechargees in range(donnes_totales+1): # on imagine qu'on telecharge octet par octet un fichier de "donnees_totales" octets

    pct_telecharge = 100 * donnes_telechargees / donnes_totales # calcul du % de donnnées telechargees
    
    print("{: <20} {}%".format("*"*int(pct_telecharge//5), pct_telecharge), end='\r', flush=True) # voir https://kapeli.com/cheat_sheets/Python_Format_Strings.docset/Contents/Resources/Documents/index pour le 
#formatage  ^^^^^
    time.sleep(0.001) # on est obligé de mettre un délai sinon l'éxécution est trop rapide
