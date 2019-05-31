# Witaj w Głosowe Misie! 

## Wstęp
Jest to projekt realizowany na przedmiot Głosowa łączność z komputerem realizowanym na II roku studiów magisterskich na specjalności Informatyka i Elektronika w Medycynie.
Autorki:
- Justyna Bundyra
- Aleksandra Szum

## Co zrobić, jeśli chcesz skorzystać z projektu? 
Sklonuj repozytorium (git clone...), ściągnij najnowsze zmiany (git pull).

## Opis projektu

Celem projektu było stworzenie systemu do rozpoznawania słów do sterowania inteligentnym domem. 
W tym celu zostały nagrane pięciokrotnie przez trzy osoby o różnych porach dnia i różnym poziomie zmęczenia następujące słowa:

* otwórz/zamknij - słowa do sterowania drzwiami
* gorąco/zimno - słowa mające zwiększyć bądź zmniejszyć temperaturę powietrza domu o 3 stopnie Celsjusza 
* ciemno/jasno - słowa dotyczące światła - ciemno oznacza zgaszenie, jasno - zapalenie światła w aktualnie przebywającym pomieszczeniu
* stop - wypowiedzenie tego słowa informuje system inteligentnego domu, aby zakończył aktualnie wykonywane polecenie.
* rozwiń/zasłoń - słowa do sterowania roletami, oznaczają kolejno rozwinięcie i zasłonięcie rolet.

Sygnały te zostały poddane wstępnemu przetworzeniu - napisano funkcje do otwierania plików z rozszerzeniem .wav, do wyciągnięcia cech sygnału, a następnie zostały poddane analizie. Szczegóły i rezultaty zostały zawarte w notatniku Jupyter (https://github.com/aleksandraszum/glosowemisie/blob/master/Project.ipynb).

## Opis nagrań:
Litera alfabetu jest pierwszą literą imienia osoby nagrywanej. Nagrania o numerach 1-5 dotyczą słowa otwórz, 6-10 słowa zamknij, 11-15 słowa gorąco, 16-20 słowa zimno, 21-25 słowa ciemno, 26-30 słowa jasno, 31-35 słowa stop, 36-40 słowa rozwiń, 41-45 słowa zasłoń. 


