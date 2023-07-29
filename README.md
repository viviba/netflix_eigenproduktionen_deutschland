# CODEBUCH					
					
# Edgelist  	

from = Akteur/innen  

to = Serien 	

relationship =

1 Regisseur/in 

2 Autor/innen 

3 beides

4 Produktionsfirma				

# Nodelist					
id = Kürzel	

name = Vor- und Nachname 

sex =

1 male 

2 female 

3 divers

university = Uni/Hochschule an der Protas studiert haben (als Eigenname codiert)

university_short = Kürzel der jeweiligen Uni/Hochschule

awards = Welche Preise/Auszeichnungen haben die Akteur/innen bekommen? (als Eigenname codiert)

type =

1 Akteur/innen 

2 Serien	

genre = 

1 fantasy

2 comedy

3 rom com 

4 crime 

5 mockumentary

6 drama 

7 young adult		

rating = durchschnittliche Zuschauerquote der Episode in Prozent	

year = Erscheinungsjahr	der Episode

country = Herkunftsland der Episode

location = Ort national

Bearbeitungshinweise					
Wir erstellen ein Two-Mode-Netzwerk, weil wir sowohl Akteur/innen-Knoten, als auch Serien-Knoten im Netzwerk haben. Dazu brauchen wir Infos über Regisseur/innen, Autor/innen und die Produktionsfirmen. Diese erheben wir auf der Website "IMDb", eine Filmdatenbank. Wichtig ist für uns aber auch, wo die Akteur/innen studiert haben und ob sie Preise für ihre Arbeit bekommen haben. Infos zur Serie, wie z.B. das Genre, das Erscheinungsjahr oder das Rating bekommen wir auf "Rotten Toamtoes", eine Website, die vor allem Filmkritiken und News veröffentlicht. 
Sollte unser Netzwerk zu wenig Daten beinhalten, wollen wir es erweitern: Zum Beispiel durch die Vorerfahrungen der beteiligten Regisseur/innen. 				
