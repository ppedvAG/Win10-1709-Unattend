# Win10-1709-Unattend
Im folgenden Repository sind drei Beispiele von automatisierten Installationen von Windows 10 1709 hinterlegt.
Ein Zero Touch
Ein LiteTouch mit Imageauswahl
Ein LiteTouch mit Imageauswahl und automatischen Domainjoin

Die Antwortdateien sind im aktuellen Falle dafür ausgelegt das diese im WDS (Windows Deployment Services) Verzeichnis "WdsClientUnattend" gespeicht sind. Wenn man mit mehreren Images arbeiten will muss lediglich der Windows PE Abschnitt im dortigen Verzeichnis abgelegt werden und die restlichen Einstellungen in einer eigenen Datei dem Image direkt zugeordnet werden.

Die Dateien wurden getestet mit Windows Server 2016 und Windows 10 Education 
