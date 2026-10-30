# Aargau: law history in git

The law of the canton of Aargau (Kanton Aargau, Switzerland) as a git history: one file per article, one commit per amending act on the day it took effect, and the amending act as the commit's author. `git blame` names the act behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `ch-ag/`. The federal law is in [lexifina/switzerland-law](https://github.com/lexifina/switzerland-law).

The text is in German, the canton's official language, exactly as the canton publishes it.

## What this repository holds

288 acts with 1198 versions so far: the cantonal constitution, the cantonal laws (Gesetze) in force and 206 Verordnungen and Reglemente in force, in the order of the systematic collection, added in parts. Other decrees and decisions, intercantonal agreements and repealed acts are not included yet.

| Folder | Act | Versions | History |
| --- | --- | ---: | --- |
| `110-000-kantonsverfassung-kv/` | Verfassung des Kantons Aargau (SAR 110.000) | 15 | oldest version available, then each consolidated version: 1 March 2010 to 30 June 2024 |
| `121-200-kbug/` | Gesetz über das Kantons- und das Gemeindebürgerrecht (SAR 121.200) | 3 | as enacted, then each consolidated version: 1 January 2014 to 1 July 2024 |
| `121-300-obug/` | Gesetz über das Ortsbürgerrecht (SAR 121.300) | 2 | as enacted, then each consolidated version: 1 January 1994 to 1 January 2014 |
| `122-200-register-und-meldegesetz-rmg/` | Gesetz über die Register und das Meldewesen (SAR 122.200) | 5 | as enacted, then each consolidated version: 1 May 2009 to 1 July 2024 |
| `122-600-egar/` | Einführungsgesetz zum Ausländerrecht (SAR 122.600) | 3 | as enacted, then each consolidated version: 1 May 2009 to 1 July 2024 |
| `131-100-gpr/` | Gesetz über die politischen Rechte (SAR 131.100) | 10 | oldest version available, then each consolidated version: 1 January 2010 to 1 January 2027 |
| `150-200-hg/` | Haftungsgesetz (SAR 150.200) | 2 | as enacted, then each consolidated version: 1 March 2010 to 1 July 2024 |
| `150-300-ug/` | Unvereinbarkeitsgesetz (SAR 150.300) | 6 | oldest version available, then each consolidated version: 1 January 2009 to 1 November 2025 |
| `150-400-statistikgesetz-statg/` | Gesetz über die öffentliche Statistik (SAR 150.400) | 1 | as enacted, 1 May 2024 |
| `150-600-publikationsgesetz-pug/` | Gesetz über die amtlichen Publikationsorgane (SAR 150.600) | 2 | as enacted, then each consolidated version: 1 January 2012 to 1 July 2024 |
| `150-700-idag/` | Gesetz über die Information der Öffentlichkeit, den Datenschutz und das Archivwesen (SAR 150.700) | 7 | as enacted, then each consolidated version: 1 July 2008 to 1 July 2024 |
| `152-100-grossratswahlgesetz/` | Gesetz über die Wahl des Grossen Rates (SAR 152.100) | 3 | oldest version available, then each consolidated version: 1 January 2009 to 1 May 2012 |
| `152-200-geschaftsverkehrsgesetz-gvg/` | Gesetz über die Organisation des Grossen Rates und über den Verkehr zwischen dem Grossen Rat, dem Regierungsrat und der Justizleitung (SAR 152.200) | 9 | oldest version available, then each consolidated version: 1 April 2009 to 1 January 2026 |
| `153-100-organisationsgesetz/` | Gesetz über die Organisation des Regierungsrates und der kantonalen Verwaltung (SAR 153.100) | 11 | oldest version available, then each consolidated version: 1 January 2009 to 1 January 2026 |
| `155-200-gog/` | Gerichtsorganisationsgesetz (SAR 155.200) | 3 | as enacted, then each consolidated version: 1 January 2013 to 1 April 2020 |
| `165-100-personalgesetz-persg/` | Gesetz über die Grundzüge des Personalrechts (SAR 165.100) | 5 | oldest version available, then each consolidated version: 1 March 2010 to 1 January 2017 |
| `171-100-gemeindegesetz-gg/` | Gesetz über die Einwohnergemeinden (SAR 171.100) | 14 | oldest version available, then each consolidated version: 1 January 2009 to 1 August 2026 |
| `171-200-ortsburgergemeindegesetz-obgg/` | Gesetz über die Ortsbürgergemeinden (SAR 171.200) | 3 | oldest version available, then each consolidated version: 1 March 1999 to 1 January 2019 |
| `210-300-eg-zgb/` | Einführungsgesetz zum Schweizerischen Zivilgesetzbuch (SAR 210.300) | 6 | as enacted, then each consolidated version: 1 January 2018 to 1 July 2024 |
| `210-500-eg-bewg/` | Einführungsgesetz zum Bundesgesetz über den Erwerb von Grundstücken durch Personen im Ausland (SAR 210.500) | 2 | as enacted, then each consolidated version: 1 January 1988 to 1 July 2024 |
| `210-700-g-bvsa/` | Gesetz über die BVG- und Stiftungsaufsicht (SAR 210.700) | 3 | as enacted, then each consolidated version: 1 August 2013 to 1 January 2018 |
| `231-200-eg-schkg/` | Einführungsgesetz zum Bundesgesetz über Schuldbetreibung und Konkurs (SAR 231.200) | 6 | oldest version available, then each consolidated version: 1 March 2010 to 1 July 2024 |
| `271-200-verwaltungsrechtspflegegesetz-vrpg/` | Gesetz über die Verwaltungsrechtspflege (SAR 271.200) | 6 | oldest version available, then each consolidated version: 1 January 2010 to 1 July 2024 |
| `290-100-eg-bgfa/` | Einführungsgesetz zum Bundesgesetz über die Freizügigkeit der Anwältinnen und Anwälte (SAR 290.100) | 6 | oldest version available, then each consolidated version: 1 January 2009 to 1 July 2024 |
| `295-200-beurg/` | Beurkundungs- und Beglaubigungsgesetz (SAR 295.200) | 2 | as enacted, then each consolidated version: 1 January 2013 to 1 January 2025 |
| `301-100-gesg/` | Gesundheitsgesetz (SAR 301.100) | 9 | as enacted, then each consolidated version: 1 January 2010 to 1 July 2025 |
| `301-200-pflg/` | Pflegegesetz (SAR 301.200) | 5 | as enacted, then each consolidated version: 1 January 2008 to 29 December 2018 |
| `331-200-spig/` | Spitalgesetz (SAR 331.200) | 5 | oldest version available, then each consolidated version: 1 January 2010 to 1 January 2021 |
| `390-200-eg-tsg/` | Einführungsgesetz zum Tierseuchengesetz (SAR 390.200) | 4 | as enacted, then each consolidated version: 1 January 2009 to 1 January 2022 |
| `393-400-hug/` | Hundegesetz (SAR 393.400) | 2 | as enacted, then each consolidated version: 1 May 2012 to 1 July 2024 |
| `411-200-gal/` | Gesetz über die Anstellung von Lehrpersonen (SAR 411.200) | 8 | oldest version available, then each consolidated version: 1 March 2010 to 1 August 2026 |
| `421-100-vsg/` | Volksschulgesetz (SAR 421.100) | 1 | as enacted, 1 August 2026 |
| `422-200-gbw/` | Gesetz über die Berufs- und Weiterbildung (SAR 422.200) | 9 | oldest version available, then each consolidated version: 1 January 2008 to 1 August 2026 |
| `423-100-msg/` | Mittelschulgesetz (SAR 423.100) | 1 | as enacted, 1 August 2026 |
| `427-300-hochschul-und-innovationsforderungsgesetz-hig/` | Gesetz über die Hochschul- und Innovationsförderung (SAR 427.300) | 2 | as enacted, then each consolidated version: 1 January 2008 to 1 January 2011 |
| `427-600/` | Gesetz über die Beteiligung des Kantons Aargau an der Ausbildung von Studenten der Medizin (SAR 427.600) | 1 | one version (the oldest available), 1 January 2000 |
| `428-500-betreuungsgesetz-beg/` | Gesetz über die Einrichtungen für Menschen mit besonderen Betreuungsbedürfnissen (SAR 428.500) | 6 | oldest version available, then each consolidated version: 1 January 2009 to 1 August 2026 |
| `461-100-sportg/` | Sportgesetz (SAR 461.100) | 1 | as enacted, 1 May 2026 |
| `471-200-stipendiengesetz-stipg/` | Gesetz über Ausbildungsbeiträge (SAR 471.200) | 4 | as enacted, then each consolidated version: 1 August 2007 to 1 August 2018 |
| `495-200-kg/` | Kulturgesetz (SAR 495.200) | 4 | as enacted, then each consolidated version: 1 January 2010 to 1 July 2024 |
| `515-200-bevolkerungsschutz-und-zivilschutzgesetz-aargau-bzg-ag/` | Gesetz über den Bevölkerungsschutz und den Zivilschutz im Kanton Aargau (SAR 515.200) | 5 | oldest version available, then each consolidated version: 1 January 2009 to 1 July 2024 |
| `531-200-polizeigesetz-polg/` | Gesetz über die Gewährleistung der öffentlichen Sicherheit (SAR 531.200) | 9 | oldest version available, then each consolidated version: 1 March 2010 to 1 July 2024 |
| `581-100-fwg/` | Feuerwehrgesetz (SAR 581.100) | 4 | oldest version available, then each consolidated version: 1 March 2010 to 1 January 2022 |
| `585-100-brandschutzgesetz-bsg/` | Gesetz über den vorbeugenden Brandschutz (SAR 585.100) | 3 | oldest version available, then each consolidated version: 1 January 2009 to 1 July 2024 |
| `612-200-gfk/` | Gesetz über die Finanzkontrolle (SAR 612.200) | 4 | as enacted, then each consolidated version: 1 August 2005 to 29 December 2018 |
| `612-300-gaf/` | Gesetz über die wirkungsorientierte Steuerung von Aufgaben und Finanzen (SAR 612.300) | 5 | as enacted, then each consolidated version: 1 August 2013 to 1 July 2024 |
| `612-500-g-sonderlasten/` | Gesetz über die Finanzierung der Sonderlasten (SAR 612.500) | 4 | as enacted, then each consolidated version: 31 December 2005 to 1 January 2024 |
| `615-200-finanzausgleichsgesetz-fiag/` | Gesetz über den Finanzausgleich zwischen den Gemeinden (SAR 615.200) | 2 | as enacted, then each consolidated version: 31 December 2017 to 1 January 2027 |
| `651-100-stg/` | Steuergesetz (SAR 651.100) | 17 | oldest version available, then each consolidated version: 1 January 2010 to 1 January 2025 |
| `662-100-gebuhrg/` | Allgemeines Gebührengesetz (SAR 662.100) | 1 | as enacted, 1 July 2024 |
| `671-200-gnb/` | Gesetz über die Nutzung des tiefen Untergrunds und die Gewinnung von Bodenschätzen (SAR 671.200) | 2 | as enacted, then each consolidated version: 1 March 2013 to 1 July 2024 |
| `673-100-gebaudeversicherungsgesetz-gebvg/` | Gesetz über die Gebäudeversicherung (SAR 673.100) | 7 | oldest version available, then each consolidated version: 1 January 2009 to 1 January 2022 |
| `681-100-akbg/` | Gesetz über die Aargauische Kantonalbank (SAR 681.100) | 2 | as enacted, then each consolidated version: 1 January 2007 to 1 January 2016 |
| `713-100-baugesetz-baug/` | Gesetz über Raumentwicklung und Bauwesen (SAR 713.100) | 15 | oldest version available, then each consolidated version: 1 January 2010 to 1 July 2025 |
| `725-100/` | Gesetz über die Grundbuchabgaben (SAR 725.100) | 4 | oldest version available, then each consolidated version: 1 July 2009 to 1 January 2020 |
| `740-100-kantonales-geoinformationsgesetz-kgeoig/` | Gesetz über die Geoinformation im Kanton Aargau (SAR 740.100) | 5 | as enacted, then each consolidated version: 1 January 2012 to 1 July 2024 |
| `751-200-strassengesetz-strg/` | Gesetz über das kantonale Strassenwesen (SAR 751.200) | 2 | as enacted, then each consolidated version: 1 January 2022 to 1 January 2026 |
| `755-100-vstg/` | Verkehrssteuergesetz (SAR 755.100) | 1 | as enacted, 1 January 2026 |
| `761-600-reusstalgesetz/` | Gesetz über den Hochwasserschutz, die Entwässerung und die Bodenverbesserungen im Gebiet der Reussebene (SAR 761.600) | 1 | one version (the oldest available), 1 January 2009 |
| `764-100-wng/` | Wassernutzungsgesetz (SAR 764.100) | 6 | as enacted, then each consolidated version: 1 September 2008 to 1 July 2024 |
| `773-200-energieg/` | Energiegesetz des Kantons Aargau (SAR 773.200) | 4 | as enacted, then each consolidated version: 1 September 2012 to 1 April 2025 |
| `781-200-eg-umweltrecht-eg-uwr/` | Einführungsgesetz zur Bundesgesetzgebung über den Schutz von Umwelt und Gewässern (SAR 781.200) | 7 | as enacted, then each consolidated version: 1 September 2008 to 1 July 2024 |
| `787-100/` | Gesetz über die Freie Reuss (SAR 787.100) | 1 | as enacted, 16 May 1965 |
| `811-400-eg-avig-avg/` | Einführungsgesetz zum Bundesgesetz über die obligatorische Arbeitslosenversicherung und die Insolvenzentschädigung sowie zum Bundesgesetz über die Arbeitsvermittlung und den Personalverleih (SAR 811.400) | 3 | as enacted, then each consolidated version: 1 May 2005 to 1 August 2018 |
| `815-200-eg-familienzulagengesetz-eg-famzg/` | Einführungsgesetz zum Bundesgesetz über die Familienzulagen (SAR 815.200) | 3 | as enacted, then each consolidated version: 1 January 2010 to 1 January 2026 |
| `815-300-kinderbetreuungsgesetz-kibeg/` | Gesetz über die familienergänzende Kinderbetreuung (SAR 815.300) | 1 | as enacted, 1 August 2016 |
| `831-100-svag/` | Gesetz über die SVA Aargau (SAR 831.100) | 4 | oldest version available, then each consolidated version: 1 January 2009 to 1 December 2025 |
| `831-300-erganzungsleistungsgesetz-aargau-elg-ag/` | Gesetz über Ergänzungsleistungen zur Alters-, Hinterlassenen- und Invalidenversicherung im Kanton Aargau (SAR 831.300) | 5 | as enacted, then each consolidated version: 1 January 2008 to 1 December 2025 |
| `837-200-kvgg/` | Gesetz zum Bundesgesetz über die Krankenversicherung (SAR 837.200) | 3 | as enacted, then each consolidated version: 1 July 2016 to 1 December 2025 |
| `851-200-sozialhilfe-und-praventionsgesetz-spg/` | Gesetz über die öffentliche Sozialhilfe und die soziale Prävention (SAR 851.200) | 11 | oldest version available, then each consolidated version: 1 July 2009 to 1 April 2024 |
| `873-700/` | Gesetz über die Förderung des Baues von Alters-, Invaliden- und Familienwohnungen sowie die Regional- und Ortsplanung (SAR 873.700) | 1 | one version (the oldest available), 1 April 1994 |
| `910-200-lwg-ag/` | Landwirtschaftsgesetz des Kantons Aargau (SAR 910.200) | 6 | as enacted, then each consolidated version: 1 August 2012 to 1 July 2024 |
| `931-100-awag/` | Waldgesetz des Kantons Aargau (SAR 931.100) | 7 | oldest version available, then each consolidated version: 1 January 2009 to 1 November 2024 |
| `933-200-jagdgesetz-des-kantons-aargau-ajsg/` | Einführungsgesetz zum Bundesgesetz über die Jagd und den Schutz wildlebender Säugetiere und Vögel (SAR 933.200) | 4 | as enacted, then each consolidated version: 1 January 2010 to 1 July 2024 |
| `935-200-fischereigesetz-des-kantons-aargau-afg/` | Einführungsgesetz zum Bundesgesetz über die Fischerei (SAR 935.200) | 2 | as enacted, then each consolidated version: 1 July 2013 to 1 July 2024 |
| `940-100-standortforderungsgesetz-sfg/` | Gesetz über die Standortförderung (SAR 940.100) | 3 | as enacted, then each consolidated version: 1 January 2010 to 1 January 2021 |
| `959-300-gsg/` | Geldspielgesetz des Kantons Aargau (SAR 959.300) | 2 | as enacted, then each consolidated version: 1 January 2021 to 1 July 2024 |
| `961-200-eg-arr/` | Einführungsgesetz zum Arbeitsrecht (SAR 961.200) | 4 | as enacted, then each consolidated version: 1 September 2012 to 1 September 2025 |
| `970-100-gastgewerbegesetz-ggg/` | Gesetz über das Gastgewerbe und den Kleinhandel mit alkoholhaltigen Getränken (SAR 970.100) | 3 | oldest version available, then each consolidated version: 1 January 2010 to 1 July 2024 |
| `991-100/` | Gesetz über den Vollzug des Strassenverkehrsrechtes (SAR 991.100) | 3 | oldest version available, then each consolidated version: 1 January 2009 to 1 July 2024 |
| `995-100-ovg/` | Gesetz über den öffentlichen Verkehr (SAR 995.100) | 4 | oldest version available, then each consolidated version: 1 January 2010 to 1 January 2018 |
| `997-100/` | Einführungsgesetz zum Bundesgesetz über die Binnenschifffahrt (SAR 997.100) | 3 | as enacted, then each consolidated version: 1 April 1981 to 1 July 2024 |
| `121-213-kbuv/` | Verordnung über das Kantons- und das Gemeindebürgerrecht (SAR 121.213) | 5 | as enacted, then each consolidated version: 1 April 2016 to 1 July 2024 |
| `122-212-register-und-meldeverordnung-rmv/` | Verordnung zum Gesetz über die Register und das Meldewesen (SAR 122.212) | 2 | as enacted, then each consolidated version: 1 September 2021 to 1 July 2024 |
| `122-315-vair/` | Vollziehungsverordnung zum Ausländer- und Integrationsrecht (SAR 122.315) | 6 | oldest version available, then each consolidated version: 1 May 2009 to 1 July 2024 |
| `122-515-integrationsv/` | Verordnung über die Integration der ausländischen Bevölkerung (SAR 122.515) | 6 | as enacted, then each consolidated version: 1 March 2009 to 1 August 2026 |
| `123-121-vv-ausweisgesetz/` | Vollziehungsverordnung zum Bundesgesetz über die Ausweise für Schweizer Staatsangehörige (SAR 123.121) | 6 | oldest version available, then each consolidated version: 1 March 2010 to 1 November 2026 |
| `131-111-vgpr/` | Verordnung zum Gesetz über die politischen Rechte (SAR 131.111) | 5 | oldest version available, then each consolidated version: 1 January 2010 to 1 July 2024 |
| `131-131/` | Verordnung über die Wahl des Nationalrates (SAR 131.131) | 2 | oldest version available, then each consolidated version: 1 September 2010 to 1 July 2015 |
| `131-731/` | Verordnung über die Wahl des Einwohnerrates (SAR 131.731) | 2 | oldest version available, then each consolidated version: 1 January 2009 to 1 May 2012 |
| `150-211-hv/` | Haftungsverordnung (SAR 150.211) | 1 | as enacted, 1 March 2010 |
| `150-411-statv/` | Statistikverordnung (SAR 150.411) | 1 | as enacted, 1 May 2024 |
| `150-711-vidag/` | Verordnung zum Gesetz über die Information der Öffentlichkeit, den Datenschutz und das Archivwesen (SAR 150.711) | 4 | as enacted, then each consolidated version: 1 July 2008 to 1 January 2026 |
| `150-731-aktenv/` | Verordnung zur Aktenführung in der kantonalen Verwaltung (SAR 150.731) | 1 | as enacted, 1 January 2026 |
| `152-111/` | Verordnung zum Grossratswahlgesetz (SAR 152.111) | 3 | oldest version available, then each consolidated version: 1 July 2008 to 1 September 2015 |
| `153-113-delegationsverordnung-delv/` | Verordnung über die Delegation von Kompetenzen des Regierungsrats (SAR 153.113) | 16 | as enacted, then each consolidated version: 1 August 2013 to 1 August 2026 |
| `153-313-v-rdrr/` | Verordnung über den Rechtsdienst des Regierungsrats (SAR 153.313) | 2 | as enacted, then each consolidated version: 1 January 2014 to 30 December 2019 |
| `155-611/` | Reglement der Justizleitung über die Aufgaben und Ziele (SAR 155.611) | 1 | as enacted, 1 January 2013 |
| `155-612/` | Reglement der Justizleitung über die Anzahl der übrigen Richterinnen und Richter (nebenamtliche Richterinnen und Richter an den Bezirksgerichten; Fachrichterinnen und Fachrichter des Kindes- und Erwachsenenschutzes; Mitglieder der Schlichtungsbehörden für Miete und Pacht; Mitglieder der Schlichtungsstelle für Gleichstellungsfragen; Friedensrichterinnen und Friedensrichter nach Kreisen) (SAR 155.612) | 9 | as enacted, then each consolidated version: 1 January 2013 to 1 March 2024 |
| `155-613/` | Reglement der Justizleitung über die Praktikumsverhältnisse der Rechtspraktikantinnen und Rechtspraktikanten (SAR 155.613) | 1 | as enacted, 1 January 2013 |
| `155-614/` | Reglement für die Schlichtungsbehörden für Miete und Pacht (SAR 155.614) | 1 | as enacted, 1 January 2013 |
| `155-615/` | Reglement der Justizleitung über das Zentrale Rechnungswesen und Controlling (SAR 155.615) | 2 | as enacted, then each consolidated version: 1 May 2014 to 1 May 2020 |
| `155-616-informationsreglement/` | Reglement der Justizleitung über die Information der Öffentlichkeit und die Publikation von Entscheiden (SAR 155.616) | 3 | as enacted, then each consolidated version: 1 July 2016 to 1 March 2022 |
| `155-617/` | Reglement der Justizleitung über Akteneinsicht und Archivierung (SAR 155.617) | 4 | as enacted, then each consolidated version: 1 July 2017 to 1 January 2023 |
| `160-621-weiterbildungsverordnung/` | Verordnung über die Weiterbildung des Personals (SAR 160.621) | 2 | as enacted, then each consolidated version: 1 January 2005 to 1 January 2020 |
| `161-115-azv/` | Arbeitszeitverordnung (SAR 161.115) | 4 | oldest version available, then each consolidated version: 1 November 2005 to 1 January 2020 |
| `161-221-inkonvenienzverordnung/` | Verordnung über die Vergütung von Inkonvenienzen (SAR 161.221) | 6 | oldest version available, then each consolidated version: 1 November 2004 to 1 January 2023 |
| `163-125/` | Personalreglement der Aargauischen Pensionskasse (APK) (SAR 163.125) | 2 | as enacted, then each consolidated version: 1 January 2008 to 1 January 2021 |
| `165-134-vep/` | Verordnung zum Einreihungsplan (SAR 165.134) | 1 | as enacted, 1 March 2025 |
| `165-171-spesenverordnung-spesenv/` | Verordnung über Spesen, Sitzungsgelder und übrige Entschädigungen (SAR 165.171) | 8 | oldest version available, then each consolidated version: 1 March 2002 to 1 April 2026 |
| `165-175/` | Verordnung über die Löhne besonderer Personalkategorien (SAR 165.175) | 5 | oldest version available, then each consolidated version: 1 September 2009 to 1 August 2024 |
| `165-321-vvp/` | Verordnung über die vorzeitige Pensionierung (SAR 165.321) | 2 | as enacted, then each consolidated version: 1 January 2011 to 1 September 2012 |
| `210-114-entschadigungsreglement-bvsa/` | Reglement über die Entschädigung der Mitglieder des Verwaltungsrats der BVG- und Stiftungsaufsicht Aargau (SAR 210.114) | 1 | as enacted, 1 August 2013 |
| `210-118-geschaftsreglement-bvsa/` | Geschäftsreglement der BVG- und Stiftungsaufsicht Aargau (SAR 210.118) | 3 | as enacted, then each consolidated version: 21 November 2011 to 1 September 2018 |
| `210-119-personalreglement-bvsa/` | Personalreglement der BVG- und Stiftungsaufsicht Aargau (SAR 210.119) | 2 | as enacted, then each consolidated version: 21 November 2011 to 1 August 2013 |
| `210-125-v-kesr/` | Verordnung über das Kindes- und Erwachsenenschutzrecht (SAR 210.125) | 3 | as enacted, then each consolidated version: 1 January 2013 to 1 January 2018 |
| `210-311-v-eg-zgb/` | Verordnung zum Einführungsgesetz zum Schweizerischen Zivilgesetzbuch (SAR 210.311) | 4 | as enacted, then each consolidated version: 1 January 2018 to 1 July 2024 |
| `210-511/` | Verordnung zum Bundesgesetz über den Erwerb von Grundstücken durch Personen im Ausland (SAR 210.511) | 2 | oldest version available, then each consolidated version: 1 September 2005 to 1 July 2024 |
| `221-211/` | Verordnung über die Entschädigung für die unentgeltliche Mediation (SAR 221.211) | 1 | as enacted, 1 January 2011 |
| `231-211/` | Verordnung über die Prüfung zum Erwerb des Fähigkeitsausweises zur Führung eines Betreibungsamtes (SAR 231.211) | 3 | as enacted, then each consolidated version: 1 January 2006 to 1 July 2024 |
| `251-213-obvv/` | Verordnung über das Ordnungsbussenverfahren (SAR 251.213) | 1 | as enacted, 1 July 2021 |
| `251-315/` | Verordnung über die Aufbewahrung, Vernichtung und Weitergabe von Personendaten aus Jugendstrafverfahren im Schulbereich (SAR 251.315) | 1 | as enacted, 1 January 2011 |
| `253-112-strafvollzugsverordnung-smv/` | Verordnung über den Vollzug von Strafen und Massnahmen (SAR 253.112) | 3 | as enacted, then each consolidated version: 1 January 2021 to 1 May 2026 |
| `253-331/` | Verordnung über die Organisation der Justizvollzugsanstalt Lenzburg (SAR 253.331) | 5 | oldest version available, then each consolidated version: 1 January 2009 to 1 January 2021 |
| `253-371/` | Verordnung über die Organisation des Jugendheims Aarburg (SAR 253.371) | 6 | oldest version available, then each consolidated version: 1 January 2009 to 1 January 2018 |
| `255-113-voh/` | Verordnung zur Bundesgesetzgebung über die Hilfe an Opfer von Straftaten (SAR 255.113) | 1 | as enacted, 1 July 2011 |
| `271-133/` | Verordnung über die Rechtspflege in der beruflichen Vorsorge (SAR 271.133) | 1 | one version (the oldest available), 1 January 2009 |
| `271-134-voss/` | Verordnung über das Schiedsgericht in Sozialversicherungssachen (SAR 271.134) | 1 | as enacted, 1 July 2016 |
| `271-215-ubermittlungsverordnung-umv/` | Verordnung über die elektronische Übermittlung in Verfahren vor Verwaltungs- und Verwaltungsjustizbehörden (SAR 271.215) | 5 | as enacted, then each consolidated version: 1 July 2012 to 1 June 2025 |
| `290-111-anwv/` | Anwaltsverordnung (SAR 290.111) | 5 | oldest version available, then each consolidated version: 1 July 2009 to 1 July 2024 |
| `301-111-gesv/` | Verordnung zum Gesundheitsgesetz (SAR 301.111) | 16 | as enacted, then each consolidated version: 1 January 2010 to 1 January 2026 |
| `301-112-vdpg/` | Verordnung über die Durchführung von Pilotprojekten in der Gesundheitsversorgung (SAR 301.112) | 3 | as enacted, then each consolidated version: 1 January 2022 to 1 May 2025 |
| `301-113-v-pflegeausbildung/` | Verordnung zur Umsetzung des Bundesgesetzes über die Förderung der Ausbildung im Bereich der Pflege (SAR 301.113) | 2 | as enacted, then each consolidated version: 1 July 2024 to 1 January 2026 |
| `301-114-vzok/` | Verordnung über die Zulassung von Leistungserbringern zur Tätigkeit zulasten der obligatorischen Krankenpflegeversicherung (SAR 301.114) | 1 | as enacted, 1 July 2025 |
| `301-215-pflv/` | Pflegeverordnung (SAR 301.215) | 11 | as enacted, then each consolidated version: 1 January 2013 to 1 July 2026 |
| `301-513-v-sterg/` | Einführungsverordnung zum Bundesgesetz über Voraussetzungen und Verfahren bei Sterilisationen (SAR 301.513) | 3 | oldest version available, then each consolidated version: 1 January 2006 to 1 January 2018 |
| `301-515-v-transplantationsgesetz/` | Einführungsverordnung zum Bundesgesetz über die Transplantation von Organen, Geweben und Zellen (SAR 301.515) | 2 | as enacted, then each consolidated version: 1 July 2007 to 1 January 2013 |
| `301-517-ev-krg/` | Einführungsverordnung zum Bundesgesetz über die Registrierung von Krebserkrankungen (SAR 301.517) | 1 | as enacted, 1 January 2020 |
| `311-121-vbob/` | Verordnung über die Berufe, Organisationen und Betriebe im Gesundheitswesen (SAR 311.121) | 7 | as enacted, then each consolidated version: 1 January 2010 to 1 January 2026 |
| `311-211/` | Gebührenverordnung der Schweizerischen Konferenz der kantonalen Gesundheitsdirektorinnen und -direktoren (GDK) (SAR 311.211) | 2 | as enacted, then each consolidated version: 7 March 2013 to 1 February 2023 |
| `311-213-verordnung-ausland-vo-ausland/` | Verordnung der GDK über die Anerkennung und Nachprüfung von ausländischen Berufsqualifikationen in Osteopathie (SAR 311.213) | 1 | as enacted, 22 November 2012 |
| `311-215/` | Reglement der GDK für die interkantonale Prüfung von Osteopathinnen und Osteopathen in der Schweiz (SAR 311.215) | 1 | as enacted, 22 November 2012 |
| `311-217/` | Reglement der Schweizerischen Konferenz der kantonalen Gesundheitsdirektorinnen und -direktoren (GDK) über die Gebühren für die interkantonale Prüfung der Osteopathinnen und Osteopathen (SAR 311.217) | 2 | as enacted, then each consolidated version: 24 January 2013 to 10 April 2014 |
| `320-112-vv-epg/` | Verordnung über den Vollzug der eidgenössischen Epidemiengesetzgebung (SAR 320.112) | 4 | as enacted, then each consolidated version: 1 January 2016 to 1 July 2021 |
| `331-212-spiv/` | Spitalverordnung (SAR 331.212) | 6 | as enacted, then each consolidated version: 1 January 2012 to 5 December 2018 |
| `331-215-spiliv/` | Verordnung über die Spitalliste (SAR 331.215) | 3 | as enacted, then each consolidated version: 1 May 2013 to 1 August 2020 |
| `331-217-gwlv/` | Verordnung über die gemeinwirtschaftlichen Leistungen (SAR 331.217) | 7 | as enacted, then each consolidated version: 1 January 2021 to 1 January 2026 |
| `331-219-vorhalteleistungs-verordnung-volev/` | Verordnung zur Entschädigung der Spitäler für Vorhalteleistungen (Ertragsausfälle und Zusatzkosten) zur Bekämpfung der Covid-19-Pandemie (SAR 331.219) | 1 | one version (the oldest available), 1 January 2022 |
| `333-111-patientenverordnung-patv/` | Verordnung über die Rechte und Pflichten der Patientinnen und Patienten (SAR 333.111) | 4 | as enacted, then each consolidated version: 1 January 2010 to 1 August 2018 |
| `355-112-v-chemg/` | Verordnung über den Vollzug der eidgenössischen Chemikalien- und der Vorläuferstoffgesetzgebung (SAR 355.112) | 3 | as enacted, then each consolidated version: 1 January 2006 to 1 July 2023 |
| `361-112-lebensmittel-und-gebrauchsgegenstandeverordnung-lggv/` | Verordnung über den Vollzug der Bundesgesetzgebung über Lebensmittel und Gebrauchsgegenstände (SAR 361.112) | 1 | as enacted, 1 July 2017 |
| `371-112-bestattungsverordnung/` | Verordnung über das Bestattungswesen (SAR 371.112) | 4 | as enacted, then each consolidated version: 1 January 2010 to 1 January 2017 |
| `371-312/` | Verordnung über die Legalinspektion (SAR 371.312) | 1 | as enacted, 1 January 2017 |
| `390-211-v-eg-tsg/` | Verordnung zum Einführungsgesetz zum Tierseuchengesetz (SAR 390.211) | 8 | as enacted, then each consolidated version: 1 January 2009 to 1 January 2025 |
| `393-111/` | Verordnung über den Vollzug der eidgenössischen Tierschutzgesetzgebung (SAR 393.111) | 6 | oldest version available, then each consolidated version: 1 January 2009 to 1 July 2024 |
| `393-411-hundeverordnung-huv/` | Verordnung zum Hundegesetz (SAR 393.411) | 5 | as enacted, then each consolidated version: 1 May 2012 to 1 March 2024 |
| `400-720/` | Reglement über die Anerkennung der Abschlüsse von Fachmittelschulen (SAR 400.720) | 1 | as enacted, 25 June 2020 |
| `400-740-maturitatsanerkennungsreglement-mar/` | Reglement der EDK über die Anerkennung von gymnasialen Maturitätszeugnissen (SAR 400.740) | 1 | one version (the oldest available), 1 August 2024 |
| `403-711-v-schulunfallversicherung/` | Verordnung über die Unfallversicherung von Schülerinnen und Schülern (SAR 403.711) | 3 | oldest version available, then each consolidated version: 1 January 2008 to 1 August 2026 |
| `405-112-v-schuldienste/` | Verordnung über die Schuldienste (SAR 405.112) | 10 | as enacted, then each consolidated version: 1 January 2018 to 1 August 2026 |
| `411-211-vall/` | Verordnung über die Anstellung und Löhne der Lehrpersonen (SAR 411.211) | 19 | oldest version available, then each consolidated version: 1 August 2008 to 1 March 2027 |
| `411-215-weiterbildungsverordnung-lehrpersonen/` | Verordnung über die Weiterbildung der Lehrpersonen (SAR 411.215) | 6 | as enacted, then each consolidated version: 1 January 2007 to 1 August 2018 |
| `411-712/` | Verordnung über die Entschädigung der Mitglieder des Erziehungsrats (SAR 411.712) | 3 | as enacted, then each consolidated version: 1 March 2007 to 1 August 2026 |
| `411-731/` | Verordnung über die Mittel der Schulräte der Bezirke und die Entschädigung deren Mitglieder (SAR 411.731) | 3 | oldest version available, then each consolidated version: 1 July 2008 to 1 August 2026 |
| `421-315-v-vsg/` | Volksschulverordnung (SAR 421.315) | 1 | as enacted, 1 August 2026 |
| `421-325-vrf/` | Verordnung über die Ressourcierung und Finanzierung der Volksschule (SAR 421.325) | 1 | as enacted, 1 August 2026 |
| `422-211-vbw/` | Verordnung über die Berufs- und Weiterbildung (SAR 422.211) | 19 | oldest version available, then each consolidated version: 1 August 2010 to 1 August 2026 |
| `422-214-v-abu/` | Verordnung über die Allgemeinbildung in der beruflichen Grundbildung (SAR 422.214) | 1 | as enacted, 1 August 2026 |
| `422-222-v-bruckenangebot/` | Verordnung über die Kantonale Schule für Berufsbildung und das Brückenangebot (SAR 422.222) | 1 | as enacted, 1 August 2026 |
| `422-233-v-bfgs-und-hfgs/` | Verordnung über die Berufsfachschule Gesundheit und Soziales und die Höhere Fachschule Gesundheit und Soziales (SAR 422.233) | 3 | as enacted, then each consolidated version: 15 September 2024 to 1 August 2026 |
| `422-251-v-bm/` | Verordnung über die Berufsmaturität an Berufsfachschulen (SAR 422.251) | 10 | oldest version available, then each consolidated version: 1 August 2010 to 1 August 2026 |
| `422-617-lzlv/` | Verordnung über das Landwirtschaftliche Zentrum Liebegg (SAR 422.617) | 6 | as enacted, then each consolidated version: 1 August 2012 to 1 August 2026 |
| `423-125-mittelschulverordnung-msv/` | Verordnung über die Mittelschule (SAR 423.125) | 2 | as enacted, then each consolidated version: 1 August 2026 to 1 August 2027 |
| `423-152-v-gymnasium/` | Verordnung über die Promotion und die Maturität am Gymnasium (SAR 423.152) | 12 | oldest version available, then each consolidated version: 1 August 2010 to 1 August 2027 |
| `423-155-v-wms/` | Verordnung über die Promotion, das eidgenössische Fähigkeitszeugnis und die Berufsmaturität an der Wirtschaftsmittelschule (SAR 423.155) | 10 | as enacted, then each consolidated version: 1 August 2010 to 1 August 2026 |
| `423-332-v-fms/` | Verordnung über die Promotion, den Fachmittelschulabschluss und die Fachmaturität an der Fachmittelschule (SAR 423.332) | 15 | as enacted, then each consolidated version: 1 August 2010 to 1 August 2027 |
| `423-342-v-ims/` | Verordnung über die Promotion, das eidgenössische Fähigkeitszeugnis und die Berufsmaturität an der Informatikmittelschule (SAR 423.342) | 8 | as enacted, then each consolidated version: 1 August 2010 to 1 August 2026 |
| `423-922/` | Verordnung über den Instrumentalunterricht an den Mittelschulen (SAR 423.922) | 6 | as enacted, then each consolidated version: 1 August 2017 to 1 August 2026 |
| `426-123/` | Verordnung über das gestalterische Propädeutikum (SAR 426.123) | 5 | as enacted, then each consolidated version: 1 August 2017 to 1 August 2026 |
| `428-511-betreuungsverordnung-bev/` | Verordnung über die Einrichtungen für Menschen mit besonderen Betreuungsbedürfnissen (SAR 428.511) | 15 | oldest version available, then each consolidated version: 1 January 2008 to 1 August 2026 |
| `428-514-vsmb/` | Verordnung über das Pilotprojekt zur Subjektfinanzierung von Leistungen für Menschen mit Behinderungen (SAR 428.514) | 1 | as enacted, 1 January 2025 |
| `453-113-v-ame/` | Verordnung über die Aargauische Maturitätsschule für Erwachsene (SAR 453.113) | 1 | as enacted, 1 August 2026 |
| `453-151-vpame/` | Verordnung über die Promotion, die Maturitätsprüfung und die Erlangung der Maturität an der Aargauischen Maturitätsschule für Erwachsene (SAR 453.151) | 9 | oldest version available, then each consolidated version: 1 August 2010 to 1 August 2027 |
| `453-153-passerellenverordnung/` | Verordnung über die Passerelle Berufsmaturität/Fachmaturität – universitäre Hochschulen (SAR 453.153) | 9 | oldest version available, then each consolidated version: 1 August 2010 to 1 August 2026 |
| `453-163-v-vorkurs-padagogik/` | Verordnung über den Vorkurs Pädagogik (SAR 453.163) | 11 | oldest version available, then each consolidated version: 1 August 2010 to 1 August 2027 |
| `461-115-sportverordnung-sportv/` | Verordnung zum Sportgesetz (SAR 461.115) | 1 | as enacted, 1 May 2026 |
| `471-211-stipendienverordnung-stipv/` | Verordnung über Ausbildungsbeiträge (SAR 471.211) | 8 | as enacted, then each consolidated version: 1 August 2007 to 1 July 2026 |
| `495-211-vkg/` | Verordnung zum Kulturgesetz (SAR 495.211) | 8 | as enacted, then each consolidated version: 1 January 2010 to 1 November 2024 |
| `495-222/` | Geschäftsreglement des Aargauer Kuratoriums (SAR 495.222) | 1 | as enacted, 1 March 2023 |
| `495-351-v-klosterkirche-und-klosterhalbinsel-wettingen/` | Verordnung über die Verwaltung und Benutzung der Klosterkirche und das kulturtouristische Angebot auf der Klosterhalbinsel Wettingen (SAR 495.351) | 3 | oldest version available, then each consolidated version: 1 September 2005 to 1 July 2024 |
| `511-712-vma-ag/` | Verordnung über den Vollzug der militärischen Aufgaben im Kanton Aargau (SAR 511.712) | 1 | as enacted, 1 January 2025 |
| `511-761-wpev-ag/` | Kantonale Verordnung über die Wehrpflichtersatzabgabe (SAR 511.761) | 5 | oldest version available, then each consolidated version: 1 January 2010 to 1 January 2026 |
| `515-211-bzv-ag/` | Verordnung über den Bevölkerungsschutz und den Zivilschutz im Kanton Aargau (SAR 515.211) | 7 | oldest version available, then each consolidated version: 1 January 2009 to 1 July 2024 |
| `515-213-kv-zs-ag/` | Verordnung über die Schutzdienstleistung und Kontrollführung des Zivilschutzes im Kanton Aargau (SAR 515.213) | 4 | as enacted, then each consolidated version: 1 January 2007 to 1 July 2024 |
| `515-215-alarmierungsverordnung-aargau-av-ag/` | Verordnung über die Warnung und Alarmierung im Kanton Aargau (SAR 515.215) | 4 | as enacted, then each consolidated version: 1 January 2007 to 1 January 2024 |
| `531-211-polizeiverordnung-polv/` | Verordnung über die Gewährleistung der öffentlichen Sicherheit (SAR 531.211) | 4 | as enacted, then each consolidated version: 1 July 2021 to 1 May 2026 |
| `581-111-feuerwehrverordnung-fwv/` | Verordnung zum Feuerwehrgesetz (SAR 581.111) | 5 | oldest version available, then each consolidated version: 1 January 2008 to 1 January 2022 |
| `581-514-interventionsfondsverordnung-ifv/` | Verordnung über die Beitragsleistung aus dem Fonds zur Bekämpfung von Feuer- und Elementarschäden (SAR 581.514) | 1 | as enacted, 1 January 2022 |
| `585-113-bsv/` | Brandschutzverordnung (SAR 585.113) | 6 | oldest version available, then each consolidated version: 1 April 2010 to 1 January 2022 |
| `611-115-swisslos-fonds-verordnung-slfv/` | Verordnung über die Verwendung der Mittel des Swisslos-Fonds (SAR 611.115) | 8 | oldest version available, then each consolidated version: 1 January 2009 to 1 August 2025 |
| `612-117-immov/` | Verordnung über die Immobilien des Kantons (SAR 612.117) | 3 | as enacted, then each consolidated version: 1 May 2023 to 1 May 2024 |
| `612-311-vaf/` | Verordnung über die wirkungsorientierte Steuerung von Aufgaben und Finanzen (SAR 612.311) | 11 | oldest version available, then each consolidated version: 1 August 2013 to 1 July 2024 |
| `615-211-finanzausgleichsverordnung-fiav/` | Verordnung über den Finanzausgleich zwischen den Gemeinden (SAR 615.211) | 4 | as enacted, then each consolidated version: 31 December 2017 to 1 January 2027 |
| `617-113-finanzverordnung-fiv/` | Verordnung über den Finanzhaushalt der Gemeinden, Gemeindeverbände und Gemeindeanstalten (SAR 617.113) | 4 | as enacted, then each consolidated version: 1 January 2014 to 1 January 2021 |
| `621-111/` | Verordnung zum Bundesgesetz über die direkte Bundessteuer (SAR 621.111) | 6 | oldest version available, then each consolidated version: 1 January 2009 to 1 January 2026 |
| `621-312/` | Verordnung über die pauschale Steueranrechnung (SAR 621.312) | 1 | as enacted, 1 January 2001 |
| `623-312/` | Verordnung zum Bundesgesetz über die Verrechnungssteuer (SAR 623.312) | 2 | as enacted, then each consolidated version: 1 January 2001 to 1 January 2013 |
| `623-313/` | Verordnung über die Auszahlung des zusätzlichen Steuerrückbehaltes auf amerikanischen Dividenden und Zinsen (SAR 623.313) | 1 | as enacted, 1 January 1953 |
| `623-321/` | Vollziehungsverordnung zum Bundesgesetz über die Stempelabgaben (SAR 623.321) | 2 | as enacted, then each consolidated version: 1 April 1918 to 1 January 2013 |
| `651-111-stgv/` | Verordnung zum Steuergesetz (SAR 651.111) | 11 | oldest version available, then each consolidated version: 1 January 2007 to 1 January 2026 |
| `651-131-progressionsverordnung-2019/` | Verordnung über die Anpassung des Steuergesetzes an die Teuerung (SAR 651.131) | 1 | as enacted, 1 January 2019 |
| `651-132-progressionsverordnung-2020/` | Verordnung über die Anpassung des Steuergesetzes an die Teuerung (SAR 651.132) | 1 | as enacted, 1 January 2020 |
| `651-133-progressionsverordnung-2023/` | Verordnung über die Anpassung des Steuergesetzes an die Teuerung (SAR 651.133) | 1 | as enacted, 1 January 2023 |
| `651-134-progressionsverordnung-2024/` | Verordnung über die Anpassung des Steuergesetzes an die Teuerung (SAR 651.134) | 1 | as enacted, 1 January 2024 |
| `651-135-progressionsverordnung-2025/` | Verordnung über die Anpassung des Steuergesetzes an die Teuerung (SAR 651.135) | 2 | as enacted, then each consolidated version: 1 January 2025 to 1 January 2026 |
| `651-217-vbg/` | Verordnung über die Bewertung der Grundstücke (SAR 651.217) | 1 | as enacted, 1 January 2025 |
| `651-271/` | Verordnung über das Nachlassinventar (SAR 651.271) | 3 | oldest version available, then each consolidated version: 1 September 2005 to 1 January 2018 |
| `651-313-zinsverordnung/` | Verordnung über Vergütungs-, Ausgleichs- und Verzugszinsen (SAR 651.313) | 3 | as enacted, then each consolidated version: 1 January 2014 to 1 July 2024 |
| `651-712-qstv-ag/` | Verordnung über die Quellensteuer (SAR 651.712) | 3 | as enacted, then each consolidated version: 1 January 2021 to 1 January 2024 |
| `651-811-vas/` | Verordnung über die Amtshilfe der Steuerbehörden (SAR 651.811) | 3 | as enacted, then each consolidated version: 1 January 2020 to 1 July 2025 |
| `651-821-vevst/` | Verordnung über elektronische Verfahren im Steuerbereich (SAR 651.821) | 2 | as enacted, then each consolidated version: 1 January 2025 to 29 October 2025 |
| `661-153/` | Verordnung über die Benutzung von kantonalen Gebäuden und Anlagen (SAR 661.153) | 4 | oldest version available, then each consolidated version: 1 March 2010 to 1 July 2024 |
| `662-111-gebuhrv/` | Gebührenverordnung (SAR 662.111) | 5 | as enacted, then each consolidated version: 1 July 2024 to 1 August 2026 |
| `673-111-gebvv/` | Verordnung zum Gesetz über die Gebäudeversicherung (SAR 673.111) | 2 | as enacted, then each consolidated version: 1 January 2008 to 1 July 2012 |
| `673-131/` | Verordnung über die Abgrenzung zwischen Gebäude- und Fahrhabeversicherung (SAR 673.131) | 1 | one version (the oldest available), 1 January 2008 |
| `673-156-praventionsfondsverordnung-pfv/` | Verordnung über die Beitragsleistung aus dem Fonds zur Verhütung von Feuer- und Elementarschäden (SAR 673.156) | 1 | as enacted, 1 January 2022 |
| `673-165/` | Reglement über den Selbstbehalt in der Elementarschadenversicherung (SAR 673.165) | 1 | as enacted, 1 July 2012 |
| `673-216-persr/` | Personalreglement der Aargauischen Gebäudeversicherung (SAR 673.216) | 3 | oldest version available, then each consolidated version: 1 January 2010 to 1 January 2025 |
| `673-221-agr/` | Allgemeines Geschäftsreglement (SAR 673.221) | 2 | as enacted, then each consolidated version: 26 June 2013 to 1 October 2017 |
| `673-222/` | Vergütungsreglement des Verwaltungsrats und der Geschäftsleitung der Aargauischen Gebäudeversicherung (SAR 673.222) | 2 | as enacted, then each consolidated version: 1 October 2017 to 1 January 2026 |
| `673-353-schatzungsreglement/` | Reglement über die Einschätzung und Schadenerledigung bei Gebäuden (SAR 673.353) | 4 | as enacted, then each consolidated version: 1 January 2008 to 1 August 2023 |
| `673-355/` | Reglement über die Schätzungsgebühren (SAR 673.355) | 1 | as enacted, 1 January 1997 |
| `681-123/` | Personalreglement der Aargauischen Kantonalbank (SAR 681.123) | 1 | as enacted, 27 August 2008 |
| `681-713/` | Reglement über die Vergütung der Geschäftsleitung der Aargauischen Kantonalbank (SAR 681.713) | 4 | as enacted, then each consolidated version: 1 January 2016 to 23 August 2023 |
| `681-714/` | Reglement über die Vergütung des Bankrats der Aargauischen Kantonalbank (SAR 681.714) | 2 | as enacted, then each consolidated version: 1 January 2021 to 1 January 2023 |
| `713-112-lev/` | Verordnung über Landumlegung, Grenzbereinigung und Enteignung (SAR 713.112) | 3 | oldest version available, then each consolidated version: 1 September 2005 to 1 January 2013 |
| `713-115-epr/` | Kantonales Reglement über Ersatzabgaben für die Befreiung von der Parkplatzerstellungspflicht (SAR 713.115) | 2 | as enacted, then each consolidated version: 1 April 1994 to 1 September 2011 |
| `713-116-mehrwertabgabeverordnung-mwav/` | Verordnung über die Mehrwertabgabe (SAR 713.116) | 4 | as enacted, then each consolidated version: 1 May 2017 to 1 March 2020 |
| `713-121-bauv/` | Bauverordnung (SAR 713.121) | 12 | as enacted, then each consolidated version: 1 September 2011 to 1 July 2026 |
| `720-110/` | Grossratsverordnung über die Einführung des Grundbuches (SAR 720.110) | 3 | as enacted, then each consolidated version: 5 July 1911 to 1 January 2018 |
| `721-115-kgbv/` | Kantonale Grundbuchverordnung (SAR 721.115) | 5 | as enacted, then each consolidated version: 1 July 2009 to 1 January 2018 |
| `723-154/` | Verordnung über die Entschädigung der Nachführungsgeometer (SAR 723.154) | 2 | as enacted, then each consolidated version: 1 July 2008 to 1 January 2012 |
| `725-131/` | Verordnung über die Kanzleigebühren im Grundbuchbereich (SAR 725.131) | 2 | oldest version available, then each consolidated version: 1 July 2009 to 1 January 2020 |
| `730-111/` | Vollziehungsverordnung zum Bundesgesetz über die Enteignung (SAR 730.111) | 3 | oldest version available, then each consolidated version: 1 September 2005 to 1 January 2018 |
| `740-111-kantonale-geoinformationsverordnung-kgeoiv/` | Verordnung über die Geoinformation im Kanton Aargau (SAR 740.111) | 10 | as enacted, then each consolidated version: 1 January 2012 to 1 January 2026 |
| `751-125/` | Verordnung über die Innerortsstrecken an Kantonsstrassen (SAR 751.125) | 3 | oldest version available, then each consolidated version: 1 January 2010 to 1 January 2022 |
| `751-172-ausnahmetransportroutenverordnung-atrv/` | Verordnung über die Offenhaltung von Versorgungsrouten für Ausnahmetransporte von unteilbaren Lasten (SAR 751.172) | 3 | oldest version available, then each consolidated version: 1 September 2005 to 30 October 2020 |
| `751-211-ksv/` | Kantonsstrassenverordnung (SAR 751.211) | 1 | as enacted, 1 January 2022 |
| `755-112-verkehrssteuerverordnung-vstv/` | Verordnung zum Verkehrssteuergesetz (SAR 755.112) | 1 | as enacted, 1 January 2026 |
| `759-111-vfw-ag/` | Kantonale Verordnung über Fuss- und Wanderwege (SAR 759.111) | 4 | oldest version available, then each consolidated version: 1 September 2005 to 1 January 2022 |
| `764-111-wnv/` | Wassernutzungsverordnung (SAR 764.111) | 2 | as enacted, then each consolidated version: 1 September 2008 to 1 January 2011 |
| `773-211-energiev/` | Energieverordnung (SAR 773.211) | 6 | as enacted, then each consolidated version: 1 September 2012 to 1 January 2026 |
| `781-211-v-eg-uwr/` | Verordnung zum Einführungsgesetz zur Bundesgesetzgebung über den Schutz von Umwelt und Gewässern (SAR 781.211) | 10 | oldest version available, then each consolidated version: 1 July 2009 to 30 August 2026 |
| `785-131-naturschutzverordnung/` | Verordnung über den Schutz der einheimischen Pflanzen- und Tierwelt und ihrer Lebensräume (SAR 785.131) | 1 | one version (the oldest available), 1 January 2010 |
| `785-152-naturschutzbeitragsverordnung-nbv/` | Verordnung für die Bemessung der Beiträge an Massnahmen des Natur- und Landschaftsschutzes (SAR 785.152) | 1 | as enacted, 1 January 2017 |
| `787-331-reusstalverordnung-rtv/` | Verordnung zum Dekret über den Schutz der Landschaft und die Nutzung im Gebiet der Reusstalsanierung (SAR 787.331) | 3 | oldest version available, then each consolidated version: 1 January 2006 to 1 July 2019 |
| `811-411-v-eg-avig-avg/` | Verordnung zum Einführungsgesetz zum Bundesgesetz über die obligatorische Arbeitslosenversicherung und die Insolvenzentschädigung sowie zum Bundesgesetz über die Arbeitsvermittlung und den Personalverleih (SAR 811.411) | 5 | oldest version available, then each consolidated version: 1 January 2010 to 1 April 2022 |
| `811-621-vollziehungsverordnung-zur-bundesgesetzgebung-uber-die-entsandten-arbeitnehmerinnen-und-arbeitnehmer-vea/` | Vollziehungsverordnung zur Bundesgesetzgebung über die flankierenden Massnahmen bei entsandten Arbeitnehmerinnen und Arbeitnehmern und über die Kontrolle der in Normalarbeitsverträgen vorgesehenen Mindestlöhne (SAR 811.621) | 4 | oldest version available, then each consolidated version: 1 September 2009 to 1 July 2024 |
| `811-625-vbgsa/` | Vollziehungsverordnung zur Bundesgesetzgebung gegen die Schwarzarbeit (SAR 811.625) | 2 | as enacted, then each consolidated version: 1 January 2008 to 1 August 2011 |
| `815-211-v-eg-famzg/` | Verordnung zum EG Familienzulagengesetz (SAR 815.211) | 2 | as enacted, then each consolidated version: 1 January 2010 to 1 January 2026 |
| `831-315-elkv-ag/` | Verordnung über die Vergütung von Krankheits- und Behinderungskosten bei den Ergänzungsleistungen (SAR 831.315) | 6 | as enacted, then each consolidated version: 1 January 2011 to 1 May 2024 |
| `831-919/` | Vergütungsreglement der Verwaltungskommission und der Geschäftsleitung der SVA Aargau (SAR 831.919) | 1 | as enacted, 1 January 2016 |
| `831-921/` | Organisationsreglement der SVA Aargau (SAR 831.921) | 2 | as enacted, then each consolidated version: 1 September 2017 to 1 November 2024 |
| `831-973/` | Personalreglement der SVA Aargau (SAR 831.973) | 1 | as enacted, 1 January 2015 |
| `837-112/` | Verordnung über den Vollzug des Unfallversicherungsgesetzes (SAR 837.112) | 1 | one version (the oldest available), 1 January 2006 |
| `837-211-v-kvgg/` | Verordnung zum Gesetz zum Bundesgesetz über die Krankenversicherung (SAR 837.211) | 10 | as enacted, then each consolidated version: 1 July 2016 to 1 September 2026 |
| `851-215-v-casenet/` | Verordnung über den Betrieb des Informationssystems CaseNet im Bereich der häuslichen Gewalt (SAR 851.215) | 3 | as enacted, then each consolidated version: 1 January 2011 to 1 January 2015 |
| `873-311/` | Vollziehungsverordnung zum Gesetz über Massnahmen zur Förderung des sozialen Wohnungsbaues (SAR 873.311) | 1 | one version (the oldest available), 1 January 2006 |
| `873-711/` | Vollziehungsverordnung zum Gesetz über die Förderung des Baues von Alters-, Invaliden- und Familienwohnungen (SAR 873.711) | 1 | one version (the oldest available), 1 January 2009 |
| `910-215-alav/` | Allgemeine Landwirtschaftsverordnung (SAR 910.215) | 4 | as enacted, then each consolidated version: 1 August 2012 to 1 March 2026 |
| `911-351-alk-verordnung/` | Verordnung über die Aargauische Landwirtschaftliche Kreditkasse (SAR 911.351) | 3 | as enacted, then each consolidated version: 1 August 2012 to 1 March 2026 |
| `913-761-vsv/` | Verordnung über die Strukturverbesserungen (SAR 913.761) | 3 | as enacted, then each consolidated version: 1 August 2012 to 1 May 2019 |
| `914-111-vdzb/` | Verordnung über Direktzahlungen und Beiträge (SAR 914.111) | 2 | as enacted, then each consolidated version: 1 May 2019 to 1 July 2024 |
| `915-712-weinbauverordnung/` | Verordnung über den Weinbau (SAR 915.712) | 7 | as enacted, then each consolidated version: 1 September 2008 to 1 January 2025 |
| `931-111-awav/` | Verordnung zum Waldgesetz des Kantons Aargau (SAR 931.111) | 7 | oldest version available, then each consolidated version: 1 January 2009 to 1 November 2024 |
| `933-211-jagdverordnung-des-kantons-aargau-ajsv/` | Verordnung zum Jagdgesetz des Kantons Aargau (SAR 933.211) | 6 | as enacted, then each consolidated version: 1 January 2010 to 30 August 2025 |
| `935-211-aargauische-fischereiverordnung-afv/` | Verordnung zum Fischereigesetz des Kantons Aargau (SAR 935.211) | 5 | as enacted, then each consolidated version: 1 July 2013 to 1 May 2026 |
| `940-111-standortforderungsverordnung-sfv/` | Verordnung zum Gesetz über die Standortförderung (SAR 940.111) | 2 | as enacted, then each consolidated version: 1 January 2010 to 1 November 2012 |
| `951-175/` | Vollziehungsverordnung zum Bundesgesetz über das Gewerbe der Reisenden (SAR 951.175) | 2 | as enacted, then each consolidated version: 1 January 2003 to 1 January 2021 |
| `951-511/` | Verordnung über die Preiskontrolle (SAR 951.511) | 1 | one version (the oldest available), 1 September 2007 |
| `953-311-vv-kkg/` | Vollziehungsverordnung zum Bundesgesetz über den Konsumkredit (SAR 953.311) | 3 | oldest version available, then each consolidated version: 1 January 2009 to 1 July 2024 |
| `957-111/` | Verordnung zur Bundesgesetzgebung über das Messwesen (SAR 957.111) | 2 | as enacted, then each consolidated version: 1 January 2014 to 1 January 2023 |
| `959-312-gsv/` | Geldspielverordnung (SAR 959.312) | 2 | as enacted, then each consolidated version: 1 January 2021 to 1 July 2024 |
| `961-211-v-eg-arr/` | Verordnung zum Einführungsgesetz zum Arbeitsrecht (SAR 961.211) | 4 | as enacted, then each consolidated version: 1 September 2012 to 1 September 2025 |
| `970-111-gastgewerbeverordnung-ggv/` | Verordnung über das Gastgewerbe und den Kleinhandel mit alkoholhaltigen Getränken (SAR 970.111) | 7 | oldest version available, then each consolidated version: 1 September 2005 to 1 March 2025 |
| `991-111-strassenverkehrsverordnung-svv/` | Verordnung über den Vollzug des Strassenverkehrsrechtes (SAR 991.111) | 8 | oldest version available, then each consolidated version: 1 January 2010 to 1 July 2024 |
| `995-811/` | Verordnung über Bewilligungen für die Personenbeförderung (SAR 995.811) | 2 | oldest version available, then each consolidated version: 1 September 2005 to 1 July 2024 |
| `997-111/` | Verordnung über die Schifffahrt (SAR 997.111) | 5 | oldest version available, then each consolidated version: 1 January 2009 to 1 July 2024 |

## Source

The SAR (systematic collection) of the canton, published by the canton at <https://gesetzessammlungen.ag.ch/>. For each act it gives every consolidated version it holds, with the day each version took effect, and a change table listing each amendment: its decision date, the day it took effect, the provision it touched and its entry in the chronological collection (AGS). Annexes the collection publishes only as separate PDF files are not included.

## Dates

- Each commit is dated at **noon, Europe/Zurich, on the day the version took effect**, as the collection gives it ("in Kraft seit / von"). The decision date of each amending act is the `Enacted:` trailer.
- An act's first commit is its oldest version in the collection. It is credited to the act as enacted only when the change table shows no amendment in force before it; otherwise it is the "oldest version available", naming the earlier amendments.
- Versions that take effect after the retrieval day are on the `zukunft` branch, never merged into `main`.
- `--before="YYYY-MM-DD"` alone uses your clock's time of day; use `T23:59:59Z` or `tools/on.py`.

## Files

`<act>/art-005.md` is Art. 5 (or § 5), `art-005a.md` Art. 5a; `ingress.md` holds the title, date and preamble; `gliederung.md` the section headings; `schluss.md` the closing formula and signatures. One paragraph or list item per line. Amendment markers (`*`), footnote numbers and the "Stand" date are left out.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of the canton's own text of that version, and every article's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the amending act, named by its entry in the chronological collection (AGS), with an e-mail address that cannot exist (`<act key>@gesetzessammlungen.ag.ch.invalid`). Where one version holds changes by several amending acts and the change table does not say which provision each one touched, the commit names them all. The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one the canton publishes as binding (its chronological collection, or its systematic collection where cantonal law makes that binding). The history starts with the oldest consolidated version the collection holds for each act, which for many acts is later than the act's enactment. Only the acts listed above are included.
