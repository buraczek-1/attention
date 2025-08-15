# Metryki Uwagi w Marketingu Cyfrowym - Strona Internetowa

Profesjonalna strona internetowa prezentująca kompleksowe badanie metryk uwagi w marketingu cyfrowym, z dwujęzyczną obsługą (polski/angielski) i responsywnym designem.

## 🌟 Funkcje

- **Dwujęzyczna obsługa**: Przełączanie między polskim a angielskim
- **Dwie główne sekcje**: Kompleksowy Raport i Pigułka Wiedzy
- **Responsywny design**: Optymalizacja dla desktop, tablet i mobile
- **Klikalny spis treści**: Łatwa nawigacja po dokumencie
- **Profesjonalny design**: Wykorzystuje font Inter (podobny do Google Sans Text)
- **Accessibility**: Wsparcie dla czytników ekranu i nawigacji klawiaturą
- **SEO-friendly**: Optymalizacja dla wyszukiwarek

## 📁 Struktura Plików

```
attention-metrics-website/
├── index.html              # Główny plik HTML
├── css/
│   └── styles.css          # Style CSS z responsywnym designem
├── js/
│   ├── data.js            # Dane treści w obu językach
│   └── app.js             # Główna logika aplikacji
└── README.md              # Ten plik
```

## 🚀 Publikacja na GitHub Pages

### Krok 1: Przygotowanie repozytorium

1. Utwórz nowe repozytorium na GitHub
2. Sklonuj repozytorium lokalnie:
   ```bash
   git clone https://github.com/TWOJA-NAZWA-UŻYTKOWNIKA/NAZWA-REPOZYTORIUM.git
   ```

### Krok 2: Dodanie plików

1. Skopiuj wszystkie pliki z folderu `attention-metrics-website/` do głównego katalogu repozytorium
2. Struktura powinna wyglądać tak:
   ```
   NAZWA-REPOZYTORIUM/
   ├── index.html
   ├── css/
   │   └── styles.css
   ├── js/
   │   ├── data.js
   │   └── app.js
   └── README.md
   ```

### Krok 3: Commit i push

```bash
git add .
git commit -m "Dodanie strony internetowej z badaniem metryk uwagi"
git push origin main
```

### Krok 4: Aktywacja GitHub Pages

1. Przejdź do repozytorium na GitHub
2. Kliknij zakładkę **Settings**
3. Przewiń w dół do sekcji **Pages**
4. W sekcji **Source** wybierz **Deploy from a branch**
5. Wybierz branch **main** i folder **/ (root)**
6. Kliknij **Save**

### Krok 5: Dostęp do strony

Po kilku minutach strona będzie dostępna pod adresem:
```
https://TWOJA-NAZWA-UŻYTKOWNIKA.github.io/NAZWA-REPOZYTORIUM/
```

## 🛠️ Dostosowywanie

### Zmiana treści

Aby zmienić treść strony, edytuj plik `js/data.js`. Struktura danych:

```javascript
const contentData = {
    pl: {  // Treść polska
        report: { sections: [...] },
        summary: { sections: [...] }
    },
    en: {  // Treść angielska
        report: { sections: [...] },
        summary: { sections: [...] }
    }
};
```

### Zmiana stylów

Edytuj plik `css/styles.css` aby dostosować:
- Kolory (zmienne CSS w `:root`)
- Fonty
- Layout i spacing
- Responsywność

### Dodanie nowych funkcji

Główna logika aplikacji znajduje się w `js/app.js`. Możesz dodać:
- Nowe sekcje
- Funkcje wyszukiwania
- Analitykę
- Dodatkowe języki

## 📱 Responsywność

Strona jest w pełni responsywna i dostosowuje się do:
- **Desktop** (1200px+): Pełny layout z bocznym spisem treści
- **Tablet** (768px-1024px): Zwinięty spis treści
- **Mobile** (do 768px): Mobilny layout z ukrytym spisem treści

## 🎨 Paleta Kolorów

- **Główny kolor**: #2563eb (niebieski)
- **Kolor tła**: #ffffff (biały)
- **Kolor powierzchni**: #f8fafc (jasny szary)
- **Tekst główny**: #1e293b (ciemny szary)
- **Tekst pomocniczy**: #64748b (średni szary)

## 🔧 Wsparcie Techniczne

### Wymagania przeglądarki

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

### Funkcje dostępności

- Nawigacja klawiaturą
- Wsparcie dla czytników ekranu
- Wysokie kontrasty
- Responsywny design

## 📄 Licencja

© 2025 Manus AI. Wszelkie prawa zastrzeżone.
Ten raport może być udostępniany i cytowany z odpowiednim przypisaniem.

## 🤝 Wsparcie

Jeśli masz pytania lub problemy z wdrożeniem, sprawdź:
1. [Dokumentację GitHub Pages](https://docs.github.com/en/pages)
2. [Przewodnik HTML/CSS/JavaScript](https://developer.mozilla.org/en-US/docs/Web)

---

**Uwaga**: Strona została zoptymalizowana pod kątem GitHub Pages i nie wymaga dodatkowych narzędzi budowania czy serwera.

