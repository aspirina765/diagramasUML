## Diagramas de UML 


### Comandos de linha para conversão

java -Djava.awt.headless=true -jar plantuml.jar zuri_passo_a_passo_pronto.puml -tsvg

java -Djava.awt.headless=true -jar plantuml.jar *.puml -tsvg -o "./uml_svg/"

java -Djava.awt.headless=true -jar plantuml.jar *.puml -o "./uml_png/"

java -Djava.awt.headless=true -jar plantuml.jar *.puml -tlatex -o "./uml_latex/"

java -Djava.awt.headless=true -jar plantuml.jar *.puml -thtml -o "./uml_html/"