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
