peaCTF Writeup

Hide and Seek

Man muss eine Datei in einer großen Anzahl an verschachtelten Ordnern finden, die dann die flag enthält.

	``find . -name '*.txt'``

Damit findet man alle .txt Dateien. Ich bin einfach davon ausgegangen, dass es sich um eine solche handelt. Und es wurde tatsächlich eine gefunden:

	``50e7b5daefd7eb3f35850d/02a31fe6237ce5572f09056c739de049/12f54ae8d933ceaf8c231aabc50a012c/65e206272e52bbe57a8c7be83f18690d/cb3f829a585b40084927c47099ea68be/flag.txt``
	Irgendwie gibt es die Datei nicht -- vielleicht fehlerhaft kopiert.

Nach ein wenig rumprobieren kam ich dann zu dem Script:

Erst muss man die gefundene Datei in einer .txt Datei abspeichern. Dann baut man darum sein bash script:

	``#! /bin/bash

	cat <hier steht dann der Dateipfad>``

Danach führt man das Skript aus dem ersten Ordner aus, in dem man gestartet hat.

Tadaaa das ist die flag: flag{peactf_linux_is_fun_5b7b6e37ae9984ec6332d8eebd9b59d0}