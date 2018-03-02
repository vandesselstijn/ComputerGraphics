# Opgave1

Er is weer eens een enquete afgenomen bij de studenten. Hierbij werd naar het
tijdsgebruik van studenten geinformeerd. Hoeveel uren per week de student
doorbracht met studeren en andere nuttige bezigheden. De enquete liep maar
over een beperkte periode (van startweek tot eindweek ).

Gevraagd: een staafdiagramma dat een overzicht geeft van het totaal aan 
	tijd dat er per week gebruikt is. 
	Als x-as kan je de weeknummers gebruiken.
	Als y-as de gebruikte tijd.

Als uitbreiding kan je ervoor zorgen dat als de gebruiker een bepaald karakter
indrukt, hij een lijn extra krijgt die de toppen van de staven verbindt. Met
een ander karakter kan de gebruiker de waarden op de y-as vermelden en verbinden
met de overeenkomstige staaf. Het esc-kar gebruiken om te stoppen.

De datafile is aanwezig en heeft de volgende structuur:
	een int voor de startweek,
	een int voor de eindweek,
	een aantal structuren van het volgende type
		typedef struct gebruik
        		{
            		char naam[NLEN];
            		int uren[WLEN];
        		} Gebruik;
	met #define NLEN 11 en #define WLEN 53

Een voorbeeld van de makefile is ook aanwezig.

