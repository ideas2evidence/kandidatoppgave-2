
### Kandidatoppgave 2

Kandidatoppgaven består av to deloppgaver. Én skriveoppgave, og én analyseoppgave i R eller Python. Du velger selv hvordan du ønsker å dele arbeidet (Word, Jupyter Notebook, R Markdown, LaTex). 

#### Skriveoppgave 
Tabellen og figuren under er basert på analyser av Kandidatundersøkelsen 2018 for Universitetet i Bergen, NHH og Høgskolen på Vestlandet. Figuren viser resultatene fra en regresjonsanalyse der estimater på høyre side indikerer en positiv effekt på jobbrelevans (dvs. om kandidatene er i relevant arbeid eller ikke). Kan du kommentere tabellen og grafen slik du ville gjort det i en rapport beregnet på et publikum som ikke er metodespesialister? Bruk ca en side.

|                   |Hjemsted før studier   |	Hjemsted nå |Nettogevinst   |
|---                |---:                   |---:           |---:           |
|Akershus           |5,6 %                  |2,8 %          |2,8 %          |
|Hordaland          |36,9 %                 |44,6 %         |7,7 %          |
|Oslo               |5,8 %                  |17,0 %         |11,2 %         |
|Rogaland           |13,9 %                 |10,1 %         |-3,7 %         |
|Sogn og Fjordane	|10,4 %                 |6,5 %          |-3,9 %         |
|Østfold            |2,0 %                  |1,0 %          |-1,0 %         |
|Hedmark            |1,1 %                  |0,7 %          |-0,4 %         |
|Oppland	        |1,2 %                  |0,6 %          |-0,6 %         |
|Buskerud           |2,4 %                  |1,7 %          |-0,7 %         |
|Vestfold           |2,4 %	                |1,2 %	        |-1,3 %         |
|Telemark	        |1,7 %	                |0,7 %	        |-1,0 %         |
|Aust-Agder	        |1,2 %	                |0,6 %	        |-0,7 %         |
|Vest-Agder	        |1,6 %	                |0,8 %	        |-0,8 %         |
|Møre og Romsdal	|5,1 %	                |3,0 %	        |-2,0 %         |
|Trøndelag	        |2,8 %	                |2,1 %	        |-0,8 %         |
|Nordland	        |0,8 %	                |0,7 %	        |-0,1 %         |
|Troms	            |0,7 %	                |1,0 %	        |0,3 %          |
|Finnmark	        |0,3 %	                |0,7 %	        |0,4 %          |
|Utenfor Norge	    |4,0 %	                |4,2 %	        |0,2 %          |

<img src="/resources/regresjon.png" width="500"/>


#### Analyseoppgave

Bruk R eller Python i denne oppgaven. 

Med utgangspunkt i ESS-data, lag et datasett med aggregert statistikk (etter land og år) om tillit til demokratiet. Velg ut et land du ønsker å fokusere på og presenter funnene dine grafisk. Grafikken bør inneholde en sammenligning til øvrige europeiske land. Gjør rede for hensyn du tar underveis og aggregeringsmetode.

ESS-data er tilgjengelig her: http://www.europeansocialsurvey.org. Du må lage en bruker. Det er gratis. 
