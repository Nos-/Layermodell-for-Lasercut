Erstellung von Schichtmodellen für den Lasercut
===============================================

Übereinandergelegte horizontale Schnittansichten eines 3D-Modells, die z.B. aus Pappe ausgelasert werden, sollen hier als Schichtmodell verwendet werden.


Voraussetzungen
---------------

* Blender 2.79 (im Test verwendet)
* Freestyle-SVG-Exporter Addon


Vorgehen
--------

1. Objekt erstellen
2. Plane (als Schnittebene) einfügen
3. mittels zweier runder Stangen (z.B. langezogene Zylinder), die alle Schichten durchstoßen, kann den Schichten später halt gegeben werden
4. per Boolean-Modifier (Intersect) Schnittkanten sichtbar machen
5. Animation der Schnittebene
6. Einheitsmaße (auf Orthografische Ansicht achten!)
7. Freestyle samt Linieneinstellungen und passenden Farben einstellen (siehe Farbmapping für den Lasercut)
8. Export per Freestyle SVG-Exporter Addon


Erstellung eines Spantenmodells
===============================

Sehr ähnlich zu Schichtenmodllen sind sogenannte Spantenmodelle. Bei ihnen werden einfach regelmäßig Schichten weggelassen, sodas eine Form entsteht, die fürs Tiefziehen oder den Leichtbau verwendet werden kann. Man kann es sich wie eine Art Skelett vorstellen, das z.B. mit einer Kunststoffhaut überzogen der Form des ürsprünglichen Körper sehr nahe kommt. Es wird z.B. für den Bau von Modellflugzeugen verwendet. Hierbei kommt es auch daruf an, das die einzelnen Schichten einigermaßen stabil sind und fest auf den Verbindungsstäben befestigt sind.
