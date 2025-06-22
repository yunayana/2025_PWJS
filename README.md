# 2025_PWJS – Laboratorium z Programowania w językach skryptowych 

To repozytorium zawiera ćwiczenia i projekt zaliczeniowy z przedmiotu "Programowanie w językach skryptowych".

Strona prezentowana pod adresem GitHub Pages:
👉 [https://yunayana.github.io/2025_PWJS/](https://yunayana.github.io/2025_PWJS/)

# Opis projektu

**Nazwa projektu:** System śledzenia postępów czytelniczych z możliwością oceniania, recenzowania i udostępniania

Projekt to aplikacja/webowa strona inspirowana estetyką i stylem kultowego anime *SoulEater*. Charakterystyczna, dynamiczna i lekko mroczna stylistyka przenika cały interfejs, nadając mu oryginalny, przyciągający wzrok charakter. Wszystkie logotypy zostały wykonane ręcznie.

---

## Cel projektu

Celem jest stworzenie wygodnego i funkcjonalnego systemu do zarządzania własną biblioteką czytelniczą, pozwalającego użytkownikom śledzić postępy w czytaniu, oceniać książki, dodawać recenzje, tworzyć notatki oraz dzielić się opiniami z innymi czytelnikami.

---

## Kluczowe funkcje (wersja początkowa)

1. **Rejestracja i logowanie użytkownika**  
   - Tworzenie konta oraz logowanie, m.in. przez e-mail lub konto Google  
   - Edycja profilu użytkownika  

2. **Zarządzanie listami książek**  
   - Dodawanie książek do trzech list: *Chcę przeczytać*, *Czytam*, *Przeczytane*  
   - Przenoszenie książek pomiędzy listami  

3. **Śledzenie postępów czytania**  
   - Wprowadzanie liczby przeczytanych stron lub procentowego postępu  
   - Wyświetlanie aktualnego stanu czytania  

4. **Wyszukiwanie książek**  
   - Integracja z Google Books API 
   - Wyszukiwanie według tytułu, autora lub ISBN  
   - Dodawanie wybranych książek do biblioteki użytkownika  

5. **Oceny i recenzje**  
   - Ocena książek w skali 1–5  
   - Dodawanie krótkich recenzji  
   - Przeglądanie opinii innych użytkowników  

6. **Zakładki i notatki**   
   - Tworzenie własnych notatek  

7. **Profil użytkownika**  
   - Przegląd list książek z podziałem na statusy  
   - Statystyki czytelnicze (np. liczba przeczytanych książek, średnia ocen)  

8. **Funkcje społecznościowe (opcjonalnie)**  
   - Obserwowanie innych użytkowników  
   - Podgląd ich aktywności czytelniczej  

---


---

## Schemat działania

```
[Użytkownik] → [Wyszukaj książkę] → [Google Books API]
                                     ↓
                        [Wybierz książkę] → [Zapisz dane w bazie]
                                                       ↓
                               [Zarządzanie ocenami, notatkami, postępem]
```

---

**Projekt stawia na połączenie funkcjonalności z unikalną estetyką SoulEater oraz indywidualnym stylem graficznym, aby czytanie i zarządzanie książkami było nie tylko użyteczne, ale i przyjemne wizualnie.**

---


## Uruchomienie projektu

Aby poprawnie uruchomić stronę **lokalnie**, należy:

1. **Uruchomić serwer lokalny**.js, który znajduje się w plikach repozytorium – bez tego niektóre funkcje (np. dynamiczne ładowanie danych) mogą nie działać prawidłowo.

2. Otworzyć stronę w przeglądarce pod adresem, który serwer wyświetli (zazwyczaj `http://localhost:PORT`).


## Autor

*Yana Trotsenko, Grupa 1, nr indeksu: 21232* 

*Programowanie w językach skryptowych – 2025*

---

