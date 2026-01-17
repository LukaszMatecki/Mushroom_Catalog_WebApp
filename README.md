<div align="center">

# Mushroom Atlas 🍄

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.x-brightgreen?style=for-the-badge&logo=springboot)
![React](https://img.shields.io/badge/React-18.x-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Database](https://img.shields.io/badge/Database-SQL-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Educational-blueviolet?style=for-the-badge)

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
```

Backend działa na:
```arduino
http://localhost:8080
```
#### Frontend (React)
1. Przejdź do folderu frontendu:
```bash
cd frontend
```
2. Zainstaluj zależności:
```bash
npm install
```
3. Uruchom aplikację:
```bash
npm start
```
#### Frontend działa na:
```arduino
http://localhost:3000
```

---

## English Version

## About the Project

**Mushroom Atlas** is a web application for cataloging mushrooms, built with a **Spring Boot backend and React frontend**.  
It allows users to browse mushrooms, view detailed information and recipes, and add their own entries.

The goal of the project was to create a full-stack CRUD system with database integration and a modern, user-friendly interface.

### Key Features

- Tile-based mushroom catalog
- Detailed mushroom view with images and description
- Recipe system linked to specific mushrooms
- User-added mushroom form
- Separate section for user-submitted mushrooms
- Filtering and sorting by name, category, and type
- Dark-themed UI with Lato font
- Tab-based navigation
- 3D rotating mushroom model on scroll

### Backend

- Spring Boot REST API
- Controller: `GrzybController`
- Database tables:
  - `grzyb`
  - `przepis`
  - `kategoria`
  - `obrazek`
- Endpoints for:
  - fetching lists
  - fetching details
  - adding new entries

### Frontend

- React SPA
- Communicates with backend via REST API
- Views include:
  - mushroom catalog
  - recipes
  - add mushroom form
  - detailed mushroom view

### Tech Stack

**Backend:**
- Java
- Spring Boot
- Spring Data JPA
- SQL Database

**Frontend:**
- React
- CSS / Flexbox
- Fetch API / Axios

**3D Assets:**
- Blender

### How to Run

#### Backend

1. Open the project in IntelliJ / Eclipse  
2. Configure the database in `application.properties`  
3. Start the backend server:

```bash
mvn spring-boot:run
```

The backend runs at:
```arduino
http://localhost:8080
```
#### Frontend (React)
1. Navigate to the frontend folder:
```bash
cd frontend
```
2. Install dependencies:
```bash
npm install
```
3. Start the frontend:
```bash
npm start
```
#### The frontend runs at:
```arduino
http://localhost:3000
```




