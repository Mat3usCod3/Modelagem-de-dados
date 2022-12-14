<div style="display: inline_block" align="center">
  <h1>Modelagem de dados utilizando Mysql Workbench</h1>
  <img align="center" alt="Mateus-ícon" height="100" width="100" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original-wordmark.svg">
</div>

## Fábrica de picolés
Uma empresa fabricante de picolés deseja armazenar informações acerca de seus negócios. Os
picolés fabricados são divididos em normal (com água) e ao leite. As informações comuns
armazenadas dos picolés são: sabor, ingredientes, preço e tipo da embalagem. Especificamente, picolés normais possuem um conjunto de aditivos nutritivos (vitaminas ou sais minerais) cada
um com nome e fórmula química; e picolés ao leite contêm um conjunto de conservantes, cada
um com nome e descrição. Os dois tipos de picolés são vendidos em lotes exclusivos (ou normais, ou ao leite) para os revendedores e cada venda gera uma nota fiscal que pode conter um ou vários lotes. As notas fiscais possuem data, valor, número de série e descrição. Todo revendedor
possui uma pessoa de contato para eventuais resoluções de problemas, além disso, armazena-se
do revendedor o CNPJ e a razão social. Deseja-se obter relatórios sobre as vendas mensais dos
picolés de cada tipo e quais revendedores compraram mais picolés nos últimos meses.

## Faculdade 
Uma faculdade oferece vários cursos cujos currículos são compostos por diversas disciplinas. Cada disciplina pode ser oferecida para vários
cursos distintos; uma disciplina pode ter outras disciplinas como pré-requisitos em série ou em paralelo. Na faculdade há diferentes tipos de
pessoas identificadas por um único número funcional: os alunos, professores e funcionários – cada qual com seus atributos gerais e específicos
(defina alguns). Os alunos, só podem estar inscritos em um único curso em um dado momento (status ativo), e só
poderão se inscrever em outro curso caso todas as suas inscrições estejam finalizadas (status concluído) – são armazenadas informações de ano
de início e de término. Em cada semestre, os alunos matriculam-se em turmas correspondentes às disciplinas do seu curso. Professores podem
ministrar para várias turmas, e toda turma tem obrigatoriamente um professor. Os funcionários auxiliam os professores, sem exclusividade.
Tanto os professores quanto os funcionários podem decidir se matricular em um curso da universidade, com as devidas restrições. A base de
dados deve permitir a geração de listas de notas para cada turma, onde deve constar com que professor um aluno fez qual disciplina.

## Clínica
Em uma clínica trabalham médicos de diversas especialidades. Cada médico é identificado pelo seu CRM, possui um nome e recebe 
um salário na clínica. Um médico pode ter formação em diversas especialidades (ortopedia, traumatologia, etc) mas só exerce uma 
delas na clínica. Para todo paciente internado na clínica são cadastrados alguns dados pessoais: nome, RG, CPF, endereço, telefone(s) 
para contato e data de nascimento. Um paciente tem sempre um determinado médico como responsável (com um horário de visita 
diário predeterminado), porém vários outros médicos podem participar do seu tratamento. Pacientes estão sempre internados em 
quartos individuais, que são identificados por um número e ficam em um andar da clínica.

## Garagem
Uma	 garagem	 para	 estacionamento	 de	 veículos	 pretende	 implementar	 um	 sistema	 que	 lhe	 permita	 administrar	 a	 informação	 relativa	 ao	
estacionamento	dos	seus	clientes.	A	garagem	é	composta	por	um	conjunto	de	vagas	cada	uma	podendo	estar	ocupada	ou	não.	Há	dois	tipos	de	
vagas:	avulsa	(se	houver	disponibilidade)	ou	mensal.	Cada	vaga	tem	um	preço	–	a	avulso	tem	um	custo	por	hora	e	o	mensal	um	custo	fixo.	Os	
preços	 serão	 diferenciados	 de	acordo	com	 o	tipo	 de	veículo:	automóvel	 ou	moto.	Cada	vaga	mensal	 possui	 um	cliente	associado. Para	cada	
cliente	é	registrado	seu	nome	e	CPF,	sendo	que	um	dado	cliente	pode	contratar	várias	vagas	mensais.	A	cada	vez	que	um	cliente	estacionar	um	
veículo	(fizer	uma	estacionagem),	deverá	se	armazenar	o	CPF	do	cliente,	código	da	vaga,	a	data/hora	de	entrada	e	de	saída,	a	placa	do	veículo	
estacionado	e	o	custo	gerado	(que	pode	ser	0	para	clientes	mensais).



