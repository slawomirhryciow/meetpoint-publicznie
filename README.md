# Meetpoint — publicznie

Meetpoint to aplikacja do umawiania wspólnych treningów w zamkniętej grupie biegowej, która już się zna. Wspólny start i meta, rozbieżne treningi w środku: jeden robi interwały, drugi spokojne 10 km, trzeci długie wybieganie. Widok grupuje ludzi według tego, kto co robi. Czat tego nie zrobi.

Buduję ją publicznie. To repozytorium jest tą częścią, której nie da się cofnąć.

## Po co to repozytorium

Deklaracja „ogłaszam kryteria z góry" jest warta dokładnie tyle, ile dowód, że kryteria stały tam wcześniej. Post można usunąć i napisać na nowo, stronę nadpisać. Historia commitów ma daty.

Więc kryteria sukcesu Meetpointa leżą tutaj w całości — na długo przed tym, zanim będzie co mierzyć.

## Kryteria sukcesu

Spisane **2 września 2026** w dokumencie wymagań MVP, zanim powstał pierwszy ekran produktu. Poniżej w brzmieniu z tamtego dokumentu:

> **Okno oceny: 8 tygodni** od wysłania zaproszenia grupie.
>
> **Sukces** — oba warunki naraz:
>
> - W ostatnich **3 tygodniach** okna **nie powstała ani jedna ankieta treningowa na Messengerze**.
> - Co najmniej **7 z 10** członków zadeklarowało udział w minimum jednym treningu.
>
> **Warunki wspierające** (nie decydują, ale informują):
>
> - Przynajmniej jedna osoba **inna niż autor** utworzyła trening — produkt nie stał się kolejnym wąskim gardłem na jednej osobie.
> - Odbył się co najmniej jeden trening, w którym uczestnicy wykonywali **co najmniej dwa różne plany** — rdzeń produktu został realnie użyty.
>
> **Porażka:** po 8 tygodniach grupa nadal umawia się na Messengerze → **zatrzymujesz dokładanie funkcji** i wracasz do pytania, dlaczego. Nie budujesz mapy, statystyk ani kolejnych sportów w nadziei, że „jeszcze jedna funkcja" to odwróci.

### Jak to będzie mierzone

To jest pierwsze pytanie, jakie tu padnie, więc odpowiadam od razu:

- **„Ani jedna ankieta treningowa na Messengerze"** — obserwacja wątku grupy. Ankieta to każda wiadomość ustalająca kto, kiedy i gdzie biegnie, niezależnie od formy.
- **„7 z 10 zadeklarowało udział"** — z bazy aplikacji: liczba osób z co najmniej jedną deklaracją w oknie.
- **Publikuję agregaty.** Żadnych zrzutów ekranu z prawdziwymi imionami, nazwą grupy ani treścią planów.

Przez całe osiem tygodni nie naprawiam nic w locie i nikogo nie popycham do użycia aplikacji. Publiczny licznik kusi, żeby ratować wynik dopingowaniem ekipy — to niszczy pomiar.

Test idzie na mojej własnej grupie i ma to wbudowaną słabość, którą wolę nazwać teraz niż tłumaczyć później: kumple wybaczą tarcie, którego obca grupa nie wybaczy. Obca grupa to drugie okno, po tym.

## Zasada zmiany kryteriów

Kryteria mogą się zmienić wyłącznie **przed startem licznika** i wyłącznie razem z wpisem w dzienniku mówiącym, co i dlaczego. Po wysłaniu zaproszenia grupie nie zmieniam ich w żadnym wypadku — również wtedy, gdy będzie widać, że wynik idzie źle.

„Z góry" nie znaczy „niezmienne od pierwszego dnia". Znaczy: nie ruszam poprzeczki, kiedy już widzę wynik. Historia zmian tego pliku pilnuje tego lepiej niż moje słowo.

## Dziennik

Jeden wpis tygodniowo, w niedzielę: stan, decyzja tygodnia, co dalej.

- [`dziennik/`](dziennik/)

## Stan

Aktualny — w ostatnim wpisie dziennika. Ośmiotygodniowe okno testu **jeszcze nie ruszyło**; ten licznik startuje w dniu, w którym grupa dostaje zaproszenie, i od tego dnia wpisy zmieniają się w tabelę tygodniową.
