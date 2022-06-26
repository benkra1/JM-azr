# JM-azr
This is a CSL style for Juris-M, which is in conformity to AZR (Austrian Legal Citation Style)
## Configured types
### Zeitschriften/Journal Articles
#### Type in machine language: `article-journal`
#### Type in natural language: Journal Article/???
#### Fields
German | English | Required? | Example
---|---|---|---
Titel | Title | :white_check_mark:|Neues IT-Recht
? | Publication | :white_check_mark:|ecolex
Autor | Author | :white_check_mark:|Knaipp
Autor | Author | |Zankl
? | Issue |:white_check_mark:|2021
Seiten | Pages |:white_check_mark:|106
#### Remark for using
You can insert a page when adding a citation in Word. This page will be shown in brackets at the end. Adding a first name does not make a difference in displaying the citation.
#### Result
![image](https://user-images.githubusercontent.com/93471400/175359585-caad3f6b-5f34-4b2e-a698-141cb0f6c3e1.png)

### Kommentar (zu Gesetz)/Legal Commentary
#### Type in machine language: `legal_commentary`
#### Type in natural language: Legal Commentary/Gesetzeskommentar
#### Fields
German | English | Required? | Example
---|---|---|---
Titel | Title | :white_check_mark:|Exekutionsordnung
Autor | Author | :white_check_mark:|Schneider
Herausgeber|Editor|:white_check_mark:|Mohr
Ausgabe|Edition||17
? | Date | |2021
Seiten | Pages |:white_check_mark:|§ 1
Kurztitel|Short Title||EO
#### Remark for using
You can insert a page or "Randziffer" when adding a citation in Word. This will be shown after a comma at the end.
#### Result
![image](https://user-images.githubusercontent.com/93471400/175361371-1b216cfe-5c5f-49bc-b201-2af81c324725.png)

### Ganzes Buch/Whole Book
#### Type in machine language: `book`
#### Type in natural language: Buch/Book
#### Fields
German | English | Required? | Example
---|---|---|---
Titel | Title | :white_check_mark:|Bürgerliches Recht
Autor | Author | :white_check_mark:|Perner
Herausgeber|Editor||
Ausgabe|Edition||6
? | Date | |2019
Seiten | Pages ||
Kurztitel|Short Title||
#### Result
![image](https://user-images.githubusercontent.com/93471400/175806787-e2ea4510-16d8-4067-98a1-a37ee48d9319.png)

### Festschrift/Gedenkschrift
#### Type in machine language: `chapter`
#### Type in natural language: Book Section
#### Fields
German | English | Required? | Example
---|---|---|---
Titel | Title | :white_check_mark:|Zum Beginn der Unredlichkeit des Kondiktionsschuldners bei Ausübung von Gestaltungsechten
?|Book Title|:white_check_mark:|FS 200 Jahre ABGB
Autor | Author | :white_check_mark:|Rummel
Herausgeber|Editor|not allowed!|---
? | Date | |2011
Seiten | Pages |:white_check_mark:|20
#### Remark for using
If it is a "Gedenkschrift" instead of FS... you type GedS ...
#### Result
![image](https://user-images.githubusercontent.com/93471400/175367093-09369f5b-af33-4193-ac94-cdbd67b1e373.png)

### Tagungsbände und Buchkapitel
#### Type in machine language: `chapter`
#### Type in natural language: Book Section
#### Fields
German | English | Required? | Example
---|---|---|---
Titel | Title | :white_check_mark:|Hinzurechnung und Anrechnung im neuen Erbrecht
?|Book Title|:white_check_mark:|Gesellschaftsrecht und Erbrecht
Autor | Author | :white_check_mark:|Apathy
Herausgeber|Editor|:white_check_mark:|Rüffler
? | Date | |2016
? | Edition | |2
Seiten | Pages |:white_check_mark:|1
#### Remark for using
Editor is absolutely required as this is the differenciator between FS/GedS and Tagungsbände
#### Result
![image](https://user-images.githubusercontent.com/93471400/175368123-e897f1f2-4531-43ac-9ba9-b712f1a4f0f8.png)


### Gesetz (Österreich)/Law (Austria)
#### Type in machine language: `statute`
#### Type in natural language: Gesetz/Statute
#### Fields for citation of single paragraph
German | English | Required? | Example
---|---|---|---
Titel | Name of Act | :white_check_mark:|Mediengesetz
Kurztitel|Short Title||MedienG
Seiten | Pages |:white_check_mark:|§ 41
Geschichte|History|:white_check_mark:|BGBl I 2020/148
#### Fields for citation of whole legislative act
German | English | Required? | Example
---|---|---|---
Titel | Name of Act | :white_check_mark:|Hass-im-Netz-Bekämpfungs-Gesetz
Kurztitel|Short Title||HiNBG
Geschichte|History|:white_check_mark:|BGBl I 2020/148

#### Remark for using
If you add a page (ie paragraph) either in Juris-M or in Word (permanent or individual page), "idF" will be shown in front of BGBl, because I'm assuming, that you want to cite the current and not the original version of the paragraph.
#### Results
![image](https://user-images.githubusercontent.com/93471400/175363700-3024fba3-f0fc-4a2f-a476-21f573e43639.png)
![image](https://user-images.githubusercontent.com/93471400/175363798-883db8cc-d798-46ba-b264-7ffd4ade6d85.png)

### Richtlinie/Verordnung (Europa)/European Regulation
#### Type in machine language: `statute`
#### Type in natural language: Gesetz/Statute
#### Fields for citation 
German | English | Required? | Example
---|---|---|---
Titel | Name of Act | :white_check_mark:|RL (EG) 2003/88 des Europäischen Parlaments und des Rates vom 4. 11. 2003 über bestimmte Aspekte der Arbeitszeitgestaltung (Arbeitszeit-Richtlinie)
Kurztitel|Short Title||AZ-RL 2003/88
Geschichte|History|:white_check_mark:|ABl L 2003/299, 9
Jurisdiktion|Jurisdiction|:white_check_mark:|European Union-EU.INT
#### Results
![image](https://user-images.githubusercontent.com/93471400/175364893-d3473828-a5f2-4287-9c1d-1ec5fe3f5737.png)

### Österreichische Entscheidungen
#### Type in machine language: `legal_case`
#### Type in natural language: Case
#### Fields for citation (ohne Fundstelle)
German | English | Required? | Example
---|---|---|---
? | Case name| :white_check_mark:|7 Ob 120/04d
?|Court|:white_check_mark:|OGH
?|Date Decided|:white_check_mark:|16.07.2004
Jurisdiktion|Jurisdiction|:white_check_mark:|Austria-AT
#### Fields for citation (ohne Fundstelle)
German | English | Required? | Example
---|---|---|---
? | Case name| :white_check_mark:|7 Ob 120/04d
?|Court|:white_check_mark:|OGH
?|Date Decided|not displayed|16.07.2004
?|Publisher|:white_check_mark:|ZVR 1999/112
?|Document Name||Mustertitel der erfundenen Entscheidung
Jurisdiktion|Jurisdiction|:white_check_mark:|Austria-AT
#### Results
##### Ohne Fundstelle 
![image](https://user-images.githubusercontent.com/93471400/175369968-e093976d-11dd-4dc3-b0bf-2487d220afff.png)
##### Mit Fundstelle
![image](https://user-images.githubusercontent.com/93471400/175370930-6a6baf23-409a-42bb-9aea-013d42425f8e.png)

### EuGH Entscheidungen
#### Type in machine language: `legal_case`
#### Type in natural language: Case
#### Fields for citation 
German | English | Required? | Example
---|---|---|---
? | Case name| :white_check_mark:|C-387/10
?|Court|:white_check_mark:|EuGH
?|Date Decided|:white_check_mark:|16.07.2004
Jurisdiktion|Jurisdiction|:white_check_mark:|European Union-EU.INT
?|Document Name||Mustertitel der erfundenen Entscheidung
?|Issue|:white_check_mark:|ECLI:EU:C:2005:446
#### Result
![image](https://user-images.githubusercontent.com/93471400/175372594-88eadc07-17b9-4342-bad8-4842cd7625e0.png)
### EGMR Entscheidungen
#### Type in machine language: `legal_case`
#### Type in natural language: Case
#### Fields for citation 
German | English | Required? | Example
---|---|---|---
? | Case name| :white_check_mark:|56483/00
?|Court|:white_check_mark:|EGMR
?|Division||GK
?|Date Decided|:white_check_mark:|07.04.2005
Jurisdiktion|Jurisdiction|:white_check_mark:|Council of Europe-COE.INT
?|Document Name||Jancikova/Österreich
#### Result
![image](https://user-images.githubusercontent.com/93471400/175373399-c8afb488-1aa0-4180-b2d2-1f4acc99f1c3.png)

### Webseite
#### Type in machine language: `webpage` or `post-weblog`
#### Type in natural language: Blog Post
#### Fields for citation 
German | English | Required? | Example
---|---|---|---
? | Title| :white_check_mark:|Überwachen, Blocken, Delisten - Zur Reichweite der EU-Sanktionen gegen RT und Sputnik
?|Author|:white_check_mark:|Lehofer
?|URL|:white_check_mark:|https://blog.lehofer.at/2022/03/uberwachen-blocken-delisten.html
?|Date|:white_check_mark:|22.03.2022
|Accessed|:white_check_mark:|26.06.2022
#### Remark for using
Choose either Date (Stand: 22.03.2022) *OR* Accessed (Abgerufen am: 26.06.2022). If you enter both, Date will be used.
#### Result
![image](https://user-images.githubusercontent.com/93471400/175373399-c8afb488-1aa0-4180-b2d2-1f4acc99f1c3.png)
