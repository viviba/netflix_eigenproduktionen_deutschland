# CODEBUCH					
					
# Edgelist  	

from = Akteur/innen  

to = Serien 	

relationship =

1 Director 

2 Writer

3 Executive Producer


# Nodelist					
id = Kürzel	

name = Vor- und Nachname 

sex =

1 male 

2 female 

3 divers

university = Uni/Hochschule an der Protas studiert haben (als Eigenname codiert)

university_short = Kürzel der jeweiligen Uni/Hochschule

awards = 

1 = 1-3 Preise

2 = 4-5 Preise

3 = über 5 Preise


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

rating = IMDb-Bewertung als Kommazahl von ingesamt 10	

year = Erscheinungsjahr	der Episode

country = Kürzel Herkunftsland der Episode 

location = Ort national (als Eigenname codiert)

Bearbeitungshinweise					
Wir erstellen ein Two-Mode-Netzwerk, weil wir sowohl Akteur/innen-Knoten, als auch Serien-Knoten im Netzwerk haben. Dazu brauchen wir Infos über Regisseur/innen, Autor/innen und die Produktionsfirmen. Diese erheben wir auf der Website "IMDb", eine Filmdatenbank. Wichtig ist für uns aber auch, wo die Akteur/innen studiert haben und ob sie Preise für ihre Arbeit bekommen haben. Infos zur Serie, wie z.B. das Genre, das Erscheinungsjahr oder das Rating bekommen wir ebenfalls auf "IMDb".
Zusätzlich dazu erheben wir noch die Produktionen, an denen unsere Akteur*innen in den letzten 10 Jahren noch mitgearbeitet haben.
