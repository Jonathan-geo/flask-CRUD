# FlaskCRUD
Aplicação CRUD utilizando o Python (Flask) como linguagem principal. Utiliza-se também, neste projeto, o banco de dados MySQL e a linguagem de script JS (Bootstrap). 

## Introdução
Esta é uma simples aplicação CRUD feita com base em Flask, um framework Python. Antes de rodar em seu sistema é necessário pontuar algums observaçes:
>1. Este app foi feito com base em um Linux Ubunto, logo a forma de instalção e utilização de alguns frameworks poderão ser diferentes em um SO diferente. 
>2. Foi utilizado o Python 3.7
>3. Foi instalado o pacote LAMP (MySQL). Recomendo a instalação do pacote XAAMP, para usuários de windows. 
>4. O diretório ENV corresponde ao virtualenv instalado em meu computador. (https://virtualenv.pypa.io/en/latest/)

## Inicialização
A seguir estão descritos os pacotes python necessários para rodar este app. Espera-se que você já tenha o python em sua máquina. 

```
pip install PyMySQL
pip install flask
pip install flask_mysqldb
```
OBS: Tive muita dificuldade para instalar a biblioteca flask_mysqldb. O problema foi resolvido digitando os seguintes comandos no terminal:

```
$sudo apt-get install libmysqlclient-dev
$sudo apt install default-libmysqlclient-dev

E logo em seguida usei o:

pip install flask_mysqldb
```
As formatações front-end, ainda incompletas, estão sendo feitas com o framework Bootstrap do JS. 
Fiquem a vontade para fazer o download e elaborar as suas próprias formatações. 

Enjoy it!

Jonathan Cardoso L Domingos. 