# Data-empires

(English translation below)

Aquest repositori conté les dades utilitzades per a modelar i analitzar les prediccions d'Alexandre Deulofeu: https://www.deulofeu.org/quadre-dels-imperis/.

## Variables

Full "Durada":
- ID: Nombre identificatiu de l'imperi.
- IMPERI: Nom de l'imperi.
- ANY1: Any d'inici de l'imperi / Any d'inici de la fase "Primer procés agressiu".
- ANY2: Any final de la fase "Primer procés agressiu" / Any d'inici de la fase "Depressió".
- ANY3: Any final de la fase "Depressió" / Any d'inici de la fase "Segon procés agressiu i plenitud".
- ANY4: Any final de la fase "Segon procés agressiu i plenitud" / Any d'inici de la fase "Decadència i desaparició".
- ANY5: Any final de la fase "Decadència i desaparició" / Any de desaparició de l'imperi.
- TOTAL: Durada total (anys) de l'imperi.
- ONA: Variable categòrica binària que pren per valor "1" si l'imperi pertany a la primera onada imperialista i "2" si pertany a la segona.

Full "Demografia":
- ID: Nombre identificatiu de l'imperi.
- AREA_1: Àrea (milions de km2) inicial de l'imperi.
- AREA_ME: Àrea (milions de km2) que assoleix l'imperi en l'any de màxima expansió territorial.
- POBL_1: Població (milions d'habitants) inicial de l'imperi
- POBL_ME: Població (milions d'habitants) de l'imperi en l'any de màxima expansió territorial.
- ANY_ME: Any de màxima expansió territorial.

Full "Localització":
- ID: Nombre identificatiu de l'imperi.
- CAP: Nom de la capital de l'imperi en l'any de màxima expansió territorial.
- LAT: Latitud de la capital de l'imperi en l'any de màxima expansió territorial.
- LON: Longitud de la capital de l'imperi en l'any de màxima expansió territorial.
- ALT: Altitud de la capital de l'imperi en l'any de màxima expansió territorial.
- MAR: Variable categòrica binària que pren per valor "0" si la capital no té sortida al mar i "1" si sí que en té.

-----------------------------------------------------------------------------------------------------------------------------

**ENGLISH TRANSLATION**  
This repository contains the data used to model and analyse Alexandre Deulofeu's predictions.

## Variables

"Durada" sheet:
- ID: Empire identification number.
- IMPERI: Name of the empire.
- ANY1: Start year of the empire / Start year of the "First aggressive process" phase.
- ANY2: End year of the "First aggressive process" phase / Start year of the "Depression" phase.
- ANY3: Final year of the phase "Depression" / Starting year of the phase "Second aggressive process and fullness".
- ANY4: Final year of the phase "Second aggressive process and fullness" / Starting year of the phase "Decadence and disappearance".
- ANY5: Final year of the "Decline and Disappearance" phase / Year of the disappearance of the empire.
- TOTAL: Total duration (years) of the empire.
- ONA: Binary categorical variable that takes the value "1" if the empire belongs to the first imperialist wave and "2" if it belongs to the second.

"Demografia" sheet:
- ID: Empire identification number.
- AREA_1: Initial area (million km2) of the empire.
- AREA_ME: Area (million km2) reached by the empire in the year of maximum territorial expansion.
- POBL_1: Initial population (millions of inhabitants) of the empire.
- POBL_ME: Population (millions of inhabitants) of the empire in the year of maximum territorial expansion.
- ANY_ME: Year of maximum territorial expansion.

"Localització" sheet:
- ID: Empire identification number.
- CAP: Name of the capital of the empire in the year of maximum territorial expansion.
- LAT: Latitude of the capital of the empire in the year of maximum territorial expansion.
- LON: Longitude of the capital of the empire in the year of maximum territorial expansion.
- ALT: Altitude of the capital of the empire in the year of maximum territorial expansion.
- MAR: Binary categorical variable that takes the value "0" if the capital is landlocked and "1" if it is.
