# Audyt wzrostu — BeeSpeaker

**Na żywo:** https://bterzic123.github.io/beespeaker-flow-rebuild-pl/
**Tylko prototyp:** https://bterzic123.github.io/beespeaker-flow-rebuild-pl/?view=proto
**Wersja angielska:** https://bterzic123.github.io/beespeaker-flow-rebuild/ ([repozytorium](https://github.com/bterzic123/beespeaker-flow-rebuild))

BeeSpeaker zadaje każdemu nowemu uczniowi dziewięć pytań: o poziom, cel nauki, najważniejsze tematy i porę nauki. Potem przychodzą dwa ekrany rejestracji i paywall, który dla wszystkich brzmi „Przełam barierę mówienia!”. Ten audyt przebudowuje ekrany między quizem a ceną w designie BeeSpeakera i w cenach BeeSpeakera, tak aby każdy cel dostał własną odpowiedź na ekranie, na którym ludzie podejmują decyzję.

Audyt ma dwa widoki:

- **Przegląd**: co znaleźliśmy, dwie reklamy, które dziś emitujecie na Meta, pięć uszeregowanych pomysłów i potencjalny efekt.
- **Prototyp**: trzy klikalne telefony obok siebie. Dwa to instalacje z Waszych reklam na Meta (zwroty podróżne oraz „nie myśl o gramatyce”), jeden z App Store. Używaj przycisków kroków, przełącznika Jasny / Ciemny albo 30-sekundowego przeglądu, albo klikaj wewnątrz dowolnego telefonu.

## Pięć pomysłów

| # | Pomysł | Dziś | W przebudowie | Oczekiwany efekt |
| :-- | :-- | :-- | :-- | :-- |
| 1 | Proście o konto po starcie okresu próbnego | Rejestracja i zakładanie konta stoją między ekranem ładowania a ceną | Paywall zaraz po ładowaniu; Wasz ekran rejestracji po zakupie | CR +8% · ARPU +17% |
| 2 | Nazwijcie ich cel w nagłówku paywalla | „Przełam barierę mówienia!” dla wszystkich | „Mów po angielsku w podróży od pierwszego dnia” dla podróżnika i znacznik z wybranymi tematami | CR +15–20% |
| 3 | Proście o przypomnienia i mikrofon po starcie okresu próbnego | Prośby o powiadomienia, mikrofon i rozpoznawanie mowy przed ceną | Powiadomienia na ekranie gratulacji, mikrofon przed pierwszą lekcją | CR +10–15% |
| 4 | Niech ekran ładowania odczyta ich odpowiedzi | „AI analizuje Twoje odpowiedzi” z samym procentem | Każda linijka nazywa poziom, cel, tematy i porę nauki | CR +10–15% |
| 5 | Postawcie ocenę obok przycisku okresu próbnego | Brak oceny na paywallu | „4,7 z 9,1 tys. ocen w App Store” i opinia ucznia pod planami | CR +10–15% |

Każde pytanie, które zadajecie dziś, zostaje. Prośba o zgodę na śledzenie zostaje na pierwszym ekranie. Zamknięcie paywalla prowadzi prosto do aplikacji, nigdy do drugiego paywalla.

## Źródła

Ceny i ekrany pochodzą z pierwszego uruchomienia BeeSpeakera na iOS w amerykańskim sklepie: 100 $ rocznie pokazane jako 9 $/mies., 44 $ co 3 miesiące, „Oszczędzasz 43%” oraz $99.99 rocznie z tygodniowym bezpłatnym okresem próbnym na arkuszu zakupu Apple. Teksty na telefonach to nasze tłumaczenie nagranych ekranów. 4,7 z 9,1 tys. ocen to polski App Store (11 listopada 2026). 7 mln+ pobrań i ponad 3000 lekcji pochodzą z beespeaker.com. Opinia i „Trusted by 5M+” pochodzą z Waszego ekranu w aplikacji. Zdjęcia pochodzą z Waszych zrzutów ekranu w App Store. Reklamy pochodzą z Biblioteki reklam Meta według AppMagic.

Zakresy wpływu to oczekiwany efekt według Adapty, na podstawie analiz i testów A/B w aplikacjach subskrypcyjnych, a nie zmierzony wzrost dla BeeSpeakera.

## Uruchomienie lokalne

```bash
python3 -m http.server 8000
```

Potem otwórz http://localhost:8000.

Przygotowane przez Adapty · [Umów demo](https://calendly.com/d/cty4-37z-zqj)
