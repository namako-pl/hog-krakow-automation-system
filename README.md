# HOG Chapter Kraków — Official Motorcycle Community Platform

A comprehensive, responsive web service designed and implemented for the Kraków branch of the Harley Owners Group (HOG). The project blends a rugged, motorcycle-inspired aesthetic with modern UX solutions, aiming to integrate chapter members and provide real-time information about upcoming **events**.

## 🏍️ Project Overview

The website serves as the primary information hub for group members and Harley-Davidson enthusiasts. A key design challenge was maintaining consistency with global H-D branding while introducing unique, localized functionalities.

## ✨ Key Features

* **Dynamic Event System**: An interactive calendar and "News" module featuring a custom-built lateral notification system (Sticky Widget).
* **Information Architecture**: A clear structural division into sections: History, Gallery, Event Calendar, and Safety.
* **Interactive Gallery**: A custom Lightbox system allowing users to view high-quality photos from parades and rides without leaving the current page.
* **User Experience (UX)**: 
    * Auto-sliding notifications for anniversary parades.
    * Intuitive modal windows featuring route maps and detailed schedules.
    * Full Responsiveness (Mobile-First Design).

## 🛠️ Tech Stack

* **Frontend**: HTML5, Tailwind CSS (Custom Configuration).
* **Interactions**: Vanilla JavaScript (ES6+).
* **Tools**: Git, GitHub, Image Optimization tools.

## 🏗️ Technical Architecture

**Full Automation & Google Ecosystem Integration**: 
    * **Smart Calendar**: The event schedule synchronizes automatically with Google Calendar. Adding a new event in Google Calendar instantly updates the website.
    * **Dynamic Gallery**: The photo gallery is synced with Google Drive. Adding a new folder to a dedicated Drive directory automatically generates a new gallery on the site.
      
### View State Management
The service implements custom layer logic (`z-index management`), allowing for seamless transitions between page content and multi-level modal windows (e.g., enlarging an image within an already open article).

### Performance & Safety
* **Performance**: Resource loading optimization (Lazy Loading for gallery images).
* **UX Safety**: Implementation of clear safety protocols and messages for large-scale **events** (parades, group column rides).

## 📱 Responsiveness (RWD)

The site is fully optimized for mobile devices, which is crucial for users checking ride routes directly "from the road."
* Adaptive navigation menu.
* Scalable maps and graphics using `object-contain`.
* Touch-friendly interfaces for closing modal windows.

---

## 📸 Project Preview

### Home Page (Hero Section)
![Home Page Preview](https://github.com/namako-pl/hog-krakow-automation-system/blob/main/hero.JPG)

### News & Events Module
![News Section Preview](https://github.com/namako-pl/hog-krakow-automation-system/blob/main/news.JPG)


---
*This project was commissioned by **HOG Chapter Kraków**. Developed as part of a professional portfolio expansion and driven by a passion for the Harley-Davidson brand.*

#Polish version 

# HOG Chapter Kraków — Oficjalny Serwis Społeczności Motocyklowej

Kompletny, responsywny serwis internetowy zaprojektowany i wdrożony dla krakowskiego oddziału Harley Owners Group (HOG). Projekt łączy surową, motocyklową estetykę z nowoczesnymi rozwiązaniami UX, mającymi na celu integrację członków chapteru oraz informowanie o nadchodzących wydarzeniach.

## 🏍️ O Projekcie

Strona służy jako główne centrum informacyjne dla członków grupy oraz pasjonatów marki Harley-Davidson. Kluczowym wyzwaniem projektowym było zachowanie spójności z globalnym brandingiem H-D przy jednoczesnym wprowadzeniu unikalnych, lokalnych funkcjonalności.

## ✨ Główne Funkcje Serwisu

* **Dynamiczny System Wydarzeń**: Interaktywny kalendarz i moduł "Aktualności" z autorskim systemem powiadomień bocznych (Sticky Widget).
* **Architektura Informacji**: Przejrzysty podział na sekcje: Historia, Galeria, Kalendarz Wydarzeń oraz Bezpieczeństwo.
* **Interaktywna Galeria**: System Lightbox umożliwiający przeglądanie wysokiej jakości zdjęć z parad i przejazdów bez opuszczania strony.
* **User Experience (UX)**: 
    * Automatycznie wysuwane powiadomienia o jubileuszowych paradach.
    * Intuicyjne modalne okna z mapami tras i szczegółowymi harmonogramami.
    * Pełna responsywność (Mobile First Design).

## 🛠️ Stack Techniczny

* **Frontend**: HTML5, Tailwind CSS (Custom Configuration).
* **Interakcje**: Vanilla JavaScript (ES6+).
* **Narzędzia**: Git, GitHub, narzędzia do optymalizacji grafik.

## 🏗️ Architektura Rozwiązania

**Pełna automatyzacja i integracja z ekosystemem Google**:
    * **Inteligentny Kalendarz**: Harmonogram wydarzeń synchronizuje się automatycznie z Kalendarzem Google. Każde nowe wydarzenie dodane w kalendarzu pojawia się natychmiast na stronie.
    * **Dynamiczna Galeria**: Galeria zdjęć jest połączona z Dyskiem Google. Wystarczy dodać folder ze zdjęciami do dedykowanego katalogu na Drive, aby strona sama zaktualizowała zasoby zdjęciowe.
      
### Zarządzanie Stanem Widoku
W serwisie zaimplementowano niestandardową logikę warstw (`z-index management`), która pozwala na płynne przechodzenie między treścią strony a wielopoziomowymi oknami modalnymi (np. powiększanie zdjęcia wewnątrz otwartego już artykułu).

### Bezpieczeństwo i Wydajność
- **Performance**: Optymalizacja ładowania zasobów (Lazy Loading zdjęć w galeriach).
- **UX Safety**: Implementacja czytelnych komunikatów dotyczących bezpieczeństwa podczas **wydarzeń** masowych (parady, przejazdy kolumnowe).

## 📱 Responsywność (RWD)

Strona została zoptymalizowana pod kątem urządzeń mobilnych, co jest kluczowe dla użytkowników sprawdzających trasy przejazdów bezpośrednio "z trasy".
* Adaptacyjne menu nawigacyjne.
* Skalowalne mapy i grafiki (`object-contain`).
* Dotykowe interfejsy zamykania okien modalnych.

---

## 📸 Podgląd Projektu

### Strona Główna (Hero Section)
![Podgląd strony głównej](https://github.com/namako-pl/hog-krakow-automation-system/blob/main/hero.JPG)

### Moduł News i Wydarzeń
![Podgląd sekcji aktualności]([link-do-twojego-screena-2.jpg](https://github.com/namako-pl/hog-krakow-automation-system/blob/main/news.JPG))

---
*Projekt zlecony przez **HOG Chapter Kraków**. Stworzony w ramach rozbudowy profesjonalnego portfolio oraz z pasji do marki Harley-Davidson.*
