O trabalho final desta disciplina consiste na construção de um modelo preditivo para uma tarefa de classificação através do emprego das técnicas de aprendizagem supervisionada vistas em aula. As técnicas a serem empregadas precisam ser obrigatoriamente aquelas estudadas em aula nesta disciplina, nesta turma, neste semestre. O trabalho deve ser realizado em trios. Para isto, cada trio de alunos(as) deve:

## Primeira Etapa até 21/05
1.  Escolher os integrantes do grupo;
2.  Escolher uma base de dados disponível publicamente que:

-   Contenha tanto atributos quantitativos quanto categóricos;
-   Permita a criação de um modelo preditivo de classificação;
-   Seja exclusiva de cada grupo, o que significa que:

-   Não pode haver mais de um grupo com a mesma base de dados;
-   Não podem ser usadas as bases de dados usadas pelo professor em aula.

4.  Escolher qual será a coluna alvo do modelo;
5.  Definir o objetivo do seu modelo preditivo e apresentar uma justificativa para tal escolha;
6.  **Até o dia 21/05/2020** publicar no [fórum no Moodle](https://moodle.pucrs.br/mod/forum/view.php?id=1471454) **(1,0 ponto)**:

-   Os nomes dos integrantes do grupo;
-   A base de dados escolhida;
-   A coluna alvo escolhida;
-   O objetivo do modelo e a justificativa para sua escolha;
-   Atenção: **A exclusividade sobre a base de dados será do primeiro grupo que publicar sua escolha no fórum**. Assim, antes de publicar sua escolha, verifique as mensagens no fórum para se certificar de que nenhum outro grupo tenha escolhido a mesma base de dados;

## Segunda Etapa 29/06

8.  Criar o projeto no formato de um notebook do Jupyter que deverá conter tanto o código em Python quanto a documentação do trabalho;
9.  O notebook deve conter obrigatoriamente etapas de:

- Análise exploratória dos dados **(1,0 ponto)**;
- Pré-processamento dos dados **(2,0 pontos)**;
- Treinamento de vários modelos preditivos, empregando todas as técnicas vistas durante o semestre **(2,0 pontos)**;
- Avaliação do desempenho de cada modelo preditivo **(3,0 pontos)** e;
- Escolha do modelo final justificada e embasada no processo de avaliação de desempenho **(1,0 ponto)**.

11.  **Até o dia 29/06/2020** entregar em um .**ZIP** na sala de entrega do Moodle o notebook feito com o Jupyter e a base de dados utilizada.

-   Não serão aceitas entregas após este prazo;
-   Não serão aceitas entregas de arquivos corrompidos;
-   Não serão aceitas entregas de trabalhos em nenhum outro formato que não seja um notebook feito com o Jupyter utilizando Python;
-   O trabalho deve obrigatoriamente ser desenvolvido neste semestre, não serão aceitos trabalhos já entregues em outros semestres ou desenvolvidos em qualquer outra disciplina.

Como resultado final, espera-se a entrega de um relatório no formato de notebook do Jupyter descrevendo:
1. Todas as etapas executadas;
2. As técnicas empregadas;
3. Os hiper-parâmetros escolhidos;
4. As razões para a escolha de cada técnica ou hiper-parâmetro; 
5. Os resultados obtidos; 
6. Os resultados da execução de cada técnica; 

**Especial atenção deve ser dedicada a:** 
1. às técnicas de preparação de dados
2. à escolha dos modelos preliminares de aprendizagem supervisionada; 
3. à comparação entre os resultados dos modelos; 
4. à correta aplicação das técnicas de avaliação da aprendizagem. 

# Sobre o dataset

- **Primeira coluna (Qualitativo):** Status da conta corrente existente.

| Atributos 	| Descrição 		|
| ------------- |-----------------------|
| A11      	| < 0 DM 		|
| A12      	| 0 <= ... < 200 DM     | 
| A13 		| ... >= 200 DM 	|
| A14 		| Sem conta corrente 	|


- **Segunda coluna (Numérico):** Duração no mês.

- **Quarta coluna (Qualitativo):** Histórico de crédito.

| Atributos 	| Descrição 		|
| ------------- |-----------------------|
| A30      	| nenhum crédito recebido ou todos os créditos já devolvidos devidamente. 		|
| A31      	|  todos os créditos deste banco foram devolvidos devidamente     | 
| A32 		| créditos existentes devidamente pagos até agora 	|
| A33 		| atraso no pagamento no passado 	|
| A34 		| conta crítica / outros créditos existentes (não neste banco) 	|

- **Quarta coluna (Qualitativo):** Propósito do crédito.

| Atributos 	| Descrição 		|
| ------------- |-----------------------|
| A40      	| Carro novo 		|
| A41      	| Carro usado   	| 
| A42 		| Móveis/Equipamentos 	|
| A43 		| Rádio/Televisão 	|
| A44 		| Eletrodomésticos 	|
| A45 		| Reparos 		|
| A46 		| Educação 		|
| A47 		| Férias 		|
| A48 		| Retraining[?] 	|
| A49 		| Business 		|
| A410 		| Others 		|

- **Quinta coluna (Numérico):** Quantia de crédito.

- **Sexta coluna (Qualitativo):** Conta de poupança / títulos.

| Atributos 	| Descrição 			|
| ------------- |-------------------------------|
| A61      	| ... < 100 DM 			|
| A62      	| 100 <= ... < 500 DM   	| 
| A63 		| 500 <= ... < 1000 DM 		|
| A64 		| .. >= 1000 DM 		|
| A65 		| desconhecido / sem poupança 	|

- **Sétima coluna (Qualitativo):** Emprego atual desde..

| Atributos 	| Descrição 			|
| ------------- |-------------------------------|
| A71      	| Desempregado 			|
| A72      	| ... < 1 year   		| 
| A73 		| 1 <= ... < 4 years 		|
| A74 		| 4 <= ... < 7 years 		|
| A75 		| .. >= 7 years 		|

- **Oitava coluna (Numérico):** Taxa de parcelamento em porcentagem da renda disponível.

- **Nona coluna (Qualitativo):** Status pessoal e genero

| Atributos 	| Descrição 			        |
| ------------- |---------------------------------------|
| A91      	| Masculino : divorciado/separado       |
| A92      	| Feminino : divorciada/separada/casada | 
| A93 		| Masculino : solteiro  		|
| A94 		| Masculino : casado/viúvo 		|
| A95 		| Feminino : solteira                   |

- **Décima coluna (Qualitativo):** Outros devedores

| Atributos 	| Descrição     |
| ------------- |---------------|
| A101      	| Nenhum        |
| A102      	| Co-requerente | 
| A103 		| Guarantor     |

- **Décima primeira coluna (Numérico):** Residência atual desde...

- **Décima segunda coluna (Qualitativo):** Propriedade

| Atributos 	| Descrição      	    |
| ------------- |---------------------------|
| A121      	| Imobiliária    	    |
| A122      	| Building society savings agreement[?] / seguro de vida | 
| A123 		| Carro ou outro 	    |
| A124 		| Desconhecido / Não possui |

- **Décima terceira coluna (Numérico):** Idade em anos

- **Décima quarta coluna (Qualitativo):** Outros planos de parcelamento

| Atributos 	| Descrição |
| ------------- |-----------|
| A141      	| Banco     |
| A142      	| Loja      | 
| A143 		| Nenhum    |

- **Décima quinta coluna (Qualitativo):** Habitação

| Atributos 	| Descrição    |
| ------------- |--------------|
| A151      	| Aluguel      |
| A152      	| Casa própria | 
| A153 		| De graça     |

- **Décima sexta coluna (Numérico):** Número de créditos existentes neste banco.

- **Décima sétima coluna (Qualitativo):** Trabalho

| Atributos 	| Descrição  					  |
| ------------- |-------------------------------------------------|
| A171      	| Desempregado / sem qualificação - não residente |
| A172      	| Sem qualificação - residente 			  | 
| A173 		| Funcionário qualificado / Funcionário           |
| A174      	| Gerente / Autônomo / Funcionário / Funcionário altamente qualificado      |

- **Décima oitava coluna (Numérico):** Number of people being liable to provide maintenance for[?]

- **Décima nona coluna (Qualitativo):** Telefone

| Atributos 	| Descrição  	       		         |
| ------------- |----------------------------------------|
| A191      	| Nenhum 				 |
| A192      	| sim, registrado com o nome de clientes | 


- **Vigésima coluna (Qualitativo):** Trabalhador estrangeiro

| Atributos 	| Descrição |
| ------------- |-----------|
| A201      	| Yes       |
| A202      	| No        | 
