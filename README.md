# FXszama na mieście

Kuchnie od A do Z: raz w miesiącu losujesz literę, wybierasz kraj na tę literę i idziesz w Warszawie do restauracji z jego kuchnią.

**Strona:** https://pacy2u.github.io/FXszama_na_miescie/

## Jak działa

- 26 talerzy z literami. Losowanie pomija litery już wykorzystane oraz Q, X i Y (po polsku żaden kraj się tak nie zaczyna).
- Po wyborze kraju dostajesz linki do Google Maps z gotowym zapytaniem dla Warszawy.
- Dziennik zapisuje miesiąc, literę, kraj i restaurację.

## Gdzie są dane

Ta strona jest publiczna, ale nie zawiera żadnych wpisów. Dziennik trafia do:

1. pamięci przeglądarki (zawsze),
2. prywatnego repozytorium `pacy2u/FXszama_dziennik`, plik `wizyty.json`, jeśli w sekcji „Prywatny dziennik” wkleisz token.

Token: GitHub → Settings → Developer settings → Fine-grained tokens → dostęp tylko do `FXszama_dziennik`, uprawnienie **Contents: Read and write**. Token zostaje w przeglądarce, w której go wkleisz.

Całość to jeden plik `index.html`, bez budowania.
