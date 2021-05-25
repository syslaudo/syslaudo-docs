# Sistema de gerenciamento de exames e laudos de cardiologia  (SYSLAUDO)

Visando atender melhor seus pacientes e informatizar seu sistema de solicitação de exames e entrega de resultados da área de cardiologia, o hospital da UNIT contratou a ABLFN³ para desenvolver o software aqui apresentado.

# Alinhamento Estratégico 

- **Missão**

Oferecer a melhor experiência em soluções de saúde, com qualidade, segurança e comodidade.

- **Nosso cliente**

Pessoas que necessitam de soluções de saúde.

- **O que o cliente valoriza?**

O cliente valoriza quando é bem atendido e suas demandas são reconhecidas.

- **Quais são os nossos resultados?**

Através dos nossos processos de segurança, comodidade e qualidade esperamos um feedback positivo do cliente, e também dos nossos funcionários em se sentir confortável para trabalhar. Com isso, esperamos construir uma boa reputação no mercado e crescer eventualmente. 

- **Qual é o nosso plano?**

Conseguir atender a todos os clientes que necessitam de soluções de saúde, tratando o cliente com comodidade e saúde para retornar.  

- **Objetivo do processo**

Realizar exames, cadastro de laudos, entre outros. 
# Funcionalidades básicas

- Emissão de pedidos de exame feita pelos médicos;
- Registro de realização de exame ou não;
- Emissão de laudos resultantes dos exames realizados;
- Revisão de laudos realizadas pelos médicos professores;
- Recomendações de exames;
- Cadastro do paciente;
- Consulta do paciente: data do exame, resultado de exame.

# Tipos de médicos

- Médicos Residentes (modalidade de ensino a pós graduação destinado a médicos, ou seja, é um aluno que já é formado porém está fazendo uma especialidade, ele precisa de uma orientação profissional);
- Médicos professores (orientadores dos residentes);
- Médicos.

# Dados dos médicos que são necessários para o cadastro

- Nome
- CRM 

- **Classificação**
- **Titulação do médico professor:** Mestre, doutor, PHD
- **Ano de residência do medico residente:** 1º ano de residência até 4º de residência

# Dados dos pacientes que são necessários para o cadastro 

- Nome
- E-mail
- Sexo
- Data de Nascimento
- Cor (é importante pois algumas doenças são predominantes em determinadas cores)
- Idade(é calculada na data de nascimento inserida no cadastro de paciente)

# Dados necessários para o pedido de exame (Realizado pelos médicos residentes)

- Nome do paciente
- Sexo
- Idade
- Cor
- Data prevista de realização;
- Nome do exame
- Recomendação
- Hipótese do diagnóstico 

# Dados necessários para o cadastro do exame

- Anexação de pdf
- Data da realização
- Hora da realização
- Laudo médico
- Tipo exame 
- Imagem exame 
- Situação do laudo

# Tipos de exames que podem ser solicitados

- Ecocardiograma
- Eletrocardiograma
- Mapa
- Holter

# Informações importantes

- Após o registro do exame, o médico irá interpretar a imagem, se houver.
- Qualquer um dos médicos pode emitir um pedido de exame, desde que informe o registro do paciente.
- Durante o cadastro, O médico vai poder informar uma data prevista para realização do exame, irá informar também a hipótese diagnóstica que deve ser com base na CID (Classificação Internacional de Doenças), por fim, ele solicita a emissão do pedido, o sistema salva e permite imprimir o pedido de exame via internet (o paciente deverá ter acesso ao exame dele pela internet).

# Regra de Negócio 
 
-  Caso o paciente já tenha o pedido em situação de aguardando o exame, o sistema não deve permitir que o outro pedido seja feito. 
	EX:  A Maria já pediu para fazer um Holter e ela ainda não fez o exame, portanto, ela não pode emitir outro pedido de exame. 


# Fatores motivação 

- O processo de realizar exames, entre outros, é responsável por toda a receita da empresa, sendo sua melhoria extremamente necessária. A falta de uma gestão efetiva sobre o processo tem grande impacto no faturamento, crescimento e sobrevivência da empresa. 


# Tecnologias utilizadas no desenvolvimento do software

- **Front-end**
	- ReactJS 

- **Back-end**
	- NodeJS

- **Analytics**
	- Python
	
- **Testes**
	- Selenium
	- Mocha
	- Jmeter

- **CI/CD**
	- GitHub Actions;
	- AWS API Gateway;
	- AWS Amplify;

## Grupo ABFLN³ 👨‍💻👩‍💻

<table>
   <thead>
			<tr>
					<th>Nome</th>
					<th>E-mail</th>
					<th>Função</th>
			</tr>
   </thead>
   <tbody>
			<tr>
					<td>Alisson Felipe Lima Santos</td>
					<td><a href="mailto:alisson.flima@souunit.com.br">alisson.flima@souunit.com.br</a></td>
					<td>Desenvolvedor</td>
			</tr>
			<tr>
					<td>Bruno César Fontes Vieira</td>
					<td><a href="mailto:bruno.cfontes@souunit.com.br">bruno.cfontes@souunit.com.br</a></td>
					<td>Desenvolvedor</td>
			</tr>
			<tr>
					<td>Fernanda Amaral de Souza</td>
					<td><a href="mailto:fernanda.amaral00@souunit.com.br">fernanda.amaral00@souunit.com.br</a></td>
					<td>Desenvolvedora</td>
			</tr>
			<tr>
					<td>Lucas Santos Souza</td>
					<td><a href="mailto:lucas.santos00@souunit.com.br">lucas.santos00@souunit.com.br</a></td>
					<td>Desenvolvedor</td>
			</tr>
			<tr>
					<td>Natália Braga da Fonseca</td>
					<td><a href="mailto:natalia.braga@souunit.com.br">natalia.braga@souunit.com.br</a></td>
					<td>Scrum Master e Desenvolvedora</td>
			</tr>
			<tr>
					<td>Natan Nascimento Oliveira Matos</td>
					<td><a href="mailto:natan.oliveira@souunit.com.br">natan.oliveira@souunit.com.br</a></td>
					<td>Product Owner e Desenvolvedor</td>
			</tr>
			<tr>
					<td>Natalie Pereira Macedo</td>
					<td><a href="mailto:natalie.pereira@souunit.com.br">natalie.pereira@souunit.com.br</a></td>
					<td>Desenvolvedora</td>
			</tr>
   </tbody>
</table>
