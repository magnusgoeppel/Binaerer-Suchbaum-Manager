# Binärer Suchbaum-Manager

Dieses Tool ermöglicht die Verarbeitung von binären Suchbäumen, einschließlich der Überprüfung der AVL-Balance, Berechnung von Baumstatistiken und Durchführung von Suchoperationen. Es kann auch verwendet werden, um zu überprüfen, ob ein bestimmter Subbaum innerhalb eines größeren Baums existiert.

## Features

- **AVL-Balance-Prüfung**: Überprüft, ob der Baum die AVL-Balance-Kriterien erfüllt.
- **Baumstatistiken**: Berechnet und gibt minimale, maximale und durchschnittliche Schlüsselwerte aus.
- **Suche**: Unterstützt einfache Suche nach einem Schlüsselwert und Subtree-Suche.

## Voraussetzungen

- Python 3.4 oder höher
- Bibliothek: `sys`
## Verwendung

```bash
AVL-Baum
Gibt die Balance-Faktoren des Baums aus und überprüft, ob er ein AVL-Baum ist:
python treecheck.py tree.txt 

Einfache Suche
Um zu überprüfen, ob ein Knoten im Baum existiert:
python treecheck.py suchbaum.txt simple.txt

Subtree-Suche
Um zu überprüfen, ob ein Subtree im Baum existiert:
python treecheck.py suchbaum.txt subtree.txt
