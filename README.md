JaCoCo Java Code Coverage Library
=================================

[![Build Status](https://travis-ci.org/jacoco/jacoco.svg?branch=master)](https://travis-ci.org/jacoco/jacoco)

JaCoCo is a free Java code coverage library distributed under the Eclipse Public
License. Check the [project homepage](http://www.jacoco.org/jacoco)
for downloads, documentation and feedback.

Please use our [mailing list](https://groups.google.com/forum/?fromgroups=#!forum/jacoco)
for questions regarding JaCoCo which are not already covered by the
[extensive documentation](http://www.jacoco.org/jacoco/trunk/doc/).

Note: We do not answer general questions in the project's issue tracker. Please use our [mailing list](https://groups.google.com/forum/?fromgroups=#!forum/jacoco) for this.
-------------------------------------------------------------------------

Anpassungen 
 - die Anotation lombok.Generated wird ausgewertet -> bei Klassen mit dieser Anotation wird _keine_ coverage für die Methoden equals() und hashCode() erstellt.

Repositories für Fork : 

<repository>
	<id>db0x</id>
	<url>http://mvn.db0x.de</url>
</repository>

<pluginRepository>
	<id>db0x</id>
	<url>http://mvn.db0x.de</url>
</pluginRepository>

-------------------------------------------------------------------------
