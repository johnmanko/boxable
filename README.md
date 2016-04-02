boxable
=======

Create tables in pdf documents using [PDFBox](http://pdfbox.apache.org)

Here are a few examples of the type of tables boxable can created :

* [Table with text and images](https://s3.amazonaws.com/misc.quodlibet.be/Boxable/BoxableSample1.pdf)
![alt text](https://s3.amazonaws.com/misc.quodlibet.be/Boxable/sample1_preview.png)
* [Vertical and Horizontal text](https://s3.amazonaws.com/misc.quodlibet.be/Boxable/BoxableSample3.pdf)
![alt text](https://s3.amazonaws.com/misc.quodlibet.be/Boxable/sample3_preview.png)


Example code can be found [here](https://github.com/dhorions/boxable/blob/master/src/test/java/be/quodlibet/boxable/TableTest.java)

The project is Java 7 compliant.

Maven : 
The project can be used as a Maven dependency : 
```xml
<dependency>
    <groupId>com.github.dhorions</groupId>
    <artifactId>boxable</artifactId>
    <version>1.3</version>
</dependency>
```


The project can also be used as a Maven dependency by using jitpack.io.
* add the repository : 
```xml
<repository>
  <id>jitpack.io</id>
  <url>https://jitpack.io</url>
</repository>
```
* add the dependency
```xml
<dependencies>
  <dependency>
    <groupId>com.github.dhorions</groupId>
    <artifactId>boxable</artifactId>
    <version>1.3</version>
  </dependency>
</dependencies>
```

Special Thanks to [dgautier](https://github.com/dgautier),[ZeerDonker](https://github.com/ZeerDonker),[Frulenzo](https://github.com/Frulenzo),[dobluth](https://github.com/dobluth) and [schmitzhermes](https://github.com/schmitzhermes) for their valuable contributions.

=======

Copyright [2016] [Quodlibet.be]

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.