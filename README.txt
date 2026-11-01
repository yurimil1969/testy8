KARTKÓWKI – instalacja na GitHub Pages

1. Utwórz oddzielne repozytorium, np. kartkowki.
2. Wgraj index.html, style.css, app.js i katalog testy.
3. Settings > Pages > Deploy from a branch > main / (root).
4. Testy wpisuj w testy/lista.txt, po jednej linii: folder|Nazwa widoczna.
5. Każdy folder testu zawiera test.txt i ewentualne obrazy.

FORMAT TESTU:
@ZADANIE ABCD / PF / UZ / LUKI
@WERSJA 1
Treść pytania, opcjonalnie $$LaTeX$$ i ![Opis](rysunek.png)
A: odpowiedź 1
...
POPRAWNA: A
@KONIEC
@WERSJA 2
...
@KONIEC
... aż do wersji 10.
@KONIEC_ZADANIA

W PF stosuj 1: Zdanie | P oraz 2: Zdanie | F, POPRAWNA: PF.
W UZ podaj A:, B:, 1:, 2:, 3:, POPRAWNA: A2.
W LUKI rozdziel treść oraz dwa zdania liniami ---; znaczniki [[AB]] i [[CD]], odpowiedzi A:, B:, C:, D:, POPRAWNA: AD.

UWAGA: MathJax do renderowania LaTeX jest pobierany z internetu.
Odpowiedzi są sprawdzane w przeglądarce, więc nie jest to zabezpieczony system egzaminacyjny.
Strona nie wysyła wyników do serwera. Uczeń widzi wynik procentowy.
