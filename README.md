# osgi-jfreechart

An OSGI repository for the popular JFreeChart library from http://www.jfree.org/

This repository simply provides an OSGI plugin repository for
JFreeChart libraries.  The source code has not been modified in
anyway. The repository is merely a convenient packaging format of both
binaries and related source material including SWT libraries for OSGI
developers.

## Install

The most recent version of the library included in the repository is
for JFreeChart **1.0.19** and can be installed using Eclipse's plugin
manager.

Add the following URL to the list of available software sites in
eclipse.

```
https://raw.githubusercontent.com/wiki/markroyer/osgi-jfreechart/org.jfree.jfreechart.repository/updates
```

## Building

The project can be built most easily using maven from the
`org.jfree.jfreechart.org.parent` directory. Typing

```bash
mvn clean verify
```

will compile the project and create a repository containing all of the
related libraries in

```bash
../../osgi-jfreechart.wiki/
```

## LICENSE

The license is LGPL3.  See the included LICENSE file for details.

## Thanks

The ant build scripts are based on code from:

[http://www.lorenzobettini.it/2015/01/creating-p2-composite-repositories-during-the-build/](http://www.lorenzobettini.it/2015/01/creating-p2-composite-repositories-during-the-build/)



<!--  LocalWords:  osgi jfreechart JFreeChart SWT mvn LGPL
 -->
