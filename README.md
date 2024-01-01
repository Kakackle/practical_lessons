# A collection of practical lessons / notes from projects / topics learned

# 2023

## General project / direction - choosing / following

### When learning a new framework (web or otherwise)

Najlepszym sposobem nauki nowego frameworku, czyli defacto, jak ten system działa, jak się go pisze, jakie ma ograniczenia, założenia, oczekiwany schemat działania, organizacji zasobów - jest tworzenie projektów, obejmujących większość tych aspektów / w jaki sposób łączyć elementy / funkcje i zaimplementować jakąś funkcjonalność.

Pytanie jest zawsze jakie projekty wybierać

#### Kwestia doboru projektów / jeśli jest to web framework
1. Bardzo prosty projekt uwzględniający podstawy - todo etc - żeby działało, żebyś wiedział cokolwiek
2. Prosty blog - user, database, CRUD, relacje
3. Projekt średniej wielkości

Oczywiście chciałbyś by był to jakiś projekt bardziej wymagający, z większą ilością relacji między elementami, polami w bazie danych, spełniał jakieś realne zadanie, był przydatny, ale i używalny, wygodny, przyciski przenosiły łatwo, kompletny, wiele opcji rozważonych.

I tutaj **pierwsza uwaga: YAGNI**, a mianowicie: 
- czy naprawdę potrzebujesz tych wszystkich funkcjonalności?
- czy muszą być tak kompletne, czy nie wystarczy by były jedynie reprezentacją?
- czy muszą być we wszystkich miejscach, takie powtórki, nakładanie sobie roboty?
- czy nie da się tego zrealizować prościej?

generalnie ocena: **czy jest to warte czasu, który na to poświęcisz?** - czy może lepiej zająć się czymś nowym

4. **tutaj zaczyna się problem**

Masz już średnio duży projekt, powiedzmy, że potrafisz, ale czujesz, że chciałbyś zrobić coś więcej, masz kolejny pomysł, sprawdzić się czy umiesz / z praktyki wiesz, że trzeba utrwalać

Pytanie jaki projekt wybrać kolejny?

Kusi wybrać podobny, bo wiesz jak już niektóre rzeczy zrobić, ale to nie jest najlepsza droga - dużo czasu - mało zysku. Jasne - następnym razem zrobisz pewne rzeczy lepiej od założeń, bo wiesz już co działało a co nie - ale zastanów się - **czy nie mógłbyś przy okazji nauczyć się czegoś więcej?** Pewnie, uwzględnić te optymalizacje, ale też skupić się na czymś nowym jako serce tego nowego projektu.

**Przykład:**
Jeśli jako pierwszy blog stworzyłeś zaawansowany blog albo sklep albo coś takiego, z wieloma relacjami w bazie, recenzjami/komentarzami, kontami, przechowywaniem wielu plików itd, generalnie natura na podstawie kont itd - może jako centrum drugiego powinieneś postawić coś jak z klonem insta - obsługa zdjęć, filtrów, a może real-time chatów, a może system powiadomień - a reszta jako otoczka - żeby się **rozwijać**, magiczne słowo.

#### generalnie: zastanów się co Ci da, jeśli się podejmiesz, czy nie możesz wyciągnąć więcej

#### Kwestia zachowywania wiedzy

Dokumentacja, dokumentacja, dokumentacja.

A przynajmniej **zorganizowane** notki z projektu.

Z:
- konkretnie opisanym problemem / zadaniem
- konkretnym, z kodem, kontekstem rozwiązaniem
- jakieś sekcje / headingi
- ...