# 🌍 Correção Atmosférica com Py6S

Este repositório contém um **tutorial prático** de como realizar **correção atmosférica de imagens de sensoriamento remoto** utilizando a biblioteca [Py6S](https://py6s.readthedocs.io/en/latest/), uma interface Python para o modelo radiativo 6S.

📌 Este material foi elaborado com base na aula ministrada pelos instrutores **Rejane Paulino**, **Daniel Maciel** e **Natália Rudorff**, durante a disciplina **Princípios Físicos do Sensoriamento Remoto**, no curso de pós-graduação do **INPE** (Instituto Nacional de Pesquisas Espaciais).



## 📘 Conteúdo

O notebook `Pratica2_principios_fisicos.ipynb` apresenta:

- ✨ Conceitos fundamentais de correção atmosférica.
- 🛰️ Introdução ao modelo 6S.
- 🧪 Utilização da biblioteca Py6S para simulação atmosférica.
- 📉 Conversão de reflectância no topo da atmosfera (TOA) para reflectância de superfície.
- 💻 Exemplos com código Python e aplicação com parâmetros reais.


## 🧰 Requisitos

Para executar o notebook, é necessário ter o Python 3 instalado, além das seguintes bibliotecas:

```bash
!pip install py6s -q
!apt install gfortran libgfortran5 -q
!wget https://anaconda.org/conda-forge/sixs/1.1.3/download/linux-64/sixs-1.1.3-h2cc385e_2.tar.bz2 -q
!tar -xvf sixs-1.1.3-h2cc385e_2.tar.bz2
!rm sixs-1.1.3-h2cc385e_2.tar.bz2
!chmod +x bin/sixs
!ln bin/sixs /usr/local/bin/sixs
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
Abra e execute o notebook `Pratica2_principios_fisicos.ipynb` em um ambiente Jupyter Notebook local ou utilize o codigo no Google Colab asseguir:
https://colab.research.google.com/drive/1snzoHdVbRaAaYu51-cuZkuW5wXjJHRoB?usp=sharing


## 📎 Referências
Vermote, E., Tanré, D., Deuzé, J. L., Herman, M., & Morcette, J. J. (1997). Second Simulation of the Satellite Signal in the Solar Spectrum (6S).



## 👨‍💻 Autor
Repositório desenvolvido por Henrique Leão \
Doutorando em Sensoriamento Remoto - INPE \
GitHub: @Liaons

## 📄 Licença
