# Aktualizacja zastępstw wysyłana na platformie Discord
Bot na platformie Discord udostępnia aktualizacje zastępstw, które pobiera ze strony internetowej korzystającej z usługi [Zastępstwa Optivum firmy VULCAN](https://duckduckgo.com/?t=h_&q=Zast%C4%99pstwa+Optivum+firmy+VULCAN&ia=web).
> Kod bota przystosowany jest do zastępstw [Zepołu Szkół Elektronicznych w Bydgoszczy](https://zastepstwa.zse.bydgoszcz.pl/).

## Konfiguracja kanału aktualizacji
Bot umożliwia administratorom ustawienie dedykowanego kanału, przy pomocy komendy `/skonfiguruj`, na który będą wysyłane aktualizacje. Dzięki temu wszystkie istotne informacje trafią do wybranej grupy użytkowników.

## Filtracja zastępstw
Administratorzy serwera mogą skonfigurować filtrowanie zastępstw, przy pomocy komendy `/skonfiguruj`. Pozwala to na wysyłanie aktualizacji tylko do określonych grup, co pomaga w znalezieniu swoich zastępstw.

## Bezpieczeństwo
Bot, który znajduję się na serwerze, nie będzie działał bez uprzedniego dodania ID serwera do pliku konfiguracyjnego bota. Taką czynność mogą dokonać osoby za pomocą komendy `/zarządzaj`, których ID zostało wcześniej umieszczone własnoręcznie w pliku konfiguracyjnym bota przez administratora kodu. Takie działanie ma zapewnić bezpieczeństwo, niezawodność oraz zapobiegać przeciążeniom bota.

## Przyjazny interfejs
Dzięki wykorzystaniu elementów interfejsu użytkownika Discorda, takich jak selektory, bot oferuje intuicyjny sposób konfiguracji oraz przejrzyste i czytelne zastępstwa, które bot umieszcza na wskazanym wcześniej kanale.

## Przechowywanie konfiguracji
Bot przechowuje konfiguracje serwerów w jednym pliku, co pozwala na łatwe zapisywanie i ładowanie ustawień pomiędzy sesjami. Jest to szczególnie przydatne w przypadku wielokrotnych konfiguracji na różnych serwerach.
