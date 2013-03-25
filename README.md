# What's this?

This software generates an Microsoft HTML Help(CHM) from generic javadoc style API documents.
It's a easy way to search something from javadoc with pre-compiled full text index.

Javadoc.chm can auto identify the new doc style for java 7.0+.

# Requirements

* [Java](http://www.oracle.com/technetwork/java/javase/downloads/index.html)
* [HTML Help Workshop](http://msdn.microsoft.com/en-us/library/ms669985.aspx)

# How to

Generates HTML Help project files

```
java -Xms256m -Xmx512m -jar javadoc.chm.jar <javadoc-api-dir> <file-encoding>
```

Compile the HTML Help

```
build.bat
```

To change the default language option of hhp file, modify htmlhelp.hhp.

```
"Language=0x409 English (U.S.)"
```