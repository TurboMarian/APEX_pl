

# APEX

## Cechy urządzenia

- 8 wyjść na wtryskiwacze paliwa
- 8 wyjść sterujących aktywnymi cewkami zapłonowymi
- 8 wyjść AUX uniwersalncyh
- 4 wejścia częstotliwościowe dla czujników VR/HALL
- 12 uniwersalnych wejść analogowych (0-5V) (Wejścia 1-4 mogą być wykorzystane jako wejścia pomiaru temperatury poprzez rezystor podciągający 2,49 kΩ (przełącznik SW10).
- 2 wejścia EGT (termopary typu K)
- 2 wejścia czujników spalania stukowego
- 8 wejść cyfrowych (np czujniki położenia typu HALL, przełączniki, czujniki prędkości, flex fuel, dodatkowe czujniki położenia wałków itp)
- 2 wyjścia H-BRIDGE (6A) (obsługa dwóch elektronicznych przepustnic, elektronicznych zaworów wastegate)
- 2 kontrolery sondy szerokopasmowej LSU 4.9
- 2 Canbus
- wbudowany czujnik ciśnienia 400kPa
- wbudowany czujnik ciśnienia barometrycznego
- wbudowany slot na kartę microSD (logowanie ponad 100 parametrów pracy urządzenia)
- Bluetooth oraz WiFi 


<div align="center">
  <img src="https://github.com/user-attachments/assets/0a5988aa-83cb-4ae6-aedd-f59653917f09" alt="naklejka" width="55%">
</div>


## Firmware


## RUSEFI Firmware
(Right click and 'Save link as...')

<!-- BEGIN LATEST DOWNLOAD BUTTON -->
[![Download zip](https://custom-icon-badges.demolab.com/badge/-RusEFI%20Firmware-blue?style=for-the-badge&logo=download&logoColor=white "Download RusEFI Firmware")]()
<!-- END LATEST DOWNLOAD BUTTON -->

<!-- BEGIN LATEST DOWNLOAD BUTTON -->
[![Download zip](https://custom-icon-badges.demolab.com/badge/-RusEFI%20TunerStudio%20INI-green?style=for-the-badge&logo=download&logoColor=white "Download RusEFI TunerStudio INI")]()
<!-- END LATEST DOWNLOAD BUTTON -->

<!-- BEGIN LATEST DOWNLOAD BUTTON -->
[![Download zip](https://custom-icon-badges.demolab.com/badge/-RusEFI%20Console-purple?style=for-the-badge&logo=download&logoColor=white "Download RusEFI Console")]()
<!-- END LATEST DOWNLOAD BUTTON -->

## FOME Firmware
(Right click and 'Save link as...')

<!-- BEGIN LATEST DOWNLOAD BUTTON -->
[![Download zip](https://custom-icon-badges.demolab.com/badge/-FOME%20Firmware-blue?style=for-the-badge&logo=download&logoColor=white "Pobierz FOME Firmware")]()
<!-- END LATEST DOWNLOAD BUTTON -->

<!-- BEGIN LATEST DOWNLOAD BUTTON -->
[![Download zip](https://custom-icon-badges.demolab.com/badge/-FOME%20TunerStudio%20INI-green?style=for-the-badge&logo=download&logoColor=white "Download FOME TunerStudio INI")]()
<!-- END LATEST DOWNLOAD BUTTON -->

<!-- BEGIN LATEST DOWNLOAD BUTTON -->
[![Download zip](https://custom-icon-badges.demolab.com/badge/-FOME%20Console-purple?style=for-the-badge&logo=download&logoColor=white "Download FOME Console")]()
<!-- END LATEST DOWNLOAD BUTTON -->



### PINOUT

<div align="center">
<a href="https://opelpanfan.github.io/OPF_ECU/core48_21.html" target="_blank">
  <img src="https://github.com/user-attachments/assets/0e97f710-793b-4ef5-b470-bfc47e76c5db" alt="black" width="100%" />

</a>
</div>

| Number Pinu (szary) | STM32 | Funkcja                     |     | Number Pinu (czarny) | STM32 | Funkcja                          |
| ---                 | ---   | ---                         | --- | ---                  | ---   | ---                              |
| A1                  |       | WTRYSKIWACZ 1                     |-------| D1                   |       | WEJŚCIE CYFROWE 1        |
| A2                  |       | WTRYSKIWACZ 2                     |       | D2                   |       | CAN 1 L                  |
| A3                  |       | WTRYSKIWACZ 3                     |       | D3                   |       | CAN 1 H                  |
| A4                  |       | WTRYSKIWACZ 4                     |       | D4                   |       | VR1+/HALL                |
| A5                  |       | WTRYSKIWACZ 5                     |       | D5                   |       | VR1-                     |
| A6                  |       | WTRYSKIWACZ 6                     |       | D6                   |       | VR2+/HALL                |
| A7                  |       | WTRYSKIWACZ 7                     |       | D7                   |       | VR2-                     |
| A8                  |       | WTRYSKIWACZ 8                     |       | D8                   |       | +12V ZASILANIE           |
| B1                  |       | WYJŚCIE AUX 1 (5A)                |       | E1                   |       | H-BRIDGE 2 -             |
| B2                  |       | WYJŚCIE AUX 2 (5A)                |       | E2                   |       | H-BRIDGE 2 +             |
| B3                  |       | WYJŚCIE AUX 3 (5A)                |       | E3                   |       | WEJŚCIE CYFROWE 2        |
| B4                  |       | WYJŚCIE AUX 4 (5A)                |       | E4                   |       | CAN 2 L                  |
| B5                  |       | WYJŚCIE AUX 5 (5A)                |       | E5                   |       | CAN 2 H                  |
| B6                  |       | WYJŚCIE AUX 6 (5A)                |       | E6                   |       | WEJŚCIE ANALOGOWE 1 (0-5V)     |
| B7                  |       | H-BRIDGE 1 -                      |       | E7                   |       | WEJŚCIE ANALOGOWE 2 (0-5V)     |
| B8                  |       | H-BRIDGE 1 +                      |       | E8                   |       | +5V ZASILANIE CZUJNIKÓW        |
| C1                  |       | CEWKA 1                           |       | F1                   |       | WEJŚCIE ANALOGOWE 3 (0-5V)     |
| C2                  |       | CEWKA 2                           |       | F2                   |       | WEJŚCIE ANALOGOWE 4 (0-5V)     |
| C3                  |       | CEWKA 3                           |       | F3                   |       | WEJŚCIE ANALOGOWE 5 (0-5V)     |
| C4                  |       | CEWKA 4                           |       | F4                   |       | WEJŚCIE ANALOGOWE 6 (0-5V)     |
| C5                  |       | CEWKA 5                           |       | F5                   |       | WEJŚCIE ANALOGOWE 7 (0-5V)     |
| C6                  |       | CEWKA 6                           |       | F6                   |       | WEJŚCIE ANALOGOWE 8 (0-5V)     |
| C7                  |       | CEWKA 7                           |       | F7                   |       | WEJŚCIE ANALOGOWE 9 (0-5V)     |
| C8                  |       | CEWKA 8                           |       | F8                   |       | GND                         |

      
<div align="center">
  <img src="https://github.com/user-attachments/assets/754b5384-3ff9-43f3-93fb-265ce7787895" alt="naklejka" width="55%">
</div>


## PCB Layout

<div align="center">
  <img src="https://github.com/user-attachments/assets/6b73b7d4-867f-4398-a5b6-4b52e0a0de97" alt="naklejka" width="100%">
</div>





