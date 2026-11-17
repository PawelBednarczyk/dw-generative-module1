# Rama projektu

PROJECT.md jest specyfikacją Twojego produktu. Możesz go przygotować w notebooku, w Builderze albo bezpośrednio w pliku. Każda droga przechodzi tę samą walidację.

Jaka praca: Zespół czyta setki skarg klientów banku dziennie i rozdziela je do sześciu zespołów.
Co oddajemy AI: Zespół, pilność i 1-3 dosłowne fragmenty skargi, które je uzasadniają.
Co zostaje u człowieka: Odpowiedź klientowi, każda decyzja finansowa i każda sprawa bez dowodu w tekście.
Główna szkoda: Pilna skarga o utracie dostępu do pieniędzy trafia do zwykłej kolejki.
Poziom: L2: model wyciąga fakty z jednej skargi, a decyzję podejmują reguły w kodzie. Nie słowa kluczowe, bo nie rozpoznają "zamrozili mi konto" bez słowa "frozen". Nie L3, bo nie potrzebujemy wiedzy spoza skargi.
Statusy odpowiedzi:
- ok: produkt decyduje sam
- to_human: sprawę przejmuje człowiek
- error: jawny błąd zamiast zgadywania
