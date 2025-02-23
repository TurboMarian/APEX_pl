

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

      


## PCB Layout

<div align="center">
  <img src="https://github.com/user-attachments/assets/6b73b7d4-867f-4398-a5b6-4b52e0a0de97" alt="naklejka" width="100%">
</div>

## WIDEBAND PINOUT

<table>
  <tr>
    <td>
      <div align="left">
        <img src="https://github.com/user-attachments/assets/b496d4ea-cc52-464d-8e90-a2e83be1d03b" alt="naklejka" width="70%">
      </div>
    </td>
    <td align="center">
      <strong>WIDEBAND 1:</strong><br><br>
      1 - LSU PIN 4<br>
      2 - LSU PIN 6<br>
      3 - LSU PIN 2<br>
      4 - LSU PIN 5<br>
      5 - LSU PIN 1<br>
      <br><strong>LSU PIN 3 - CONNECT TO SWITCHED +12V WITH 5A FUSE</strong>
    </td>
    <td align="center">
      <strong>WIDEBAND 2:</strong><br><br>
      1 - LSU PIN 4<br>
      2 - LSU PIN 6<br>
      3 - LSU PIN 2<br>
      4 - LSU PIN 5<br>
      5 - LSU PIN 1<br>
      <br><strong>LSU PIN 3 - CONNECT TO SWITCHED +12V WITH 5A FUSE</strong>
    </td>
  </tr>
</table>

## LSU 4.9 CONNECTOR

<div align="left">
        <img src="https://github.com/user-attachments/assets/5913830f-605d-4a51-9635-8c93a41e3664" alt="naklejka" width="65%">
      </div>

## EGT/ANALOG/KNOCK/USB/DIGITAL/AUX CONNECTORS

<table>
  <tr>
    <td>
      <div align="left">
        <img src="https://github.com/user-attachments/assets/8e5822b1-3525-4df8-8b20-5a3d4dfbc909" alt="VR" width="105%">
      </div>
    </td>
    <td align="center">
      <strong>VR:</strong><br><br>
      1 - VR3-<br>
      2 - VR3+<br>
      3 - VR4-<br>
      4 - VR4+
    </td>
    <td align="center">
      <strong>EGT:</strong><br><br>
      1 - K+<br>
      2 - K-<br>
      3 - K1+<br>
      4 - K1-
    </td>
    <td align="center">
      <strong>ANALOG IN:</strong><br><br>
      1 - ANALOG INPUT 10<br>
      2 - ANALOG INPUT 11<br>
      3 - ANALOG INPUT 12<br>
      4 - NOT USED
    </td>
    <td align="center">
      <strong>KNOCK:</strong><br><br>
      1 - KNOCK SENSOR 1<br>
      2 - KNOCK SENSOR 2<br>
      3 - KNOCK AUDIO OUTPUT 1<br>
      4 - KNOCK AUDIO OUTPUT 2
    </td>
    <td align="center">
      <strong>USB:</strong><br><br>
      1 - VBUS<br>
      2 - D-<br>
      3 - D+<br>
      4 - GND
    </td>
    <td align="center">
      <strong>DIGITAL IN:</strong><br><br>
      1 - DIGITAL IN 3<br>
      2 - DIGITAL IN 4<br>
      3 - DIGITAL IN 5<br>
      4 - DIGITAL IN 6
    </td>
    <td align="center">
      <strong>DIGITAL IN/AUX:</strong><br><br>
      1 - DIGITAL IN 7<br>
      2 - DIGITAL IN 8<br>
      3 - AUX 7<br>
      4 - AUX 8
    </td>
  </tr>
</table>



## SPI5 CONNECTOR
<table>
  <tr>
    <td>
      <div align="left">
        <img src="https://github.com/user-attachments/assets/ea6489d2-817d-4648-8d05-b27e5785b4d7" alt="SPI5" width="50%">
      </div>
    </td>
    <td align="center">
      <strong>SPI5:</strong><br><br>
      1 - SPI5 SCK<br>
      2 - SPI5 MISO<br>
      3 - SPI5 MOSI<br>
      4 - SPI5 CS1 (PF10)<br>
      5 - SPI5 CS2 (PF5)
    </td>
  </tr>
</table>

<table>
  <tr>
    <td>
      <div align="left">
        <img src="https://github.com/user-attachments/assets/9d346c36-0cd5-4926-82a2-080b6bc4a592" alt="VR" width="50%">
      </div>
    </td>
    <td align="center">
      <strong>VR:</strong><br><br>
      1 - VR3-<br>
      2 - VR3+<br>
      3 - VR4-<br>
      4 - VR4+
    </td>
  </tr>
</table>


<div align="center">
  <img src="https://github.com/user-attachments/assets/754b5384-3ff9-43f3-93fb-265ce7787895" alt="naklejka" width="55%">
</div>









