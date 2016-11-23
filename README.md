JaCoCo Java Code Coverage Library
=================================

! FORK !

Anpassungen 
 - die Annotation lombok.Generated wird ausgewertet -> bei Klassen mit dieser Annotation wird die Auswertung der Abdeckung für die Methoden equals()hashCode() toString() unterbunden.
 
Repositories für Fork : 

```xml
<repository>
	<id>db0x</id>
	<url>http://mvn.db0x.de</url>
</repository>

<pluginRepository>
	<id>db0x</id>
	<url>http://mvn.db0x.de</url>
</pluginRepository>
```

Aktuelle Version 0.7.8db0x0001

How2Use:
Da nicht die Erstellung der .exec-files verändert ist, sondern das Auswerten dieser Files muss man die jaCoCo Version überall da tauschen, wo die Auswertung passiert. Das sind meist folgende Orte 
 - eclEmma-plugin für Eclipse
 - Jenkins
 - SonarQube
