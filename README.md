# Robotika - 4HW
Žadintuvas (garsas + užuolaidos)

# Demo video:



# Problem:
Dažniausiai rytais buna labai sunku atsikelti iš lovos. Tai aš pagalvojau kas palengvintu šį procesą.
Akivaizdu - dienos šviesa, tačiau nakti užuolaidos turi būti nuleistos, kadangi lauke šviečia lempos ir
tai trugdo miegui. Šis projektas išsprendžia šias problemas, kadangi užuolaidos prasidaro ryte automatiškai.


# Design:
Šis automatinis žadintuvas ne tik žadina garsu, bet ir automatiškai pradaro užuolaidas. Žadintuvas turi du režymus.
Pirmas režimas: žadintuvo saulės režymas ir antras: pagal tam tikrą nustatytą laiką. Taigi saulės režymas veikimo prinipas yra toks, kad
kai šviesos rezistorius aptinka šviesą (ryte saulė šviečia ryškiau, negu lempos nakti, tai nustatom žemesnį jautrumą, kad šviesos rezistorius reaguotu tik
į saulės šviesą, bet ne į lempas), servo motoras pradaro užuolaidas. Servo gali pasisukti tiktais 150 laipsnių, tai pilnai užuolaidų jis pradaryti negali, tačiau
mums tai nėra svarbu, svarbiausiai yra, kad jis tik truputi pradarytų jas, kad dienos šviesa patektų į vidų. 
Po užuolaidų pradarymo skamba žadintuvas, minučių kieki, po kiek būtent minučių jis suskamba galima nustatyti (po 15, 20, 30 minučių) 
arba jei nustatyta 0 minučių, tada kai tik šviesos rezistorius pajunta saulės šviesą suskamba žadintuvas, tačiau užuolaidos neprasidaro.
Antras žadintuvo režimas yra žadintuvo laiko režymas. Pirmiausiai nustatome kada nuskambės žadintuvas(valandomis, minutėmis ir sekundėmis), 
tada nustatom kada pakils užuolaidos. Žadintuvo skambėjimui naudojau Piezo. Visa informacija 
yra išvedama į lcd ekraną, kontroliavimas vyksta dviejais mygtukais, ekrane dar yra rodoma temperatūra viduj.



# Parts list:
| Quantity | Component              |
| -------- | ---------------------- |
| 1        | Arduino Uno R3         |
| 1        | Lcd ekranas            |
| 1        | Temperatūros jutiklis  |
| 1        | Micro Servo            |
| 1        | Fotorezistorius        |
| 2        | Mygtukai               |
| 1        | Potenciometras         |  
| 2        | 10 kΩ Resistoriai      |
| 1        | 100 Ω Resistorius      |
| 2        | 220 Ω Resistorius      |
| 1        | Piezo                  |

# Design and schematics:
## Design
<img width="800" height="786" alt="Fantabulous Bojo" src="https://github.com/user-attachments/assets/da04ae35-50c2-4c44-8d9a-5881e77d90a0" />

## Schematic of the design
<img width="1944" height="1514" alt="image" src="https://github.com/user-attachments/assets/adf6045f-dd9e-4368-8f1f-c94d51428587" />

# Encountered problems and future improvements:
## Encountered problems
- 
# Future improvements
- Galima pakeistį motoriuką i kitą, kad užuolaidos galėtų pilnai prasidaryti.
- 
