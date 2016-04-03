# Triathlon Hamburg Everyman Olympic Men 2009–2015

> “A triathlon is a multiple-stage competition involving the completion of three continuous and sequential endurance disciplines. [...] The first modern swim/bike/run event to be called a 'triathlon' was held at Mission Bay, San Diego, California on September 25, 1974.” (from Wikipedia, the free encyclopedia) 

##Research questions:

- How well balanced is this competition format?
- Are all disciplines equally important?
- Do some athletes have an advantage over others?

##Procedure: 

To answer the questions formulated above I have collected and aggregated data from the “Triathlon Hamburg Everyman Olympic Men” from 2009 to 2015. The Triathlon Olympic Distance consists of 1.5 km swimming, 40 km biking and 10 km running. The [ITU World Triathlon Hamburg](http://hamburg-triathlon.org/) (known 2009–2012 as Dextro Energy Triathlon ITU World Championship Hamburg and ITU World Triathlon Hamburg since 2013)  claims to be known as the “The World's Biggest Tri” with more than 10,000 participants (actually the London Triathlon – currently known as the “AJ Bell London Triathlon”, and previously the “Virgin Active London Triathlon”, “Mazda London Triathlon” and the “Michelob ULTRA London Triathlon”, for sponsorship reasons – attracts more than 13,000 competitors, but is not an event of the International Triathlon Union). Elite athletes have to qualify to participate in the [ITU World Triathlon Series](https://en.wikipedia.org/wiki/ITU_World_Triathlon_Series). So-called “everyman” competitors howevers can sign up for the sprint distance (0,5km/22km/5km), the olympic distance (1,5km/40km/10km) or the relay together with friends (“Staffel”), family (“Staffel Familienwertung”) or colleagues (“Staffel Firmenwertung”). The number of places for solo competitors is strictly limited, and usually sold out well in advance. 

The swimming course is located in the Alster, a backed-up river with little current, creating a mild open water situation. The remaining course runs through the city center (Rathausmarkt) and along Reeperbahn, Elbchaussee and Alster's riverside, and has little difference in altitude (“mostly flat [bike] course” and “complete flat run course without any ascents”). Due to the large number of competitors the transition zone is exceptionally long with 800 m. For more information on the course see http://hamburg-triathlon.org/en/info/course/. 

2013 was exceptional, when everyman competitors where split up into two races taking place on Saturday *and* Sunday. 

## Data source

Timekeeping & Result Service is provided by mika:timing using reusable transponders and multiple measuring/check points. 

- [mika:timing](http://mikatiming.de/)
    - July 25–26, 2009 <http://hamburg-itu.r.mikatiming.de/2009/>
    - July 17–18, 2010 <http://hamburg-itu.r.mikatiming.de/2010/>
    - July 16–17, 2011 <http://hamburg-itu.r.mikatiming.de/2011/>
    - July 21–22, 2012 <http://hamburg-itu.r.mikatiming.de/2012/>
    - July 19–20, 2013 <http://hamburg-itu.r.mikatiming.de/2013/>
    - July 12–13, 2014 <http://hamburg-itu.r.mikatiming.de/2014/>
    - July 18–19, 2015 <http://hamburg-itu.r.mikatiming.de/2015/>

## Participants not included in the sample: 
- DNS (Did Not Start) 
- DNF (Did Not Finish) 
- DQ (Disqualified) 
- participants missing split times

## Information removed from the sample: 
- club 
- (multiple) split check points 
- DQ 
- time penalties 

## Anomalies and measurement errors 
Transitions T1 and T2 show several cases of impossible and improbable times (e.g. 55 participants with T1 < 01:30, 78 participants with T1 < 03:00, 6 participants with T2 < 02:00). The transition zone is about 800 meters long. 

There is no way to determine if extreme outliers (i.e. times > 6 * standard deviation) are due to measurement errors or other factors e.g. late start, flat tire, collision with other participant(s). 

## Coding 
- Inconsistencies in Age Class (also: Age Group) labels (e.g. AK4 or MAK4) have been standardized (to include the letter M for male participants). 
- Inconsistencies in three-letter country codes with Nationality have been solved by applying ISO 3166-1 alpha-3 (NED > NLD, DEN > DNK, ROM > ROU, CRO > HRV, SUI > CHE, RSA > ZAF, POR > PRT, CHI > CHL). 
- Competitors with inconsistent nationality have been reduced to one (predominant nationality if uneven; non-German in tied cases; first reported nationality where only non-German nationalitites given): 
    - ernesto-rogge (5* GER, 1* CHE) 
    - etienne-junot (3* FRA, 1* GER) 
    - farid-najem (2* AFG, 2* GER) 
    - ferran-canet (1* ESP, 1* GER) 
    - florian-berger (1* AUT, 1* GER) 
    - frank-rusche (2* NLD, 1* GER) 
    - hassan-abdel-meguid (1* EGY, 1* GER) 
    - helmut-cordes (1* DJI, 1* GER)
    - joachim-doeding (1* BRA, 1* GER) 
    - jos-meijerhof (1* GER, 2* NLD) 
    - karsten-elias (2* GER, 3* EGY) 
    - klaus-huppertz (1* NLD, 1* GER) 
    - marcos-fadul (2* GER, 1* ARG) 
    - marcus-leaver (4* GBR, 1* GER) 
    - marios-winding (1* CIV, 2* DNK, 3* GRC) 
    - mark-van-der-merwe (1* ZAF, 1* GER)
    - michael-niermann (1* GER, 1* SGS) 
    - michael-schenk (1* GER, 1* NLD) 
    - michael-schmid (1* AUT, 1* GER) 
    - mike-fehrs (1* CHE, 1* GER)
    - paul-lockwood-lee (1* GBR, 1* VGB) 
    - raul-campos (1* GER, 1* PRT) 
    - robin-de-ruiter (2* NLD, 1* GER) 
    - siegfried-pillmann (5* GER, 1* EGY) 
    - spyridon-foundas (1* GER, 1* GRC) 
    - thomas-blades (3* GBR, 1* GER) 
    - thomas-dziubinski (3* GER, 1* ALG) 
    - thomas-goetz (1* CHE, 1* GER) 
    - urs-pargaetzi (2* CHE, 2* GER) 

## Naming convention 
- Since names of competitors are self-reported, names are not consistent. To better recognize competitors between events, the names have been sanitized and stored in the colum “nicename”. 
    - Names have been rearranged (from “Last Name, First Name” to “First Name Last Name”). 
    - All letters have been transformed to lower case. 
    - Diacritics have been changed into base characters (á, å, é, è, í, ó, ú), Umlaute transcribed (ä > ae, ö > oe, ü > ue), ß transcribed with ss. 
    - Titles have been removed (e.g. B.Sc., Dipl.Bau I, Dipl.-Betr , Dipl. Bibl, DiplIng, Dipl-Ing, Dipl. Ing., Dipl.-Ing. Dipl.Ing., Dipl Kfm, Dipl. Wirt, Dipl.vet., Dr, Dr., Dr. Dr., Dr.-Ing., Dr. med, Dr. med., Dr.med., Lic., Prof. , Prof. Dr., Prof.Dr.)
    - Abbreviations (e.g. gen.) have been removed. 
    - Spaces have been replaced by n-dash signs, dots removed. 
