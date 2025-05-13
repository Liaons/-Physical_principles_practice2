# 🌍 Correção Atmosférica com Py6S

Este repositório contém um **tutorial prático** de como realizar **correção atmosférica de imagens de sensoriamento remoto** utilizando a biblioteca [Py6S](https://py6s.readthedocs.io/en/latest/), uma interface Python para o modelo radiativo 6S.

📌 Este material foi elaborado com base na aula ministrada pelos instrutores **Rejane Paulino**, **Daniel Maciel** e **Natália Rudorff**, durante a disciplina **Princípios Físicos do Sensoriamento Remoto**, no curso de pós-graduação do **INPE** (Instituto Nacional de Pesquisas Espaciais).



## 📘 Conteúdo

O notebook `Pratica_de_princípios_2.ipynb` apresenta:

- ✨ Conceitos fundamentais de correção atmosférica.
- 🛰️ Introdução ao modelo 6S.
- 🧪 Utilização da biblioteca Py6S para simulação atmosférica.
- 📉 Conversão de reflectância no topo da atmosfera (TOA) para reflectância de superfície.
- 💻 Exemplos com código Python e aplicação com parâmetros reais.


## 🧰 Requisitos

Para executar o notebook, é necessário ter o Python 3 instalado, além das seguintes bibliotecas:

```bash
from Py6S import *
import numpy as np
import pandas as pd
import glob
from osgeo import gdal
gdal.UseExceptions()
```

⚠️ Importante: O Py6S depende do executável do modelo 6S, que precisa ser instalado separadamente.
Siga as instruções na documentação oficial:
https://py6s.readthedocs.io/en/latest/installation.html#installing-the-6s-executable

## 🚀 Como usar
Clone este repositório:

```bash
git clone https://github.com/Liaons/py6s-correcao-atmosferica.git
cd py6s-correcao-atmosferica
```
Abra e execute o notebook `Pratica_de_princípios_2.ipynb` em um ambiente Jupyter Notebook local ou Google Colab.


## 📎 Referências
Vermote, E., Tanré, D., Deuzé, J. L., Herman, M., & Morcette, J. J. (1997). Second Simulation of the Satellite Signal in the Solar Spectrum (6S).

Documentação oficial do Py6S
Modelo 6S original


## 👨‍💻 Autor
Repositório desenvolvido por Henrique Leão \
Doutorando em Sensoriamento Remoto - INPE \
GitHub: @Liaons

## 📄 Licença
