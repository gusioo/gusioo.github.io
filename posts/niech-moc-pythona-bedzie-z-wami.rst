Niech moc Pythona będzie z Wami
###############################
:date: 2010-02-13 18:19
:author: Roch Brada
:tags: Oboczności
:slug: niech-moc-pythona-bedzie-z-wami
:status: published

| Roch myślał, że widział już (prawie) wszystko. Zdawało mu się, że z niejednego pieca chleb jadł, a jednak dziś doznał kolejnego oświecenia. Dostał był Roch plik, który trzeba było trochę “\ *przerobić”*, czyli coś wyciąć i coś dodać. Nie byłoby w tym nic dziwnego, gdyby nie to, że plik miał tysiąc linii, a więc ręczna edycja – nawet w weekend – odpada, bo Rochowi się nie chce. Pozostało napisane jakiegoś automatu, który wytnie z pliku kilka znaków i wstawi kilka innych.
| Kiedy Roch stwierdził, że pisanie programu odpada, bo już jest 15 linijek, a wciąż końca pliku nie widać wpadł na pomysł napisania skryptu. Jako, że lubi uczyć się nowych rzeczy sięgnął po `Pythona <http://pl.wikipedia.org/wiki/Python>`__. Wszyscy się nim zachwycają jako on jest prosty i fajny. Roch lubi proste i fajne rzeczy, więc był on w sam raz dla niego. Okazało się, że zapisanie tysiąca linijek bez dwóch pierwszych znaków mieści się w sześciu linijkach:
| ``def writeFile():    write_file = open("plik.txt", "w")    for binary in range(1000): ``
| ``        write_file.write(bin(binary)[2:])    write_file.close()    return``
| Później okazało się, że odczyt jest jeszcze prostszy, bo mieści się w jednej linijce. Roch zakochał się bez pamięci w prostocie i fajności. Pewnie znajdzie się osoba, która to jeszcze bardziej zoptymalizuje, ale Roch i tak jest z siebie dumny, bo 6 linijek to 15.
| Z braku tematów rowerowych Roch rzucił się na tematy informatyczne. To był ostatni raz, bo i tak już Roch przegina z elektroniką i robotami. Wybaczcie.
| Roch pozdrawia Czytelników.
