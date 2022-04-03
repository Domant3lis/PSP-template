---
Author: Vardenis Pavardenis
---

# Užduotis
Parašyti Deque realizaciją ir kartu įgyvendinti šį funkcionalumą:

- Sukurti tuščią deką
- Patikrinti, ar dekas tuščias
- Patikrinti, ar dekas pilnas
- Įterpti naujus duomenis (naują elementą) į deko pradžią
- Išimti elementą iš deko pradžios (gaunami elemento duomenys)
- Įterpti naujus duomenis (naują elementą) į deko pabaigą
- Išimti elementą iš deko pabaigos (gaunami elemento duomenys)
- Gauti deko pradžios elemento duomenis, neišimant jo iš deko (nebūtina oper.)
- Gauti deko pabaigos elemento duomenis, neišimant jo iš deko (nebūtina oper.)
- Gauti deko elementų skaičių (nebūtina operacija)
- Sunaikinti deką

# Prognozė

## Eilučių skaičius 

|             |  main.c  |  kitas.c  |
|  ---        |  ---     |  ---      |
|  Numatyta   |  X       |  X        |
|  Reali      |  Y       |  Y        |

## SVS
|  |  Projektavimas  |  Kodavimas  |  Testavimas  |   Klaidų taisymas  |  Atsiskaitymas  |  PSP  |  Kita  |  Viso  |
|  ---       |  ---  |  ---  |  ---  |  ---  |  ---  |  ---  |  ---  |  ---  |
|  Numatyta  |  X  |  X  |  X  |  X  |  X  |  X  |  X  |  X  |
|  Reali     |  Y  |  Y  |  Y  |  Y  |  Y  |  Y  |  Y  |  Y  |

# PSP Lentelė

|  Data  |  Nuo   |  Iki   |  Trukdžiai  |  Laikas  |  Veikla  |  Komentarai ir problemos  |  Vnt. (LoC)  |
|  ----  |  ----  |  ----  |  ----  |  ----  |  ----  |  ----  |  ---:  |
|  |  12:00 |  13:00  |  15 ~kavutė~  |  45  |  Projektavimas  |  Paskaičiau wikipediją  |  0  |
|  |  13:00 |  13:05  |  -  |  5  |  Kodavimas  |  Pradėjau  |  0  |
|  |  13:05 |  13:10  |  -  |  5  |  Testavimas  |  atrasta klaida #1  |  0  |
|  |  13:10 |  13:15  |  -  |  5  |  Klaidų taisymas  |  ištaisyta klaida #1  |  0  |

# Defektų lentelė

|  Data  |  Nr.  |  Tipas  |  Padarytas fazėje  |  Pašalintas fazėje  |  Taisymo laikas  |  Aprašas  |  Sprendimas  |
|  ----  |  ---  |  -----  |  ---  |  ---  |  ---  |  ---  |  ---  |
|  04-20  |  1  |  Funkcionalumas  |  Kodavimas  |  Klaidų taisymas  |  5  |  Pamiršau main'ą  |  Padariau main'ą  |

# Defektų standartas
|  Tipo pavadinimas     |  Aprašas  |
|  -------------------  |  -------  |
|  Funkcionalumas       |  Logika, rodyklės, ciklai, rekursija, skaičiavimai, funkcionalumo defektai  |
|  Testo klaida         |  Testas neatitinka reikalavimų  |
|  Atminties tvarkymas  |  Bandomai nuskaityti iš atlaisvintos atminties arba ji išvis neatlaisvinama  |
