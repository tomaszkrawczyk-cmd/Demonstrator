# Asystent AI Act + RODO — demonstrator koncepcyjny

Prywatny, niezależny demonstrator koncepcji asystenta RAG do oceny zgodności
systemów AI z rozporządzeniem (UE) 2024/1689 (AI Act) oraz rozporządzeniem
(UE) 2016/679 (RODO). Autorski projekt przygotowany na potrzeby prezentacji
koncepcyjnej.

**To nie jest oficjalne narzędzie żadnej instytucji publicznej ani jednostki
wojskowej** — wyłącznie prywatny projekt demonstracyjny jednej osoby,
przedstawiany jako propozycja do ewentualnego dalszego rozwoju.

## Co to jest

Lekki interfejs (`demo.html`, ~49 KB) z zewnętrznym korpusem prawnym
ładowanym z plików JSON. Odpowiada na pytania dotyczące AI Act i RODO oraz
ocenia opisane systemy AI pod kątem zgodności z oboma aktami, zawsze
z cytowaniem źródła i rozróżnieniem jego rangi prawnej:

- **artykuł / załącznik** — norma prawna,
- **motyw preambuły** — wykładnia,
- **wytyczne Komisji** — interpretacja niewiążąca.

System retrievalu rozpoznaje tematykę pytania i wykorzystuje synonimy,
co poprawia trafność wyników wyszukiwania w korpusie.

## Struktura plików

| Plik | Zawartość |
|------|-----------|
| `demo.html` | Interfejs użytkownika (~49 KB) |
| `corpus_part1.json` | AI Act — artykuły + załączniki (609 wpisów) |
| `corpus_part2.json` | AI Act — motywy preambuły + wytyczne KE C(2025) 5052 (197 wpisów) |
| `corpus_part3.json` | RODO — motywy + artykuły (389 wpisów) |

## Status

Wersja robocza, przygotowana do celów prezentacyjnych. Streszczenia wytycznych
Komisji są tłumaczeniami/skrótami roboczymi z oryginału w języku angielskim —
wymagają weryfikacji przy każdym poważniejszym zastosowaniu.

## Uruchomienie

Otwórz `demo.html` w przeglądarce (wymaga hostowania pod adresem https://,
nie działa lokalnie z pliku ze względu na CORS). Wymaga klucza API dostawcy
modelu zgodnego z OpenAI API (Groq, OpenRouter i in.) lub lokalnego serwera
(Ollama).

## Autor

Tomasz Krawczyk
www.foodlaw.ai · www.supplemental.pl
