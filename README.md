# 🌦️ Blazor Web App (.NET 8.0 + Blazor Server)

Prosta aplikacja webowa w technologii **Blazor Server**, prezentująca dane pogodowe w sposób interaktywny z możliwością filtrowania i przetwarzania danych na stronie.

---

## 📌 Informacje

- **Autor:** *Patryk Piwnicki*
- **Prowadzący:** mgr inż. Michał Jaroszczuk
- **Grupa:** [SR][17:05]
- **Data:** 23 kwietnia 2025

---

## 🔧 Technologie

- .NET 8.0
- ASP.NET Core Blazor Server
- C#
- Visual Studio 2022

---

## ⚙️ Opis działania

Aplikacja zawiera zmodyfikowaną stronę `Weather.razor`, która:

1. Generuje prognozę pogody na 10 dni.
2. Zlicza liczbę ciepłych dni (powyżej 15°C).
3. Umożliwia filtrowanie wyłącznie ciepłych dni.
4. Pozwala na przywrócenie pełnej listy prognoz.
5. Umożliwia dynamiczne filtrowanie prognoz po opisie pogody.

Wszystko renderowane jest interaktywnie po stronie serwera przy użyciu komponentów Blazor.

---

## 🌲 Drzewo projektu

![image](https://github.com/user-attachments/assets/c23dc995-f98e-41ac-8e79-b5efb3b6631e)

---

## 🌍 Widok aplikacji

![image](https://github.com/user-attachments/assets/88bad281-12bf-4a51-b232-8e39799307a2)

---

## 🔍 Kluczowe fragmenty kodu

**Weather.razor**

Komponent zawierający logikę:
- generowania prognozy i liczenia ciepłych dni
  ![image](https://github.com/user-attachments/assets/07cd52bf-49e6-4922-95b6-dc8f8cada779)
  ![image](https://github.com/user-attachments/assets/68b55905-6f40-4b56-b9d1-8eafcfed7389)
- filtrowania ciepłych dni i przywracania wszystkich prognóz
  ![image](https://github.com/user-attachments/assets/28fce9ff-ba5b-4f13-9cdb-c1bc238baefa)
  ![image](https://github.com/user-attachments/assets/ad6a2e0e-5e1b-4879-8a1d-a8417c1f2f76)
- dynamicznego filtrowania prognóz po opisie:
  ![image](https://github.com/user-attachments/assets/5eaa5a4b-9389-461e-9fc8-7aeeb126e20d)
  ![image](https://github.com/user-attachments/assets/06d8eb6f-cca3-4b34-b887-ddc94222f3d3)

**Program.cs**

- Konfiguruje serwis Blazor Server i uwierzytelnianie certyfikatowe:
  ![image](https://github.com/user-attachments/assets/7594d1ee-dfec-42ef-8bf0-78d525efefe8)
  ![image](https://github.com/user-attachments/assets/3ae9be80-468c-4adb-b509-bc6515f35706)

---
