# Bachelorarbeit „Entwicklung eines Lerndashboard zur Zeitreihenanalyse mit R “ - Daten

## Autor*innen

**Authorin:**
Dieu Linh Pham
Masterstudiengang Wirtschaftsinformatik

**Betreurer:**
Prof. Dr. Martin Spott
Kontaktadresse: Martin.Spott@HTW-Berlin.de

Prof. Dr.-Ing. Ingo Claßen
Kontaktadresse: Ingo.Classen@HTW-Berlin.de

**Institution:**
Hochschule für Technik und Wirtschaft Berlin
ROR: <https://ror.org/01xzwj424>

## Code

Zeitreihenanalyse.Rmd


## Datensatz

hanoi_temp.csv : Temperaturdaten von Hanoi von 01.01.2020 - 01.06-2025

tokyo_temp.csv : Temperaturdaten von Tokyo von 01.01.2020 - 01.06-2025
 
manila_temp.csv : Temperaturdaten von Manila von 01.01.2020 - 01.06-2025

hanoi_w_na.csv : 	Datensatz aus Hanoi mit gezielt eingefügten fehlenden Werten von 01.01.2025 - 30.04.2025

hanoi_w_na1.csv : Weitere Variante mit fehlenden Werten von 01.01-2024 - 31.05.2025

tankerkoenigSoSe2025.csv : stündliche Kraftstoffpreise im Jahr 2023


## Fragenbogen

Umfrage-Link: https://docs.google.com/forms/d/e/1FAIpQLSfkOXPH_UW_TBGEg7UlM7JR5-tzE-JoCKfqcDT04OejclnmNQ/viewform?usp=preview

Anworten und Analyse: in Datei "Course Evaluation (Responses).xlsx" oder unter folgenden Link abrufbar: https://docs.google.com/spreadsheets/d/13laq0_I2temewEeFpi4pCz7jfDxKdFRaqRKdm1HXSGY/edit?usp=sharing 


## Datenzugriff 

hanoi_temp.csv, tokyo_temp.csv, manila_temp.csv:
Diese Datensätze wurden eigenständig am 08.06.2025 direkt von der Website meteostat.net mithilfe der „Export“-Funktion heruntergeladen und umbenannt.

Lizenz: CC BY 4.0 Quelle: Meteostat, https://meteostat.net

hanoi_w_na.csv, hanoi_w_na1.csv:
Ebenfalls am 12.07.2025 über meteostat.net bezogen. Nach dem Herunterladen wurden manuell zufällig ausgewählte Werte bzw. Einträge gelöscht, um den Umgang mit fehlenden Werten (NA) in der Zeitreihenanalyse zu simulieren.

Lizenz: CC BY 4.0 Quelle: Meteostat, https://meteostat.net

tankerkoenigSoSe2025.csv:
Dieser Datensatz basiert auf Daten der tankerkoenig.de. Die Rohdaten wurden von Manu Muttathu und Prof. Dr. Martin Spott vorverarbeitet und bereitgestellt.

Lizenz: CC BY 4.0 Quelle: Tankerkönig, https://tankerkoenig.de

Course Evaluation (Responses).xlsx:
Dieser Datensatz stammt aus einer eigenen Google-Forms-Umfrage.

Der Sheet "Form responses" wurde automatisch von Google Forms erstellt.

Der Sheet "Likert" wurde manuell erstellt, um die Antworten umzukodieren (Likert-Skala) und den Median zu berechnen.

Die vollständige Datei wurde direkt aus Google Sheets exportiert.


## Datenschutz

Alle Umfrageantworten wurden anonym erhoben.

Es werden keine personenbezogenen Daten verarbeitet oder gespeichert.


## Zeitraum

Dashboardentwicklung: Juni-Juli 2025

Die Umfrage wurden am 21.07.2025 bis 29.07.2025 durchgeführt.

Die Datenanalyse fand im 01-03 August 2025 statt.

## Angewendete Software

* RStudio
* Google Forms
* Google Sheets

## Ordnerstruktur & Dateibennenungskonvention

Die Projektdateien wurden lokal im Rahmen der RStudio-Projektdatei `Lerndashboard Zeitreihenanalyse.Rproj` organisiert.

├── Lerndashboard Zeitreihenanalyse.Rproj    # RStudio-Projektdatei
├── Zeitreihenanalyse.Rmd                    # Hauptskript (R Markdown)
├── Course Evaluation (Responses).xlsx       # Umfragedaten
├── hanoi_temp.csv                           # Wetterdaten Hanoi (vollständig)
├── tokyo_temp.csv                           # Wetterdaten Tokyo
├── manila_temp.csv                          # Wetterdaten Manila
├── hanoi_w_na.csv                           # Hanoi mit fehlenden Werten (NA)
├── hanoi_w_na_1.csv                         # Weitere Version mit NA
├── tankerkoenigSoSe2025.csv                 # Kraftstoffpreise (API-Daten)
├── README.md                                # Projektdokumentation inkl. DPM
├── renv/                                    # Abhängigkeiten (R-Packages)
├── renv.lock                                # Snapshot der R-Umgebung
├── rsconnect/                               # Verzeichnis zur Veröffentlichung (Shiny etc.)


## Qualitätssicherungsmaßnahmen



