# Zadanie 6. Martianeum

W 2033 roku na Marsie wylądowała automatyczna stacja wydobywcza wyposażona
w transporter i w autonomiczny dron pobierający ładunki skał zawierających minerał
niewystępujący na Ziemi – martianeum.

Stacja działa według następujących zasad:
- dron codziennie przywozi ładunek z pewnego obszaru Marsa
- stacja waży ładunek przywieziony przez drona i bada zawartość martianeum
- jeśli zawartość martianeum w przywiezionym ładunku wynosi co najmniej 1%, to stacja
automatycznie wydobywa cały minerał z tego ładunku
- jeśli na koniec dnia (po wydobyciu martianeum) ilość minerału na stacji osiągnie co
najmniej 100 kg, to transporter zabiera 100 kg na orbitę, skąd ładunek jest wysyłany na
Ziemię, a transporter wraca do stacji (jeśli na stacji zgromadzone jest więcej niż 100 kg, to
nadmiar pozostaje na stacji)
- początkowy stan magazynu na stacji – 0 kg martianeum.

W pliku tekstowym `martianeum.txt` w kolejnych wierszach zapisano dane z lat 2033–
2038:
`data` – data przywozu ładunku w formacie rrrr-mm-dd

`nazwa_obszaru` – nazwa obszaru Marsa, z którego ładunek został pobrany

`masa [kg]` – masa ładunku drona w kilogramach

`zawartość [%]` – zawartość martianeum w próbce w % (nieujemna liczba z jednym
miejscem po przecinku, np. 0,1 oznacza 0,1%)

Dane w pliku rozdzielono znakami tabulacji.

**Przykład:**

| data       | nazwa_obszaru   | masa [kg] | zawartosc [%] |
|------------|-----------------|-----------|---------------|
| 2033-03-03 | Cebrenia        | 27,8      | 0,2           |
| 2033-03-04 | Amenthes        | 11,8      | 1,7           |
| 2033-03-05 | Noachis         | 21,0      | 6,0           |
| 2033-03-06 | Coprates        | 26,3      | 11,4          |
| 2033-03-07 | Ismenius Lacus  | 28,8      | 0,0           |
| 2033-03-08 | Mare Boreum     | 29,2      | 0,0           |

Z wykorzystaniem danych zawartych w pliku `martianeum.txt` oraz dostępnych narzędzi
informatycznych wykonaj podane zadania. Wyniki zapisz w pliku tekstowym `wyniki6.txt`.
Odpowiedź do każdego zadania poprzedź numerem tego zadania.

## Zadanie 6.1. (0−2)
Podaj łączną masę ładunków drona oraz łączną masę martianeum wydobytego przez stację.

## Zadanie 6.2. (0−1)
Podaj nazwę obszaru, dla którego średnia masa przywiezionych ładunków jest najmniejsza.

## Zadanie 6.3. (0−2)
Czas pracy stacji dzielimy na kolejne 7-dniowe okresy. Pierwszy okres obejmuje dni od
03.03.2033 do 09.03.2033, drugi – od 10.03.2033 do 16.03.2033 itd.
Podaj największą łączną masę ładunków przywiezionych w ciągu kolejnych 7-dniowych
okresów oraz podaj datę początku okresu, w którym przywieziono tę największą masę.

## Zadanie 6.4. (0−3)
Wykonaj zestawienie, w którym dla każdego obszaru podasz, ile razy dron przewoził ładunek
z tego obszaru w poszczególnych latach.
Na podstawie wykonanego zestawienia utwórz wykres skumulowany kolumnowy. Pamiętaj
o czytelnym opisie wykresu: na osi X umieść nazwy obszarów, dodaj opisy osi – „nazwy
obszarów” dla osi X i „liczba przewozów ładunku” dla osi Y, tytuł oraz legendę zawierającą
kolejne lata.

## Zadanie 6.5. (0−3)
Uwzględnij zasady działania stacji opisane na początku zadania i podaj:
- ile razy stacja wysyłała ładunek na orbitę
- datę pierwszego transportu ładunku na orbitę
- datę ostatniego transportu ładunku na orbitę.


# Do oceny oddajesz:
- plik tekstowy `wyniki6.txt` zawierający odpowiedzi do zadań 6.1.–6.5. Odpowiedź do
każdego zadania powinna być poprzedzona jego numerem.
- plik zawierający wykres do zadania 6.4. o nazwie: `wykres6.jpg`
- plik(pliki) zawierający(-e) komputerową realizację Twoich rozwiązań o nazwie(-ach):
(uwaga: brak tych plików jest równoznaczny z brakiem rozwiązania zadania)

