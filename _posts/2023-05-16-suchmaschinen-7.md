---
title: "Lerneinheit 9: Suchmaschinen und Discovery-Systeme"
date: 2023-05-16
---

# Intro

Nach der letzten Lerneinheit habe ich mir erhofft, dass die heutige ein bisschen klarer verläuft als die Thematik der Transformation von Metadaten. Heute geht es darum sich einen Überblick zu erschaffen über die Suchmaschinen und Discovery-Systeme. Und dabei arbeiten wir heute mit zwei Testservern: VuFind und Solr.

# VuFind und Discovery-Systeme

Als erstes ging es darum die Open-Source-Software VuFind zu installieren um die angesprochenen Discovery-Systeme zu verwenden. Mithilfe der Software können wir später auf Ressourcen aus Bibliotheken zugreifen. Aber was sind Discovery-Systeme?

Nach mehreren Semestern als IW-Studentin kenne ich die klassischen Standards der Bibliothekskataloge und das beste Beispiel dafür sind die OPACs. Diese helfen den BenutzerInnen von Bibliotheken nach Medien (in den Beständen) zu suchen. Und wenn wir schon von Such(maschinen) reden, dann ermöglichen solche Systeme Begriffe in das Suchfeld einzugeben und durch den Bibliothekskatalog relevante Treffer zu erhalten.

Und die Weiterentwicklung zum klassischen Bibliothekskatalog sind die Discovery-Systeme und dafür haben wir in der Vorlesung VuFind (installiert) verwendet. Und wie immer handelt es sich, typisch für das Modul, um eine Open-Source-Software, die sozusagen als eine weiterentwickelte Form eines Bibliothekskatalogs dient. Hierbei setzt die Software darauf, dass die Suche nach den Ressourcen verbessert ist und noch benutzerfreundlicher.

Aber um VuFind starten zu können, gebraucht es noch der Open-Source-Software Solr, mit der man es schafft eine effektive Volltextsuche und Indizierung der Daten zu ermöglichen. Dabei verwendet VuFind Solr als eine Art Backend-Suchmaschine, damit deren Suchfunktionen in seinem (Discovery-)System zu verbessern respektive unterstützen. Also kann das eine nicht vom anderen separat fungieren, soweit ich es verstanden habe. Über sogenannte APIs, das sind Programmierschnittstellne, kommuniziert VuFind mit Solr um deren Suchanfragen an Solr zu stellen und dann die Ergebnisse abzurufen.

Aber in der heutigen Lektion haben wir die beiden Softwares separat begutachtet und in Übungen miteinander verglichen. Ich werde weniger auf die Übungen selbst eingehen als auf die Ergebnisse. Auch wenn ich persönlich den Nutzen beider Software in der gemeinsamen Arbeit sehe, haben wir in der Diskussion darüber geredet das Solr mehr Informationen liefert in den Trefferlisten. Und auch haben wir festgestellt, das ein oder zwei Funktionen bei den beiden Software jeweils offener oder versteckter integriert wurde. So findet man bei VuFind die Facettierung direkt, während bei Solr diese recht versteckt ist.

# Marktüberblick Discovery-Systeme 

Gegen Ende gab es wieder mal einen Überblick des Marktes wenn wir schon Discovery-Systeme im Unterricht behandeln.


# Mood of the day

Im Vergleich zu der letzten Lerneinheit war diese Vorlesung das reine Paradies (der vollständigen Verständlichkeit):

![Paradies](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTsVSFm_1-kHHFTSmDMt6j1RCOwTsN_UP-BcE8UTvvK&s)


![Anstrengender Tag](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT-S5EKz-djV3_JiN2gtRPntAxApxobUjxBQBCafJaikw&s)
