# 🧀 SerAn – Zamów sery kraftowe online

## 📜 Opis projektu
SerAn to prosta i intuicyjna strona internetowa do zamawiania tradycyjnych serów sprowadzanych z gór oraz z Podlasia.
Zamówienia są wysyłane bezpośrednio na podany adres e-mail sprzedawcy (EmailJS).

## 🛒 Menu i ceny

### Sery góralskie
- **Niewędzony mały biały** – 3,50 zł/szt
- **Gałka wędzona** – 22 zł/szt
- **Gałka niewędzona** – 16 zł/szt
- **Pudełko bryndza** – 13 zł/20 dag
- **Korbacze / warkocze** – 8 zł/wiązka
- **Paluchy** – 18 zł/25 dag
- **Bundz** – 70 zł/kg
- **Bundz wędzony** – 75 zł/kg
- **Ser pleśniowy** – 90 zł/kg
- **Proziaki** – 42 zł/kg
- **Żurawina** – 12 zł/słoik

### Sery z Podlasia – 70 zł/kg
- Płatek czosnku, suszony pomidor, szpinak
- Czarnuszka, kozieratka
- Suszony pomidor, bazylia *(ziołowy)*
- Dynia, słonecznik, kozieratka
- Chili
- Orzech włoski, migdał
- Czosnek niedźwiedzi
- Czarnuszka z ziołami
- Pistacja

**Kompozycja własna** – 80 zł/kg

### Nabiał i dodatki
- **Masło wiejskie** – 16 zł/25 dag
- **Twaróg** – 30 zł/kg
- **Śmietana** – 8 zł/400 ml
- **Masło koperkowo-czosnkowe** – 18 zł/25 dag

## 🎯 Funkcje
- Dodawanie/odejmowanie ilości (+/-)
- Automatyczne przeliczanie ceny zamówienia
- Podgląd koszyka
- Formularz wysyłający zamówienie na e-mail (EmailJS)

## 🛠 Technologie
- HTML, CSS, JavaScript (Vanilla)
- EmailJS (wysyłka e-mail bez serwera)

## 🚀 Uruchomienie lokalne
1. Pobierz repozytorium i otwórz `index.html` w przeglądarce.

## 🌍 Publikacja (GitHub Pages)
1. Wejdź w `Settings` → `Pages`
2. Wybierz branch `main` i folder `/ (root)`
3. Zapisz — strona będzie pod `https://<twoja-nazwa-uzytkownika>.github.io/SerAn`

## ✉️ Konfiguracja EmailJS
1. Załóż konto na https://www.emailjs.com
2. Utwórz **Email Service** oraz **Email Template**
3. Skopiuj **Public Key**, **Service ID** i **Template ID**
4. W `index.html` podmień wartości `YOUR_PUBLIC_KEY`, a w `script.js` `YOUR_SERVICE_ID` i `YOUR_TEMPLATE_ID`.

## 📄 Licencja
MIT
