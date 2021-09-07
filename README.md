# Mapa de Roubo de Carros no Estado de SP

Para a correta interpretação dos dados é importante observar as seguintes informações:
1. Os dados constantes da resposta foram extraídos do sistema de Registro Digital de Ocorrências (R.D.O.) que é a ferramenta de registro dos boletins de ocorrência nas delegacias de polícia. 
1.1. Com relação ao sistema R.D.O. é importante esclarecer que sua implantação foi concretizada de modo gradual nas diversas unidades policiais do Estado, tendo sua abrangência alcançado todos os municípios apenas a partir do ano de 2010. 
1.2. Também deve ser destacado que as tabelas e campos de preenchimento deste sistema são objetos de constante aperfeiçoamento a fim de adaptar-se às alterações nas dinâmicas criminais observadas no Estado ou propiciar melhoria no atendimento do serviço policial.
1.3. A inclusão ou alteração de um campo e respectivos períodos de implementação podem influenciar diretamente nos critérios de pesquisa executados, não havendo na base fornecida o tratamento metodológico necessário para qualificá-las como dados estatísticos oficiais.
2. Para entendimento do conteúdo de cada campo, deve ser analisada a tabela denominada Dicionário de Dados.
3. Cada linha constante na tabela registra os dados de uma pessoa, natureza ou objeto relacionado no boletim. Assim, um boletim que possua a identificação de mais de uma pessoa, natureza ou objeto (a depender da pesquisa solicitada) terá os dados da ocorrência multiplicados pelos indexadores solicitados, ou seja, várias linhas podem se referir ao mesmo boletim. 
4. Para conclusões quanto as quantidades de ocorrências é necessária exclusão das duplicidades por meio dos campos:

* NOME_DELEGACIA
* ANO_BO
* NUM_BO

5. Frise-se que ao cidadão é facultado o registro da ocorrência em qualquer Delegacia de Polícia do Estado, sendo certo que cerca de 60% das ocorrências são registradas fora de sua circunscrição, ou seja, local do fato (ocorrência). Assim, para a análise dos dados obtém-se resultados diferentes sobre delegacia de registro e delegacia de circunscrição.
6. Os campos que podem levar a identificação da pessoa são protegidos de acordo com o art 31 da Lei de Acesso a Informação
6.1 não são fornecidos endereços que contem como tipo de local residências.
7. O número total de boletins de ocorrências registrados sob uma natureza criminal não representa a estatística criminal do Estado ou de determinada área ou região. A estatística em São Paulo é contabilizada de acordo com os procedimentos estabelecidos pela Resolução SSP nº 160/01 de 08 de maio de 2001, que criou o Sistema Estadual de Coleta de Estatísticas Criminais e pode ser consultada através do endereço eletrônico www.ssp.sp.gov.br."

## A PRESENTE TABELA TEM POR FINALIDADE ESCLARECER OS CAMPOS CONTIDOS NA BASE DE DADOS
* Resultado Null indica que o campo se encontrava vazio no banco de dados
	
Campos	Descrição:

* ID_DELEGACIA - Código da delegacia responsável pelo registro da ocorrência
* NOME_DEPARTAMENTO -	Departamento responsável pelo registro
* NOME_SECCIONAL - Delegacia Seccional responsável pelo registro
* NOME_DELEGACIA - Delegacia responsável pelo registro
* CIDADE - Cidade de Registro
* ANO_BO - Ano do BO
* NUM_BO -	Número do BO
* NOME_DEPARTAMENTO_CIRC -	Departamento de Circunscrição
* NOME_SECCIONAL_CIRC -	Seccional de Circunscrição
* NOME_DELEGACIA_CIRC -	Delegacia de Circunscrição
* NOME_MUNICIPIO_CIRC -	Município da Delegacia de Circunscrição
* DESCR_TIPO_BO -	Tipo de Documento
* DATA_OCORRENCIA_BO -	Data da Ocorrência
* HORA_OCORRENCIA_BO -	Hora da Ocorrência
* DESCR_PERIODO -	Período da Ocorrência
* DATA_INICIAL_OCORR_INCERTA -	Data da Ocorrência Inicial Incerta
* DATA_FINAL_OCORR_INCERTA -	Data da Ocorrência Final Incerta
* DATA_COMUNICACAO_BO - 	Data da Comunicação
* HORA_COMUNICACAO_BO -	Hora da Comunicação
* FLAG_STATUS -	Indica se é crime consumado ou tentado
* RUBRICA -	Natureza jurídica da ocorrência
* DESCR_CONDUTA -	Tipo de local ou circunstancia que qualifica a ocorrência
* DESDOBRAMENTO -	Desdobramentos jurídicos envolvidos na ocorrência
* BAIRRO -	Bairro da Ocorrência
* DESCR_TIPOLOCAL -	Descreve grupo de tipos de locais onde se deu o fato
* DESCR_SUBTIPOLOCAL -	Descreve subgrupo de tipos de locais, vinculado ao tipo de local,  onde se deu o fato
* CEP -	Código de Endereçamento Postal
* LOGRADOURO -	Logradouro dos fatos
* NUMERO_LOGRADOURO -	Número do Logradouro dos fatos
* LOGRADOURO_REFERENCI -A	Logradouro de referência dos fatos
* NUMERO_LOGRADOURO_REFERENCIA -	Número do Logradouro de referência dos fatos
* LATITUDE -	Latitude da Ocorrência
* LONGITUDE -	Longitude da Ocorrência
* DESCR_TIPO_PESSOA -	enquadramento da pessoa de acordo com seu envolvimento na ocorrência
* FLAG_VITIMA_FATAL -	indica se a pessoa relacionada é vítima fatal.(S= sim; N=não) 
* DESCR_ESTADO_CIVIL -	Estado Civil
* SEXO_PESSOA -	Sexo
* IDADE_PESSOA -	Idade
* COR_CUTIS -	Cor da Pele
* DESCR_GRAU_INSTRUCAO -	Grau de escolaridade do envolvido
* DESCR_PROFISSAO -	Profissão do envolvido
* CONT_PESSOA -	NÚMERO DE ORDEM DE REGISTRO DA PESSOA NO BO
* DESCR_RELACIONAMENTO -	Relacionamento entre a vítima e o autor
* FLAG_INTOLERANCIA -	Indica se houve intolerância (S= sim; N=não)
* TIPO_INTOLERANCIA -	Tipo de intolerância
* DESCR_TOXICO -	descrição do entorpecente apreendido
* DESCR_UNIDADE -	unidade de medida do entorpecente apreendido
* QTDE_ENCONTRADA -	quantidade do entorpecente apreendido
* DATAHORA_IMPRESSAO_BO -	Data-Hora da elaboração da impressão
* CONT_ENTORPECENTE -	NÚMERO DE ORDEM DE REGISTRO DO ENTORPECENTE NO BO
* CONT_PESSOA -	NÚMERO DE ORDEM DE REGISTRO DA PESSOA NO BO
* FLAG_FLAGRANTE -	Indica se houve flagrante (S= sim; N=não)
* DESCR_MODO_OBJETO -	Situação do objeto na ocorrência
* DESCR_TIPO_OBJETO -	Tipo de objeto - grande categoria
* DESCR_SUBTIPO_OBJETO -	Subtipo de objeto
* CONT_OBJETO -	Identificação do Objeto na Ocorrência
* DESCR_UNIDADE -	Unidade de contagem do objeto
* DESCR_TIPO_VEICULO -	Tipo de Veículo
* DESCR_OCORRENCIA_VEICULO -	Envolvimento do veículo na ocorrência
* DESCR_MARCA_VEICULO -	Marca/MODELO
* ANO_FABRICACAO -	Ano de Fabricação
* DESCR_COR_VEICULO -	Cor do Veículo
