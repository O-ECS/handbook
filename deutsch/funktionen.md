# Funktionen
## (Sammelfunktion oecs_all())[https://github.com/O-ECS/handbook/tree/main/deutsch/funktionen]
Mit der Sammelfunktion oecs_all() kann das Screening mit Hilfe einer Exceldatei gesteuert werden. Dies vereinfacht die Anwendung und das Sichern der 

## Basisfunktionen
### oecs_init()
Mit der Funktion oecs_init() wird die Verbindung zur LimeSurvey-Installation hergestellt.

### oecs_create()
Mit der Funktionen oecs_create() wird in LimeSurvey eine neue Umfrage mit Token für die Teilnehmenden angelegt. Um die Funktion aufzurufen muss eine Verbindung zu LimeSurvey installiert werden.

### oecs_letter()
Mit der Funktion oecs_letter() werden versandfertige Einladungen für das Screening erstellt. Die Vorlagen sind in einfachem HTML und CSS und können angepasst werden.

### oecs_evaluate()
Mit der Funktion oecs_evaluate() wird der Rücklauf ausgewertet und die ausstehenden Teilnahmen gelistet.

### oecs_compare()
Mit der Funktion oecs_compare() werden die Daten mit den Umfragen von anderen verglichen. Dies kann bei der Interpretation der Werte helfen.

### oecs_open_science()
Mit der Funktion oecs_open_science() werden die anonymität der Daten sichergestellt und anschliessend in die gemeinsame Datensammlung eingetragen. Damit wird die Evaluation der Screeninginstrumente sowie Forschung ermöglicht.
