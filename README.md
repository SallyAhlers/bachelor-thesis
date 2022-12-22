# bachelor-thesis
Recognition of spatial entities in german 19th century novels with Machine Learning

Dieses Repository dient zur Dokumentation und Versionsverwaltung der in der Bachelorarbeit verwandter Dateien.

Es basiert auf dem Korpus ELTeC-deu-1.0.0, dem deutschen Teilkorpus der European Literary Text Collection. 
Dieser besteht aus hundert deutschsprachigen Romanen, die zwischen 1840 und 1920 publiziert wurden. 
Die Datei "Textkorpus Ground truth" besteht aus je einer zufällig ausgewählten Seite pro Roman.
Eine Kopie des Teilkorpus wurde mit Raumentitäten ausgezeichnet ("Textkorpus Ground truth mit Entities"). 
Dabei wurde unerschieden zwischen Eigennamen, wie "Berlin" oder "Atlantis" und Gattungsbegriffen, wie "Fluss" oder "Zimmer".
Die Ground truth kann in dieser Form oder nach Hinzufügung weiterer Tags für ein Training eines Named Entity Taggers genutzt werden.
Ein mit der Ground truth trainierter Tagger kann an dem "Korpus ELTeC-deu-1.0.0 ohne Trainingsseiten" erprobt werden. 
Die Auszeichnung der XML-Dokumente basiert auf den TEI Guidelines.
