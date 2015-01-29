# Patricia Ennenbach
# 29.01.2015
# Zahlen raten

import random
geheimnis = (random.randint(1,99))
tipp=0
versuche=0
print ("AHOI! Ich bin Kpt. Flitzpiepe und ich habe ein Geheimnis!")
print ("Es ist eine Zahl zwischen 1 und 99. Du hast 6 Versuche!")
while tipp != geheimnis and versuche < 6:
    tipp = int (input("Tippe eine Zahl ein: "))
    if tipp < geheimnis:
                print("Zu niedrig, du Landratte!")
    elif tipp > geheimnis:
                print("Zu hoch, du Leichtmatrose!")

    versuche=versuche+1

if tipp == geheimnis:
    print ("Ha! Du hast es erraten!")
else:
    print ("Alle Versuche verbraucht! Mehr Glück beim nächsten Mal!")
    print (("Gesucht war: "),geheimnis)
