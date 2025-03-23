# Projetos
Bom aqui você poderá ver tudo aquilo que venho aprendendo no atual momento, em forma de projetos, e por falar neles, que tal usar uma calculadora?

## Calculadora
Certo, o projeto que você está preste a ver é uma ferramenta revolucionária (Bom provavelmente para quem se cansou de usar o ábaco) porém simples, nada de interfaces gráficas ou afins... 

### Tecnologias usadas
- **Python e Bash script** 
- **Jupyter Lab**

#### Requisitos
A seguir você pode ver as instruções de como utilizar o programa, e quais são os requisitos necessário para roda-lo em sua máquina.


**I**. tenha um ambiente virtual já criado, isso será necessário para que o programa possa funcionar. Para isso, basta abrir seu **terminal** e seguir a linha de comando a baixo:

**Linux/macOS**
	
	python3 -m venv nome_ambiente
	

	python3 -m pip install -r requerimentos.txt

**Widowns**

	python -m venv nome_ambiente

	python -m pip install -r requerimentos.txt

*****

**II**. Ative sou ambiente virtual e em seguida instale as devidas dependências:

**Linux/macOS**

**Nota!**

Lembre-se de que é necessário estar no diretório em que seu ambiente virtual foi criado para ativa-lo ou passar o caminho onde ele está alocado.

	source nome_ambiente/bin/activate

**Windows**
	
	nome_ambiente/Scripts/Activate.ps1


****
**III**. Bom, se você um usuário **Windows** basta seguir a linha de comando a seguir a baixo:

	ipython Calculadora.ipynb
	
**IV**. Agora se você for um usuário **Linux** ou **macOS** e quiser por sua vez rodar um script bash para instânciar a calculadora ou caso queira modificar o código fonte, basta seguir a instruções a baixo:

_De as permissões necessárias para tornar os arquivo init executáveis_

**Linux/macOS**
	
	sudo chmod +x init_calc.sh init_Labs.sh

agora basta rodar os executáveis de sua preferência:

**Instânciar a calculadora**

	./init_calc.sh

**Instânciar o JupyterLab para modificações**

	./init_Lab.sh