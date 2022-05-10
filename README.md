## Diagramas de UML 

Estes arquivos provém exemplos e formas para se fazer diagramas UML usando o software (free e open source) <a href="https://plantuml.com/" alt="a0">plantUML</a>. 

Existe um jupyter notebook (*.ipynb) de exemplo que utiliza o plantUML (localmente ou usando API) em jupyter. 

Para uso local, é necessário usar o arquivo plantuml.jar (presente na referência <a href="https://plantuml.com/download" alt="c">3</a>) junto dos comandos de linha, documentados na referência <a href="https://plantuml.com/command-line" alt="a" >1</a>.


Um guia completo de como produzir diferentestipos de diagramas é fornecida pelo próprio plantUML, via referência <a href="https://plantuml.com/guide" alt="b">2</a>. 

### Comandos de linha para conversão

Nesta seção vão exemplos de como se converter, localmente (usando plantuml.jar), arquivos .puml ou .txt (ou seja, diagramas produzidos em plantUML) em formatos diversos. Uma visão mais completa de formatos e comandos possíveis está na referência <a href="https://plantuml.com/command-line" alt="a" >1</a>. 

Seguem um rol de exemplos de comandos para cada tipo de formato de arquivo: 
#### a) svg : 
* java -Djava.awt.headless=true -jar plantuml.jar file.puml -tsvg

* java -Djava.awt.headless=true -jar plantuml.jar *.puml -tsvg -o "./uml_svg/"


#### b) png : 
* java -Djava.awt.headless=true -jar plantuml.jar *.puml -o "./uml_png/"


#### c) latex : 
* java -Djava.awt.headless=true -jar plantuml.jar *.puml -tlatex -o "./uml_latex/"


#### d) html : 
* java -Djava.awt.headless=true -jar plantuml.jar *.puml -thtml -o "./uml_html/"

## Referências 

1. <a href="https://plantuml.com/command-line" alt="a" >Comandos de linha para salvar diagramas localmente usando java e plantuml.jar</a>

2. <a href="https://plantuml.com/guide" alt="b">Guia do plantUML</a>

3. <a href="https://plantuml.com/download" alt="c">Página de downloads do plantUML</a>

