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
#### Results
![image](https://user-images.githubusercontent.com/93471400/175364893-d3473828-a5f2-4287-9c1d-1ec5fe3f5737.png)

