## 1. Text-Editor der Wahl
Spyder

## 2. Eine Python-Bibliothek
Pyxel. Diese Bibliothek ermöglicht es mittels eines Baukastens Spiele 
mit 16 Farben und 4 Sounds im Retro-Design zu entwickeln.
Die Bibliothek bietet mir aufgrund meiner Gaming-Passion eine hohe Motivation kreativ neue Spiele zu entwickeln und mich intensiver mit der Programmierung zu beschäftigen. 

## 3. Eine Fehlermeldung und Ihre Lösung
#Fehlermeldung: KeyError Traceback (most recent call last) in ----> 1 pmid_data["result"]["title"]
#Lösung: print(Titel:" pmid_data ["result"] [str(pmid)]["title"])
```
for pmid in pmids:
    full_url = base_url + pmid
    pmid_json_data = urllib.request.urlopen(full_url).read()
    pmid_data = json.loads(pmid_json_data)
    print(pmid)
    print("Titel: " + pmid_data ["result"] [str(pmid)]["title"])
    print("Erscheinungsdatum: " + pmid_data ["result"] [str(pmid)]["pubdate"])
    print()
 ```
## 4. Was ist JupyterLab?

JupyterLab ist die Weiterentwicklung des Juypter Notebooks.
Das Juypter Notebook ist eine web-basierte Computerumgebung, deren Aufgabe es ist das darstellen von Daten zu ermöglichen.
JupyterLab hingegen ist das Upgrade welches es ermöglicht simultan auf mehreren Tabs/Notebooks in einem Fenster zu arbeiten.

## 5. San Francisco
Ergebnissanalyse:

Zu Frage 1
Durch das Filtern mit den keys war es möglich ausschließlich die geforderten Werte für meine Fragestellung herauszusuchen. Ein simples wechseln mithilfe von "#" zwischen der print- und der Headausgabe ermöglichte mir schnell die benötigten Informationen strukturiert zu auf einen Blick zu sehen. Hierbei fiel besonders die Bibliothek in Richmond im Mai 2015 auf. Deren Erneuerungen bei Senioren betrug 487 und lag somit weit über den Vergleichswerten.

Zu Frage 2

Mir war es nicht möglich mehrere tables zusammenzuführen. Im ersten Schritt, also dem zusammenführen von zwei tables war es mir möglich, den weiteren Schritt konnte ich nicht ausführen. 
