Originaltext von Luis Quesada übersetzt in die deutsche Sprache.

JarSplicePlus (Deutsche Version)
================================

JarSplicePlus (Jar File Merger - Eine Erweiterung zu JarSplice). 
Copyright (c) 2013, Luis Quesada - https://github.com/lquesada

JarSplice (The Fat Jar Creator) wurde ursprünglich von The Ninja Cave ( http://ninjacave.com/ ) veröffentlicht. JarSplice ermöglicht das Zusammenführen von JAR-Dateien und nativen Bibliotheken in einer JAR- oder ausführbaren Datei von GNU / Linux, Windows oder Mac OS.

Dieses Tool verfügte jedoch über keine Funktionen wie eine Befehlszeilenschnittstelle für die Integration in Build-Ketten. Die JarSplice-Website gibt an, dass "JarSplice für jede Art und Anwendung frei ist" und dass "der Quellcode für die eigentliche JarSplice-Anwendung unter einer BSD-Lizenz steht". Leider, und trotz der Anfragen von JarSplice-Benutzern, ist es fast zwei Jahre her. Weder eine Version mit Unterstützung der Befehlszeilenschnittstelle, noch der Quellcode wurden veröffentlicht.


Da ich mich immer noch mit den Interna von JarSplice vertraut machen wollte, habe ich beschlossen, es zu dekompilieren und die Unterstützung für die Befehlszeilenschnittstelle direkt darin zu implementieren. Daher enthält das Quellpaket org.ninjacave.jarsplice den Quellcode, der beim Dekompilieren von JarSplice mit Java Decompiler erhalten und geringfügig geändert wurde.

Übersetzt ins deutsche von Adam Jaquet
