![Badge Desenvolvido](http://img.shields.io/static/v1?label=STATUS&message=%20DESENVOLVIDO&color=GREEN&style=for-the-badge)
# :abacus: Gerador de Orçamentos
#### Esse código tem como finalidade interagir com o usuário para que ele digite a descrição de seu projeto, as horas estimadas para conclusão desse projeto, o valor da hora trabalhada e o prazo estimado para conclusão.

Para receber os dados do usuário, utilizamos a função **input()**.
Os **input()** são armazenados em variáveis.
````python
projeto = input(“Digite a descrição do projeto: ”)
horas = input(“Digite o total de horas estimadas: ”)
valor_hora = input(“Digite o valor da hora trabalhada: )
prazo_estimado = input(“Digite o prazo estimado: ”)
````
#### Todos os dados que digitamos no **input()** são tipo **string** (str) texto, mesmo os números.
#### Para calcular o total de horas estimado é necessário converter esse texto para número.
#### Para converter número em texto, podemos utilizar a função **str()**.
#### Para converter textos em números, podemos utilizar as funções:
	**Int()** : para converter em um número inteiro
	**Float()** : para converter em um número com casas decimais

````python
valor_total_estimado = int(horas_estimadas) * int(valor_hora)
````

Para gerar um PDF é necessário instalar a biblioteca fpdf
````python
!pip install fpdf
````
Utilizando o comando fpdf para importar a biblioteca
````python
From fpdf import FPDF
````
Após criar um PDF, o código insere os dados em um template e gera um arquivo no formato PDF
````python
Pdf.image(“template.png”, x=0, y=0)

Pdf.output(“orçamento.pdf”)
````
:movie_camera:

<img src=".\Animação.gif" alt="Código funcionando" width="600px" heidth="400px">

:film_strip:

<img src=".\Animação2.gif" alt="Código 2 funcionando" width="600px" heidth="400px">

## 📁 Como utilizar o código:
O arquivo **script.py** pode ser usado em um terminal
````python
Python script.py
````
## :computer: Técnicas e Tecnologias utilizadas:
- Converter tipos de dados
- Gerar PDF e criar um arquvi PDF
- Inserir dados no PDF
- **Python**
- **Jupyter Nootbook**

### :books: Bibliotecas:
 **fpdf**
 
