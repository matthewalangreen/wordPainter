# wordPainter
Wolfram Language Custom API + Processing

<img src="https://raw.githubusercontent.com/matthewalangreen/wordPainter/master/07192017.gif"/> 

## Contents of WL File
```
CloudDeploy[
 APIFunction[{"x" -> "String"}, 
  ResponseForm[TextWords[Import[#x]], "XML"] &], 
 Permissions -> "Public"]
 ```
