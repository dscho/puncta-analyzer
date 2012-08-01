Puncta-Analyzer 
===============

Puncta Analyzer is an ImageJ plugin for detecting and quantifying punctate co-localization in multi-channel images.	

Build Instructions:
-------------------
1. Install JDK

2. Install maven

3. [Fork](https://help.github.com/articles/fork-a-repo) the puncta analyzer repo (or [download project zip](https://github.com/toddstavish/puncta-analyzer/zipball/master))

4. Execute 'mvn compile' in project directory (where the pom.xml is located)

5. Create a 'PunctaAnalyzer' directory in the your ImageJ plugins directory 

6. Copy all of the class files (bytecode) in target/classes to plugins/PunctaAnalyzer


Relevant links:
---------------
Project Home: [Puncta Analyzer](https://github.com/physion/puncta-analyzer)

Operational Instructions: [Documentation](./doc/instructions.md)

Continuous integration: [travis-ci.org] (http://travis-ci.org/#!/physion/puncta-analyzer)

Underlying technology: [ImageJ](dev.imagej.net) 

Legacy version: [Puncta Analyzer v1.1](https://github.com/physion/puncta-analyzer/tree/v1.1)


