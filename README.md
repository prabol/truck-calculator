# 🚛 Kalkulator Tras dla Pojazdów Ciężarowych

Aplikacja internetowa do obliczania dystansów i opłat drogowych dla tras ciężarowych.

## 🌐 Live Demo
**[Użyj aplikacji online →](https://twoja-nazwa.github.io/truck-route-calculator/)**

## ✨ Funkcjonalności

### 📊 Obsługa plików CSV
- Import danych z Excel (po konwersji na CSV)
- Automatyczna konwersja polskiego formatu CSV
- Inteligentny parser dla różnych separatorów

### 🗺️ Różne API tras
- **Symulacja** - realistyczne dane bez kluczy API
- **TomTom Routing API** - 2,500 bezpłatnych zapytań/miesiąc
- **OpenRouteService** - 2,000 zapytań dziennie za darmo

### 🚚 Parametry ciężarówek
- Konfiguracja masy, wymiarów (wysokość, szerokość, długość)
- Uwzględnienie ograniczeń dla pojazdów ciężarowych
- Specialized routing dla HGV (Heavy Goods Vehicle)

### 📈 Wyniki i eksport
- Szczegółowe wyniki z dystansami i opłatami
- Czas podróży dla tras API
- Eksport zaktualizowanego CSV z wynikami

## 🛠️ Technologie
- **Frontend:** Vanilla JavaScript + Tailwind CSS
- **APIs:** TomTom, OpenRouteService
- **Hosting:** GitHub Pages (darmowy, HTTPS)

## 📋 Jak używać

1. **Przygotuj dane:**
   - Otwórz Excel z trasami
   - Zapisz jako: CSV UTF-8 (rozdzielany przecinkami)

2. **Wczytaj do aplikacji:**
   - Kliknij "Wybierz plik CSV"
   - Lub użyj "Załaduj dane testowe"

3. **Wybierz API:**
   - Symulacja (działa bez konfiguracji)
   - TomTom/OpenRouteService (wymaga klucza API)

4. **Oblicz trasy:**
   - Kliknij "Oblicz trasy"
   - Poczekaj na wyniki

5. **Pobierz wyniki:**
   - Kliknij "Pobierz zaktualizowany plik CSV"

## 🔧 API Setup (opcjonalnie)

### TomTom API
1. Zarejestruj się: https://developer.tomtom.com/
2. Utwórz aplikację i skopiuj klucz API
3. Limit: 2,500 zapytań/miesiąc za darmo

### OpenRouteService
1. Zarejestruj się: https://openrouteservice.org/dev/
2. Utwórz token API
3. Limit: 2,000 zapytań/dzień za darmo

## 💡 Wskazówki

### Problem z plikiem CSV?
- Użyj przycisku "Napraw plik CSV"
- Automatycznie konwertuje polski format Excel

### Brak wyników API?
- Sprawdź klucz API
- Sprawdź limity zapytań
- Użyj trybu symulacji jako fallback

### Chcesz więcej tras?
- Symulacja: unlimited
- API: sprawdź limity na stronach dostawców

## 📊 Przykładowe trasy
Aplikacja zawiera dane testowe z trasami:
- Hamburg → Heilbronn (520 km)
- Huegelsheim → Ploiești (1,450 km)
- Hull → Ploiești (2,150 km)
- Ter Apelkanaal → Ploiești (1,680 km)

## 🤝 Contributing
Projekt jest open-source. Pull requesty i issues mile widziane!

## 📄 Licencja
MIT License - możesz używać i modyfikować swobodnie.

---
**Aplikacja hostowana na GitHub Pages | Bezpłatna i open-source**
