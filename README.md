<div align="center">

# Mushroom Atlas 🍄

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.x-brightgreen?style=for-the-badge&logo=springboot)
![React](https://img.shields.io/badge/React-18.x-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Database](https://img.shields.io/badge/Database-SQL-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-In_Development-orange?style=for-the-badge)

</div>

---

## Wersja Polska

### O projekcie

**Mushroom Atlas** to aplikacja webowa do katalogowania grzybów, stworzona w architekturze **Spring Boot (backend) + React (frontend)**.  
Projekt umożliwia przeglądanie bazy grzybów, wyświetlanie szczegółowych informacji, przepisów oraz dodawanie własnych wpisów przez użytkownika.

Celem projektu było stworzenie pełnego systemu CRUD z nowoczesnym interfejsem, integracją z bazą danych oraz podziałem na warstwy backend / frontend.

### Główne funkcjonalności

* **Katalog grzybów**
  * Lista grzybów w formie kafelków
  * Widok szczegółowy z opisem i zdjęciem
* **System przepisów**
  * Przepisy powiązane z konkretnymi grzybami
* **Grzyby użytkownika**
  * Formularz dodawania nowych grzybów
  * Oddzielna sekcja z wpisami użytkownika
* **Filtrowanie i sortowanie**
  * Po nazwie, kategorii, typie
* **UI / UX**
  * Czarne tło, biały tekst
  * Font Lato
  * Nawigacja zakładkowa
* **Element 3D**
  * Model grzyba obracający się podczas scrollowania strony

### Backend

* **Spring Boot REST API**
* Kontroler: `GrzybController`
* Tabele bazy danych:
  * `grzyb`
  * `przepis`
  * `kategoria`
  * `obrazek`
* Endpointy do:
  * pobierania list
  * pobierania szczegółów
  * dodawania nowych rekordów

### Frontend

* React (SPA)
* Komunikacja z backendem przez REST API
* Widoki:
  * katalog grzybów
  * przepisy
  * formularz dodawania
  * szczegóły grzyba

### Technologie

**Backend:**
* Java
* Spring Boot
* Spring Data JPA
* SQL Database

**Frontend:**
* React
* CSS / Flexbox
* Fetch API / Axios

**Grafika / 3D:**
* Blender (model grzyba)

### Instalacja i uruchomienie

#### Backend (Spring Boot)

1. Otwórz projekt w IntelliJ / Eclipse  
2. Skonfiguruj bazę danych w `application.properties`
3. Uruchom aplikację:

```bash
mvn spring-boot:run
