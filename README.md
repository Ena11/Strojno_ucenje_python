# Metode umjetne inteligencije (chatbot, prepoznavanje slika i web scraping) u izradi aplikacije za poduzeće koje se bavi poljoprivredom (u Pythonu).
# Opis problema
Poduzeća se suočavaju s ključnim izazovima u očuvanju zdravlja biljaka i optimizaciji uvjeta uzgoja. Glavni problemi obuhvaćaju poteškoće u identifikaciji bolesti biljaka, nedostatak precizne dijagnoze i teškoće u praćenju specifičnih simptoma
# Rješenje
Chatbot je implementiran kao alat za komunikaciju s poljoprivrednicima, pružajući im jednostavan način dijeljenja informacija
Implementirano je i prepoznavanje slika, koristeći InceptionV3 model iz TensorFlow biblioteke te je tako omogućeno dijeljenje slika bolesti biljaka
Treće implementirano rješenje je web scraping, koristeći BeautifulSoup i requests za prikupljanje informacija o bolestima i štetnicima biljaka s različitih izvora na webu. 
# O korištenju
Program je pisan koristeći Google Collab notebook, u slučaju pokretanja u npr. PyCharm-u potrebno je najprije instalirati pakete.
# Pojedinosti
Za pokretanje dijela "prepoznavanje slika" potrebno je programu dati određene slike za prepoznavanje (a koje su najprije spremljene na računalo, stoga se path slike može razlikovati)
Kako bi se vidio rezultati web scraping-a, potrebno je preuzeti .csv datoteku nakon pokretanja koda
