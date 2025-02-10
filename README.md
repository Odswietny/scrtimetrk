# scrtimetrk
scrtimetrk (ScreenTimeTrk) to program dla systemu Windows który jest zaprojektowany by ukrycie monitorować czas i na podstawie tego wykonywać ustalone akcje (w celu ograniczenia czasu przed ekranem).

# Jak skonfigurować?
## Otwórz plik `config.ini`:
Zamień HH:MM w wartości `time`, jeśli wartość godziny jest normalnie jednocyfrowa, np. 9:00, wartość godziny musi mieć przed sobą zero, np. 09:00
			Przykłady:
			21:00
			22:00
			21:30
			22:30
			
## W przypadku wartości `action`, możesz ustawić co się stanie po określonym wcześniej czasie.
Akcje:
		0 - nic nie rób
		1 - przypomnienie
		2 - wyloguj
		3 - zamknij system (wyłącz)
		4 - hibernacja (jeśli możliwe)
	
## Uruchom program by rozpocząć działanie.
Polecane: dodaj program do programów startowych:
	Utwórz skrót do pliku scrtimetrk.exe i dodaj go do folderu shell:startup (lub %appdata%\Microsoft\Windows\Start Menu\Programs\Startup)

