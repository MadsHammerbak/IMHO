# IMHO
Gruppe IMHO - Eksamensquiz

KRAVSPECIFIKATION 

BESKRIVELSE: 

Applikationen skal fungere som eksamenstræning for de studerende på ha(it). Rent praktisk skal en administrator (forelæser) oprette pensum relaterede multiple choice quizzes. Alle brugerne skal kunne tilgå quizzes og forsøge at besvare dem, få resultatet udskrevet.
					
SERVER: 	
- Serveren skal kunne validere login baseret på et hashet password.
- Serveren skal kunne oprette og opdatere en bruger.
- Serveren skal udstille et API, som gør det nemt at udarbejde klienter der kan trække på serverens funktionalitet. API’et skal dække følgende funktionaliteter:
	- En gæst skal kunne oprette sig som bruger
	- En bruger skal kunne logge ind/ud
	- En bruger skal kunne tilgå en quiz under et respektivt fag
	- En admin skal kunne oprette en quiz
	- En admin skal kunne opdatere en quiz (tilføje spørgsmål, redigere spørgsmål og slette spørgsmål)
	- En admin skal kunne slette en quiz

KLIENT:
- Klienten skal kunne tilgå loginsiden samt logge ind.  
- Klienten skal kunne oprette sig som bruger
- Klienten skal kunne tilføje quiz til de respektive fag samt svar. 
- Klienten skal kunne opdatere en quiz
- Klienten skal kunne slette quizzen
- Klienten skal kunne tilgå quiz relateret til det specifikke fag
- Klienten skal kunne vælge quizzen samt tage den. 
- Klienten skal kunne vise svarene på de enkelte spørgsmål.
- Klienten skal vise samlet score udfra brugerens svar.
- Klienten skal ud fra brugertype se forskellige menuer. 

IDEER TIL VIDEREUDVIKLING: 
- Gemme resultater samt se statistik. 
- Glemt password
- Admin godkende brugere 
- Slette/blokere spørgsmål - hvordan?		
- Brugere skal kunne oprette spørgsmål
- Server skal kunne slette brugere
- Kommentarer til quiz

KLASSER:
- scr
	- main
		- ResponseHandler
		- Server
		- Database
			- UserTable
			- TopicTable
			- QuizTable
			- QuestionTable
		- Endpoints
		- Models
			- User
			- Topic
			- Quiz
			- Question
		- Utility
			- Digester

ER DIAGRAM:
- g
- g


