# MissaoPraticaN2_Mundo3
 Missao Pratica em SQL Server







Universidade: [UNIVERSIDADE ESTÁCIO DE SÁ]

Campus: [Itaguaí/RJ]

Curso: [Desenvolvimento Full Stack]

Disciplina: [Nível 2: Vamos Manter as Informações?]

Semestre Letivo: [Mundo 3]

Integrantes da Prática: [Wallace Felipe Tavares Moreira]

Informações Gerais do Projeto:

Título da Prática: [Vamos manter as informações! Modelagem e implementação de um banco de dados simples, utilizando como base o SQL Server.]

Objetivo da Prática: [O objetivo da prática é ensinar a identificação de requisitos de um sistema, modelagem de banco de dados, criação de estruturas usando SQL (DDL), consultas e manipulação de dados (DML) e implementação no SQL Server.]

Documentação do Projeto:

O projeto foi armazenado em um repositório no GIT. 

O endereço do repositório é [https://github.com/Wfelipetm/MissaoPraticaN2_Mundo3].

Detalhamento da Prática:

Nesta seção, apresentamos todos os elementos solicitados no roteiro da aula:

Códigos Solicitados:

[1º Procedimento | Criando o Banco de Dados]

[2º Procedimento | Alimentando a Base]

Resultados da Execução dos Códigos:

Resultados obtidos após a execução dos códigos foram os seguintes:

[1º Procedimento]

![image](https://github.com/Wfelipetm/MissaoPraticaN2_Mundo3/assets/108297008/f3654277-bc65-41b8-91ec-3bf041c53a39)

a) Como são implementadas as diferentes cardinalidades, basicamente 1X1, 1XN ou NxN, em um banco de dados relacional?

1- Cardinalidade 1:1 (Um para Um): Use uma chave estrangeira em uma tabela para se relacionar com a chave primária de outra tabela.

2- Cardinalidade 1:N (Um para Muitos): Adicione uma chave estrangeira na tabela "muitos" para referenciar a chave primária da tabela "um".

3- Cardinalidade N:N (Muitos para Muitos): Use uma tabela de junção para conectar duas tabelas principais, incluindo suas chaves primárias.



b) Que tipo de relacionamento deve ser utilizado para representar o uso de herança em bancos de dados relacionais?
  
Para representar herança em bancos de dados relacionais, é recomendado o uso de um relacionamento do tipo "Tabelas Separadas" (ou "Tabelas Filhas"), onde cada subclasse tem sua própria tabela, contendo atributos específicos, e compartilha uma chave comum com a tabela da superclasse.


c) Como o SQL Server Management Studio permite a melhoria da produtividade nas tarefas relacionadas ao gerenciamento do banco de dados?

O SQL Server Management Studio melhora a produtividade no gerenciamento do banco de dados oferecendo uma interface intuitiva para executar tarefas, como consultas SQL, administração de servidores, criação de esquemas e visualização de dados, facilitando o desenvolvimento e a manutenção do banco de dados.




[2º Procedimento]


Análise e Conclusão [2º Procedimento]:

a) Diferenças no Uso de Sequence e Identity:
Sequence: É um objeto genérico de banco de dados que gera valores exclusivos em ordem sequencial. Pode ser usado em várias tabelas e em diferentes sistemas de gerenciamento de banco de dados (DBMS).

Identity: É um recurso específico de alguns DBMS, como o SQL Server e o MySQL, usado para criar colunas que geram automaticamente valores exclusivos e crescentes. Geralmente é usado como chave primária em uma tabela.


b) Importância das Chaves Estrangeiras para a Consistência do Banco:
As chaves estrangeiras são vitais para garantir a consistência dos dados em um banco de dados. Elas estabelecem relacionamentos entre tabelas, evitam dados "órfãos", facilitam consultas complexas e ajudam na manutenção do banco de dados. Em suma, mantêm os dados organizados e precisos.



c) Operadores do SQL Pertencentes à Álgebra Relacional e Definidos no Cálculo Relacional:
Na linguagem SQL, a maioria dos operadores pertence à álgebra relacional, enquanto o cálculo relacional é mais usado para especificar consultas. Operadores comuns da álgebra relacional em SQL incluem SELECT, JOIN, UNION, entre outros, enquanto o cálculo relacional é usado de maneira mais teórica para descrever consultas. Em resumo, a álgebra relacional é a base das operações práticas em SQL.





d) Agrupamento em Consultas e Requisito Obrigatório:
Em consultas SQL, o agrupamento é realizado com a cláusula "GROUP BY". O requisito obrigatório é listar todas as colunas não agregadas na cláusula "GROUP BY". Isso permite agrupar registros com base em colunas específicas e aplicar funções de agregação, como AVG, COUNT, MAX, MIN ou SUM, aos grupos resultantes. Isso é útil para resumir dados em consultas.





