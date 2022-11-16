A tool to decrypt the passwords stored in maven settings.xml files
===========================================================================

Maven 2.1.0+  supports [server password encryption](http://maven.apache.org/guides/mini/guide-encryption.html)
This tool lets you decrypt these passwords as long as you have access to both the settings.xml file and the settings-security.xml file.

To use it [download](https://github.com/maddingo/maven-settings-decoder/packages/1718059) the compiled distributable
or build it from source with

    mvn package

This will produce the excutable jar file in `target/maven-settings-decoder.jar`

    usage: settings-decoder
     -f,--settings <arg>            location of settings.xml file.
     -s,--settings-security <arg>   location of settings-security.xml.
