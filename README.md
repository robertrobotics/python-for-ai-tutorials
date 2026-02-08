# 🐍 Kurs Pythona od Zera — dla Developerów AI

Witaj w kompletnej ścieżce nauki języka Python, przygotowanej specjalnie dla przyszłych inżynierów AI i Machine Learning. Kurs składa się z **10 odcinków** w formie interaktywnych Jupyter Notebooków, które poprowadzą Cię od absolutnych podstaw składni aż po asynchroniczność, dekoratory i pracę z ekosystemem AI/ML.

> 🎥 **Kurs jest dostępny również w formie wideo na YouTube!**
> Każdy odcinek ma odpowiadający mu film z dokładnym omówieniem kodu.

---

## 📚 Spis Treści

### Część 1: Fundamenty

| # | Temat | Czego się nauczysz |
|---|-------|---------------------|
| **01** | [🐍 Fundamenty Pythona](./01-fundamenty-pythona/lekcja.ipynb) | Zmienne, typy danych (`int`, `float`, `str`, `bool`, `None`), operatory, f-stringi, `print()` / `input()`, konwersja typów. |
| **02** | [🔀 Struktury Sterujące](./02-struktury-sterujace/lekcja.ipynb) | `if`/`elif`/`else`, pętle `for` i `while`, `range()`, `enumerate()`, `zip()`, `break`/`continue`/`pass`, list comprehensions. |
| **03** | [🔧 Funkcje](./03-funkcje/lekcja.ipynb) | Definiowanie funkcji, argumenty pozycyjne i nazwane, `*args`/`**kwargs`, wartości zwracane, zakres zmiennych, funkcje lambda, docstringi. |

### Część 2: Poziom Średniozaawansowany

| # | Temat | Czego się nauczysz |
|---|-------|---------------------|
| **04** | [🏗️ Programowanie Obiektowe](./04-oop/lekcja.ipynb) | Klasy i obiekty, atrybuty i metody, dziedziczenie, enkapsulacja, polimorfizm, metody specjalne (dunder methods). |
| **05** | [⚠️ Obsługa Błędów](./05-obsluga-bledow/lekcja.ipynb) | Wyjątki `try`/`except`/`else`/`finally`, tworzenie własnych wyjątków, best practices, debugowanie. |
| **06** | [📁 Praca z Danymi](./06-praca-z-danymi/lekcja.ipynb) | Pliki tekstowe, format JSON, przetwarzanie CSV, `pathlib`, kodowanie znaków. |

### Część 3: Techniki Zaawansowane

| # | Temat | Czego się nauczysz |
|---|-------|---------------------|
| **07** | [📦 Moduły i Pakiety](./07-moduly-pakiety/lekcja.ipynb) | Moduły i pakiety, style importów, środowiska wirtualne, `pip`, organizacja projektu. |
| **08** | [✨ Magia Pythona](./08-dekoratory-generatory/lekcja.ipynb) | Dekoratory, generatory (przetwarzanie dużych danych bez zużycia RAM), menadżery kontekstu (`with`). |
| **09** | [⏱️ Async/Await](./09-async-await/lekcja.ipynb) | Współbieżność vs równoległość, `async`/`await`, `asyncio`, równoczesne wykonywanie wielu zadań. |
| **10** | [🤖 Ekosystem AI/ML](./10-ekosystem-ai-ml/lekcja.ipynb) | NumPy (obliczenia numeryczne), Pandas (analiza danych tabelarycznych), Requests (komunikacja z API). |

---

## 🚀 Jak korzystać z tego kursu?

### Wymagania

- **Python 3.10+**
- **VS Code** z rozszerzeniem [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)
- Menedżer pakietów [uv](https://docs.astral.sh/uv/) (zalecany) lub `pip`

### Instalacja

```bash
# Sklonuj repozytorium
git clone <url-repozytorium>
cd python-tutorials

# Zainstaluj zależności (uv)
uv sync
```

### Praca z lekcjami

1. Otwórz folder projektu w VS Code.
2. Przejdź do wybranego folderu z odcinkiem (np. `01-fundamenty-pythona/`).
3. Otwórz plik `lekcja.ipynb`.
4. Wykonuj komórki kodu po kolei, czytając opisy między nimi.
5. Na końcu każdej lekcji znajdziesz **ćwiczenia praktyczne** — spróbuj je rozwiązać samodzielnie!

> 💡 **Wskazówka:** Każdy odcinek buduje na wiedzy z poprzedniego. Zalecamy przerabianie lekcji po kolei.

---

## 🗺️ Mapa kursu

```
python-tutorials/
├── 01-fundamenty-pythona/     # Zmienne, typy, operatory
├── 02-struktury-sterujace/    # if/else, pętle, comprehensions
├── 03-funkcje/                # Funkcje, lambda, *args/**kwargs
├── 04-oop/                    # Klasy, dziedziczenie, polimorfizm
├── 05-obsluga-bledow/        # try/except, własne wyjątki
├── 06-praca-z-danymi/         # Pliki, JSON, CSV, pathlib
├── 07-moduly-pakiety/         # Importy, venv, organizacja projektu
├── 08-dekoratory-generatory/  # Dekoratory, generatory, context managers
├── 09-async-await/            # asyncio, współbieżność
├── 10-ekosystem-ai-ml/        # NumPy, Pandas, API
├── pyproject.toml
└── README.md
```

---

## 📄 Licencja

Projekt edukacyjny. Korzystaj, ucz się i dziel się wiedzą!
