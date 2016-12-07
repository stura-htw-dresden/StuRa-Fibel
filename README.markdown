# StuRa-Fibel

Was man über den StuRa wissen möchte – für Einsteiger in die Studentische Selbstverwaltung

Eine Schamlose Raumordkopie [aus dem Plone](http://www.stura.htw-dresden.de/stura/ref/qm/stu-ve/fibel/die-fibel-als-text) 

Inhaltlich waren u.a. Riegel@StuRa und Volke@StuRa am Werk.

## Lokal bauen

Hier als Beispiel wie man zu einer PDF-Datei kommt.

```bash
git clone git@github.com:stura-htw-dresden/StuRa-Fibel.git stura-fibel
cd stura-fibel
git submodule update --init img/logo
make pdf
```

Andere Formate wie e-PUB, ODT, HTML entsprechend.

## Aufräumen

Um Zwischenformate und Logs loszuwerden dient:

```bash
make clean
```

Um auch Zielformate zu entfernen:

```bash
make cleanall
```

## Lizensierung

### Inhalte der Fibel

${tbc:Muss noch geklärt werden, s. #1}

