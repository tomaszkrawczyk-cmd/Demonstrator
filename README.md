# Asystent AI Act — demonstrator koncepcyjny

Prywatny, niezależny demonstrator koncepcji asystenta RAG do oceny zgodności
systemów AI z rozporządzeniem (UE) 2024/1689 (AI Act). Autorski projekt
przygotowany na potrzeby prezentacji koncepcyjnej.

**To nie jest oficjalne narzędzie żadnej instytucji publicznej ani jednostki
wojskowej** — wyłącznie prywatny projekt demonstracyjny jednej osoby,
przedstawiany jako propozycja do ewentualnego dalszego rozwoju.

## Co to jest

Jednoplikowy demonstrator (`demo.html`) z wbudowanym korpusem pełnego tekstu
urzędowego AI Act (artykuły, załączniki, wszystkie motywy preambuły) oraz
oznaczonymi streszczeniami roboczymi wytycznych Komisji Europejskiej
C(2025) 5052. Odpowiada na pytania o AI Act oraz ocenia opisane systemy AI,
zawsze z cytowaniem źródła i rozróżnieniem jego rangi prawnej (norma / wykładnia /
interpretacja niewiążąca).

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
