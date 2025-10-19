import string
#articolul despre explozia din Rahova
articol = " Anchetatorii au început audierea martorilor. Printre cei care au dat declarații polițiștilor criminaliști sunt și locatari din blocul distrus.Unii dintre ei au susținut că o firmă privată ar fi deschis, joi seara, robinetul de gaze, sigilat dimineața de echipele Distrigaz. Procurorii fac verificări.Florin Mirea, fost locatar: A venit firma respectivă la ora 5, nu s-au înțeles, a venit a rupt sigiliul direct. Scurgerea de gaz a fost pe conducta de alimentare cu gaz a blocurilor. Fiind fisura lângă blocul respectiv, a intrat în subsol și până a aerisit s-a dus în tot blocul și toate apartamentele. S-a acumulat la etajele unde au fost închise geamurile. A fost o primă explozie la etajele care au fost spulberate și o a doua explozie a fost în subsolul blocului, care s-a simțit ca un cutremur"

#impartirea textului in 2 parti egale

jumate = len(articol) //2
prima_parte =articol[:jumate]
a_doua_parte = articol[jumate:]


#transformare toate litere in majuscule din prima parte

prima_parte = prima_parte.upper()


#eliminare toate spațiile goale de la inceputul si finalul sirului

prima_parte = prima_parte.strip()

#inversarea caracterelor din a doua parte

a_doua_parte = a_doua_parte[::-1]

#capitalizare prima litera

a_doua_parte = a_doua_parte.capitalize()

#eliminare semne de punctuatie din a doua parte

a_doua_parte = a_doua_parte.replace(".", "").replace(",", "").replace("!", "").replace("?", "")

#combinarea celor doua parti si printarea rezultatului.

text_combinat = prima_parte + a_doua_parte
print (text_combinat)


