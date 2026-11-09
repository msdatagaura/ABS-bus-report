# ABS bus dashboard about GA4
Dashboard, ktorý mal za úlohu zistiť údaje o objednávkach, ktoré boli realizované v CRM a GA4.

## 1. Project Title / Headline
Jednalo sa o projekt,ktorý mal za úlohu zistiť počet objednávok ktoré boli realizované cez CRM  a GA4 a taktiež vyhodnotiť základné metriky z GA4.

## 2. Short Description / Purpose
Na základe dát, ktoré som mala poskytnuté  a následne stiahnuté pomocou https://sqliteonline.com/ som mala odpovedať na nasledovné otázky:
1. Vytvoriť tabuľku objednávok  podľa mesiacov
2. Vytvoriť cards ktoré budú odzrkadľovať počet objednávok a kampaní, ktoré boli organizované cez GA4
3. Zostaviť grafy, ktoré zobrazujú TOP 10 najeefektívnejšie zdroje objednávok z GA4
4. Preskúmať závislosť popularity destinácií podľa mesiacov
5. Spočítať CTR, CA, CPA a ďalšie marketingové KPI
6. Pridať mapový vizuál krajín

## 3. Tech Stack

Dashboard bol vytvorený pomocou nasledujúcich nástrojov:
📊 Power BI Desktop – Tvorba a vizualizácia dashboardov
📂 Power Query – Transformácia dát v Power BI
🧠 DAX - tvorba metrík na vypočítanie priemerov
📂 SQL - sťahovanie údajov z tabuliek
📁 File Format – .pbix (Power BI), .png (obrázky dashboardov), pdf

## 4. Data Source

Dáta boli v súbore, ktorý som musela najprv otvoriť v SQL a následne jednotlivé súbory vo forme .csv stiahnúť.
Dáta obsahovali:

-dáta o id_letiská, názvy letísk
-dáta o id_objednávky a stave objednávky
-dáta o dátume spustenia kampane, zdroj a médium kampane, názvu kampane
-dáta o id_rezervácie letenky, id_rezervácie a o id letiska odkiaľ sa odlietalo a id letiska kam sa prilietalo

## 5. Features / Highlights

Vymedzenie problému:

Dáta ohľadom letísk, kde sa jednotlivé letiská nachádzajú, v akom meste, krajine a kontinente mi chýbali. Taktiež jednotlivé dáta o konverziách, takže mi chýbali pri výpočte marketingových KPI.

Cieľom dashboardu:
1. Poskytnúť marketingovému oddeleniu cenné informácie, ktoré by vedeli aplikovať v ďalšom procese rozhodovania.
2. Vizualizovať jednotlivé mestá a krajín, ktoré sú populárne.
3. Zistiť najefektívnejšie zdroje dát, ktoré prinášajú zákazníkov.

Kľúčové vizualizácie:
1. KPI cards: CPC, Počet klikov, Počet kampaní,Počet objednávok, Počet objednávok cez CRM,Miera zrušenia rezervácií, Počet rezervácií, Počet predaných leteniek,Počet destinácií,Total cost, Priemerné náklady na kampaň
2. Filtre: Typ kampane, Zdroj objednávky, Stav objednávky, Kontinent, Mesiace

## 6. Screenshots 

!<img width="1920" height="1030" alt="ABS-bus" src="https://github.com/user-attachments/assets/e3bb3845-d8f9-45d9-8664-894acf261963" />
<img width="1920" height="1030" alt="ABS-bus4" src="https://github.com/user-attachments/assets/00842c76-a1da-4524-86e9-8337750146a7" />
<img width="1920" height="1030" alt="ABS-bus3" src="https://github.com/user-attachments/assets/191d4c36-8326-4225-afa9-d402112021af" />
<img width="1920" height="1030" alt="ABS-bus2" src="https://github.com/user-attachments/assets/bddaff27-3e9c-4e29-926a-575eda9bf464" />

