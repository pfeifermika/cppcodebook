# cppcodebook

Howto:

IDE des Vertrauens. VScode hat gute extension -> AsciiDoc
Neues .adoc file in entsprechenden Ordner
Um c++ Code zu inkludieren:

.cpp file in gleichen Ordner wie .adoc Datei.
Um nur Teile zu inkludieren, folgende Kommentare in c++ code:
// tag::template[]

// end::template[]

Dann im .adoc:
[source, c++]
----
include::template.cpp[tag=template]
----

