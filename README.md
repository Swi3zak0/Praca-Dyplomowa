# Praca-Dyplomowa

## Opis aplikacji
Aplikacja pozwala administratorom przypisywać paczki do kurierów oraz zarządzać ich statusem. Kurierzy mogą przeglądać swoje przypisane paczki, aktualizować ich status na dostarczone lub niedostarczone, a także zgłaszać problemy związane z paczkami, takie jak uszkodzenia. System umożliwia śledzenie stanu paczek na różnych etapach dostawy i ułatwia komunikację między administracją a kurierami.

#### Korzyści z korzystania z aplikacji:
- Efektywność zarządzania: Umożliwia administratorom szybkie i sprawne przypisywanie paczek do kurierów, co przyspiesza proces dostawy.
- Śledzenie paczek: Kurierzy mogą aktualizować status paczek w czasie rzeczywistym, co pozwala na bieżące monitorowanie dostaw.
- Zarządzanie problemami: Kurierzy mogą zgłaszać problemy z paczkami, co ułatwia ich szybkie rozwiązanie.
- Usprawniona komunikacja: Aplikacja wspiera lepszą komunikację między administracją a kurierami, co poprawia ogólną organizację pracy.
- Przejrzystość: Administratorzy mają pełny wgląd w status wszystkich paczek, co pomaga w zarządzaniu i planowaniu.

## Diagram Przypadków Użycia (DPU)
![DPU](https://github.com/Swi3zak0/Praca-Dyplomowa/assets/92025645/849be9ee-9a73-44fd-8e8f-21401fa3ff2d)

## Scenariusze
1. Administrator przypisuje paczki do kuriera
- Administrator loguje się do systemu.
- Przegląda listę paczek oczekujących na przypisanie.
- Wybiera paczkę i przypisuje ją do konkretnego kuriera.
- Kurier otrzymuje powiadomienie o nowej paczce do dostarczenia.
2. Kurier aktualizuje status paczki
- Kurier loguje się do systemu.
- Przegląda listę przypisanych paczek.
- Wybiera paczkę, którą dostarczył.
- Aktualizuje status paczki na "dostarczona".
- Administrator otrzymuje powiadomienie o dostarczeniu paczki.
3. Kurier zgłasza problem z paczką
- Kurier loguje się do systemu.
- Przegląda listę przypisanych paczek.
- Wybiera paczkę, z którą jest problem.
- Zgłasza problem, podając szczegóły awarii.
- Administrator otrzymuje powiadomienie o zgłoszonym problemie.
4. Administrator rejestruje nowego kuriera
- Administrator loguje się do systemu.
- Przechodzi do sekcji zarządzania kurierami.
- Wprowadza dane nowego kuriera.
- System wysyła dane logowania do nowego kuriera.
5. Administrator generuje raport dostaw
- Administrator loguje się do systemu.
- Przechodzi do sekcji raportów.
- Wybiera zakres dat i generuje raport dostaw.
- System wyświetla raport, który można pobrać w formacie PDF lub CSV.

## Projekt Bazy Danych
![BAZA_DANYCH](https://github.com/Swi3zak0/Praca-Dyplomowa/assets/92025645/1814426b-d1b2-4f72-aaa8-00a18c6eca8e)
