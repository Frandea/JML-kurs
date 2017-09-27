# JML-kurs
Jeeves Academy 2017-09-27 o 2016-09-28

## Inledning
Välkommen till (grund-)kursen i JML, Jeeves Macro Language.
Kursen kommer att lära dig att använda, skriva och förstå Jeeves-makron.
Kursen är grundläggande och för att du ska bli riktigt duktig på begreppen och användningsområdena måste du arbeta praktiskt med makron och/eller delta i en fördjupande kurs.
## Innehåll
- Kursmoment
	- Grunder
		* Klargör bakgrunden till begreppet makron. Bättre att kalla det skriptspråk.
		* Börja genom att kolla hjälpen
		* Klargör kopplingen till Appl.ufu
		* Klargör begränsningarna
		* Visa exempel på hur makron används
		* Vilka delar av Jeeves omfattas av möjligheten att använda makron? Formulär, Listor, Rapporter...?
		* Datatyper
		* Inbyggda kommandon
		* SQL
		* Null-värdet
		* Datumhantering
		* Händelser
    
	- Hur man skriver makron
		* Editorn
		* Stomme/struktur
		* Namnstandard
		* Mallar
	
	- Hur makron kopplar till aktuell post
		* I Read Only-läge
		* I redigera-läge
	
	- Hur makron kommer åt och manipulerar data
		* Postbufferten
		* SQL
	
	- Avancerat
		* Debugging
		* Tracing
		* Timingeffekter
		* DDL
		* UFU replacements
		
	- Exempel/övningar
		* Enkel input/output, hämta värden och läsa input genom dialog
		* Manipulera datum
		* Manipulera sträng-/textdata
		* Läsa befintligt makro och felsöka

## Målsättning
## Förutsättningar
### Fält att lägga till
`Termnamn` | `Termtyp` | `Ledtext` | `Kolumnrubrik` | `Maxlängd`
------- | ------- | ------- | ------- | -------
`q_jis_GTIN13` | `ztstring` | `GTIN-13 Code` | `gtin13 code` | `13`
`q_jis_NoOfLabels` | `ztinteger` | `No of labels` | `no of lbl`
`q_jis_InkVolume` | `ztfloat` | `Ink Volume` | `ink vol`
`q_jis_QATestReqmnt` | `ztboolean` | `QA Test Required` | `qual test req`
`q_jis_QATestValidThru` | `ztdate` | `QA Test Valid Thru` | `test valid dt`
