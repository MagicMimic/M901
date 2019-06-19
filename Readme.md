# Dokumentation M901 

## 703.1
### Vagrant

Vagrant automatisiert das erstellen und löschen von virtuelle Machinen anhand einer vagrant Datei.
Vagrant gehört zu einer Sprache die "Infrastructure as a Code" übermittelt, das soll heissen, dass man einen "Code" schreiben kann, in unserem Fall die Vagrantdatei.
Man kann auch in einem Vagrantfile mehere Virtuelle Machinen erstellen, die mit einander kommunizieren

Eine Vagrant Datei könnte dabei ungefähr so aussehen:

![image](Code.PNG)

## Vagrant Befehle
| Vagrant Befehle    | Wirkung           |
| ------------------ | -----------------:|
| vagrant up         | Führt das Vagrant File aus |
| vagrant destroy -f | Löscht die erzeugten Daten des Vagrant Files |
| vagrant reload     | Reloaded das Vagrant File |

Wenn man dann mit Vagrant eine Vm erstellt hat, kann man mit einem Virtualizer (VirtualBox Oracle) in diese Virtuelle Machine   

![image](Vagrant.PNG)

Das obrige Bild beschreibt die Struktur von Vagrant.

