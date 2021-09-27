CODEBUCH							
Im Codebuch definieren Sie, wie und nach welchen Kriterien erfasst werden.							
Achtung: das Codebuch wird immer als eigene Datei in Github gesetzt. Beispiel siehe hier.							
Wert	Kommentar						
edgelist	Grundregel: Die Edgelist darf pro Spalte immer nur einen Wert enthalten. Bis auf die ID idealerweise numerisch codiert (als Zahl).						
from	definiert den Sender in gerichteten Netzwerken. Entspricht ID in der Nodelist. Keine Sonderzeichen, nur ein Wort						
to 	definiert den Empfänger in ungerichteten Netzwerken. Entspricht ID in der Nodelist. Keine Sonderzeichen, etc. 						
weight	1=no, 2=weak, 3=strong						
enemy	1=yes, 2=no						
							
nodelist	Grundregel: die IDs der Nodelist müssen mit den IDs der Edgelist komplett übereinstimmen. Ausprägungen der Attribute in der Regel numerisch definieren.						
id	eindeutige Identifikation jedes einzelnen Knotens (vertex), der erfasst wird.  						
name	Name oder Bezeichnung des Knotens. 						
sex	1=female, 2=male, 3=divers						
age	1= young, 2= middleage, 3=old						
species	1=human 2=not human						
							
							
NA	definiert fehlende Werte, bei der Datenerhebung das Feld einfach leer lassen, R rechnet NAs (missing values) automatisch raus..						
							
Bearbeitungshinweise							
Achten Sie bitte auf die Kommentare in den Spalten. Diese erklären genauer, welche Daten erfasst werden. 							
Sie sehen die Kommentare, wenn Sie auf die entsprechende Spalte gehen. 							
Skizzieren Sie zunächst Ihr Netzwerk bzw. die Daten, die für Sie relevant sind. 							
Welche Informationen wollen Sie erheben? Wie müssen diese erfasst sein?							
Legen Sie bitte im Codebuch möglichst genau fest, wie die Daten erhoben werden (Codebuch)							
Bitte verwenden Sie keine Sonderzeichen in der Erfassung, dazu gehören Satzzeichen, Umlaute, etc.							
Verpflichten Sie alle Teammitglieder darauf, das Codebuch zwingend einzuhalten. 							
Wer seine Daten nicht sauber erstellt muss diese nachbereinigen.							
Dokumentieren Sie jeden Schritt Ihrer Datenerfassung mit, um dies zu rekonstruieren.							
Nutzen Sie das Skript zur Datenbereinigung auf dem letzten Reiter!							
Beispiel für die Dokumentation von Codebuch, Edge- und Nodelist							
https://github.com/hdm-crpr/226305/tree/master/data/crpr2							
Vergeben Sie stets eindeutige Spaltenbeschriftungen. Am besten immer nur ein Begriff ohne Sonderzeichen etc.							
