# BurpSuite
Help to install 

**Download BurpSuite from : **

https://portswigger.net/burp/releases

**Add this to BurpSuitePro.vmoptions file**

**windowa**:
```
-XX:MaxRAMPercentage=50
--add-opens=java.desktop/javax.swing=ALL-UNNAMED
--add-opens=java.base/java.lang=ALL-UNNAMED
--add-opens=java.base/jdk.internal.org.objectweb.asm=ALL-UNNAMED
--add-opens=java.base/jdk.internal.org.objectweb.asm.tree=ALL-UNNAMED
--add-opens=java.base/jdk.internal.org.objectweb.asm.Opcodes=ALL-UNNAMED
-javaagent:D:\Program Files\BurpSuitePro\Loader.jar
-noverify
-jar D:\Program Files\BurpSuitePro\burpsuite_pro.jar
-include-options settings.vmoptions
-include-options user.vmoptions
```
