# Search Methods in Game of 8

## Objetivo

Esse trabalho foi desenvolvido por Alice Ribeiro e Aline Guimarães para a disciplina de Inteligência Artificial, com dois de métodos de buscas aplicados ao jogo dos 8: heurística gulosa e busca em profundidade.

## Arquivos

notebookDFS.ipynb: notebook contendo código em python de uma busca em profundidade e documentação de seus métodos.

notebookGulosa.ipynb: notebook contendo código em python de uma heurística gulosa com três critérios diferentes e documentação de seus métodos.

main.ipynb: notebook contendo importação dos dois outros notebooks e com código para execução das buscas com entradas estáticas (estabelecidas no código) e possibilidade de input de matriz. Seus métodos também estão documentados. 

## Requistos

Para rodar o código você precisará dos seguintes requisitos:  

[![Python Version](https://img.shields.io/badge/python-3.8.2-green)](https://www.python.org/downloads/release/python-382/)

Além disso, rodar essas linhas de código na pasta onde estão os arquivos (quando for a primeira vez) para criação do virtual environment e instalação dos requisitos.
```
$ python3 -m venv env
$ source env/bin/activate
$ pip install -r requirements.txt
  ```
  
## Execução

Para ativar o virtual environment, utilizar a seguinte linha de comando:
```
$ source env/bin/activate
```  

Com o virtual environment ativado, para rodar o notebook, utilizar a seguinte linha de comando:
```
$ jupyter notebook
```

Para sair do jupyter notebook, utilizar Ctrl + c, e para desativar o virtual environment:
```
$ deactivate
```

