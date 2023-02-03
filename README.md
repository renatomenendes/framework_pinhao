# Framework Pinhão

<br>
<img src="/img/logo.png" alt="My cool logo" height=600 width=1010>
<br>


| <img src="/img/ind1.png">                                                                                                                                                        | <img src="/img/ind2.png">                                                                                                  |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------|
|1. [Origem](https://github.com/renatomenendes/framework_pinhao/README.md#1-origem)                                                                                     |4. [Camada visual](https://github.com/renatomenendes/framework_pinhao/README.md#4-camada-visual)                 |
|2. [Pré-requisitos](https://github.com/renatomenendes/framework_pinhao/README.md#2-pr%C3%A9-requisitos)                                                                |    4.1 [Iconografia](https://github.com/renatomenendes/framework_pinhao/README.md#41-iconografia)               |
|    2.1 [Padronização de arquivos de CSV/EXCEL](https://github.com/renatomenendes/framework_pinhao/README.md#21-padroniza%C3%A7%C3%A3o-de-arquivos-de-csvexcel)        |    4.2 [Letra](https://github.com/renatomenendes/framework_pinhao/README.md#42-letra)                           |
|    2.2 [Padronização da tabela](https://github.com/renatomenendes/framework_pinhao/README.md#22-padroniza%C3%A7%C3%A3o-da-tabela)                                     |    4.3 [Cores](https://github.com/renatomenendes/framework_pinhao/README.md#43-cores)                           |
|    2.3 [Permissionamento](https://github.com/renatomenendes/framework_pinhao/README.md#23-permissionamento)                                                           |    4.4 [Números em Geral](https://github.com/renatomenendes/framework_pinhao/README.md#44-n%C3%BAmeros-em-geral)|
|    2.4 [Direcionamento](https://github.com/renatomenendes/framework_pinhao/README.md#24-direcionamento)                                                               |5. [Wireframe](https://github.com/renatomenendes/framework_pinhao/README.md#5-wireframe)                         |
|3. [Padronização dos arquivos e da (s) tabela(s)](https://github.com/renatomenendes/framework_pinhao/README.md#3-padroniza%C3%A7%C3%A3o-dos-arquivos-e-da-s-tabelas)   |                                                                                                                            |
|                                                                                                                                                                                                                                                                                                               |
| <img src="/img/ind3.png">                                                                                                                                                        | <img src="/img/ind4.png">                                                                                                  |
|6. [Arquitetura](https://github.com/renatomenendes/framework_pinhao/README.md#6-arquitetura)                                                                           |7. [Documentação](https://github.com/renatomenendes/framework_pinhao/README.md#7-documenta%C3%A7%C3%A3o)         |
|    - [Desenvolvimento](https://github.com/renatomenendes/framework_pinhao/README.md#devhomol)                                                                         |    7.1 [Controle](https://github.com/renatomenendes/framework_pinhao/README.md#71-controle)                     |
|    - [Homologação](https://github.com/renatomenendes/framework_pinhao/README.md#devhomol)                                                                             |    7.2 [Cálculos](https://github.com/renatomenendes/framework_pinhao/README.md#72-c%C3%A1lculos)                |
|    - [Produção](https://github.com/renatomenendes/framework_pinhao/README.md#producao)                                                                                |    7.3 [Especifiçação](https://github.com/renatomenendes/framework_pinhao/README.md#73-especifica%C3%A7%C3%A3o) |
|                                                                                                                                                                                  |    7.4 [Evidência](https://github.com/renatomenendes/framework_pinhao/README.md#74-evid%C3%AAncia)              |
|                                                                                                                                                                                  |    7.5 [Detalhe Filtro](https://github.com/renatomenendes/framework_pinhao/README.md#75-detalhe-filtro)         |
|                                                                                                                                                                                  |    7.6 [Modelagem](https://github.com/renatomenendes/framework_pinhao/README.md#76-modelagem)                   |
    
<br>

## Por que Pinhão?

<br>

<p>Pinhão é a designação genérica da semente de várias espécies de pinaceaes e araucariaceaes, plantas gimnospérmicas, isto é, cuja semente não se encerra num fruto. O pinhão se forma dentro de uma pinha, fechada, que com o tempo vai-se abrindo até liberar o pinhão. Nas pináceas (a exemplo do Pinus elliottii), as sementes são dotadas de uma película, como uma espécie de asa, que se descola da pinha madura e possibilita que as sementes sejam espalhadas pelo vento, iniciando-se assim o processo de crescimento de um novo pinheiro. <br>
	
<p>No Brasil, o termo “pinhão” geralmente designa as sementes da Araucaria angustifolia, árvore de destacada importância cultural, econômica e ambiental no sul e em algumas partes do sudeste do Brasil. Já em Portugal, o termo “pinhão” (ou penisco) designa o que no Brasil se chama de “pinhão miúdo” (ou pinolo, em italiano), que vem do pinheiro-manso e é bem menor que o pinhão brasileiro. <br>
	
<p>O Pinhão tem uma disposição Clean dentro da pinha além do degrade natural das cores que ajuda a destacar o pinhão da pinha. Assim como na fruta, o Framework é focado no ágil para toda solução de front seja em Big Data ou BI e não leva em consideração a solução (PowerBI, Tableau, Oracle Biee) em uso no momento do desenvolvimento, pois se molda a cada particularidade das ferramentas utilizadas. O desenvolvimento foi realizado pensando em todo projeto que é necessário desenvolver soluções de front (gráficos e dashboard’s), sem depender de uma estrutura de dados parruda para o desenvolvimento.<br>

<br>
	
## <a id="origem" />1. ORIGEM
	
<p>Com o aumento de projetos em BI e Big Data sempre se faz necessário desenvolvimento de Dashboard para suportar a tomada de decisão, porém nem sempre temos estruturas de dados prontas para atender o desenvolvimento dos relatórios e foi aí que o pinhão surgiu. Porque temos que nos prender a grandes estruturas de dados, se podemos utilizar arquivos para esse desenvolvimento de forma mais simples e objetivas, mantendo sempre o foca em entregas rápidas sem perder a qualidade. <br>
<p>Primeiramente foi feito entendimento com key user e se os dados que ele trabalhava eram provenientes de arquivos Excel ou já executava consultas em alguma estrutura de dados com uso de SQL. Por sua vez solicitamos uma amostragem de dados para entender se todas as perguntas que precisavam ser respondidas seriam respondidas com apenas os dados que estava sendo utilizado. Foi nesse momento que entendemos que poderíamos fazer todo o desenvolvimento sem ter necessidade de aguarda toda a estrutura de dados ficar pronta, bastava apenas montar um arquivo excel ou uma tabela (ambos de forma temporária), com colunas na mesma estrutura final a ser entregue (já que isso não um tempo tão grande). <br>

<p>Entendemos então que precisamos apenas padronizar a informação inicial com os tipos certos (tanto no arquivo, quanto na tabela), para que pudéssemos iniciar o desenvolvimento e desse ponto em diante teríamos que focar na homologação, parte visual (iconografia, cores, fonte) e regras de negócio para o wireframe.<br>

<br>
	
## <a id="requisitos" />2. PRÉ-REQUISITOS	

<p>Este Framework foi desenvolvido para qualquer solução de front em dados e isso significa que é necessário conhecimento prévio da solução utilizada pela companhia, além de conhecer sobre arquivos (CSV e Excel) e base dados. Caso não tenha este conhecimento prévio você terá uma dificuldade maior em entender o contexto deste Framework e sua essência, por isso recomendamos fortemente que leia sobre banco de dados, arquivos (CSV e Excel) e principalmente sobre a solução de front utilizada pela companhia. <br>

<p>Também precisamos ter de forma clara, definida e aprovada:</br>

* Arquitetura: Desenho de arquitetura aprovada pelo cliente. Caso o cliente não tenha podemos auxiliar no desenvolvimento. Temos que ter definido se vamos trabalhar com arquivos (Excel | CSV), tabelas, repositório para o desenvolvimento (local onde será disponibilizado os arquivos de documentação e da ferramenta de front) e aplicações para carga dos dados, armazenamento e apresentação (Solução de Front).<br>

* Dados: Os responsáveis pelas origens dos dados (Nome(s) e e-mail(s)), cargas e manutenções dos mesmos. Após recebimento será enviado um e-mail com uma amostra de dados (nesse caso aguardaremos retorno do responsável informando que a amostragem de dados está ok e é confiável). <br>

* Acesso: Qual(is) usuário(s) serão liberados em qual(is) ambiente(s) (Sistema Operacional e Banco de dados) e quais suas responsabilidades.<br>

<br>

### <a id="padronizacaoarq" />2.1 PADRONIZAÇÃO DE ARQUIVOS DE CSV/EXCEL

<p>Por convenção, nem todos os arquivos que recebemos estão no formato UTF8 e para que não tenhamos problemas quando for refeito o apontamento devemos ajustar o arquivo para esse padrão. Logos após isso devemos padronizar o nome das colunas com usando o arquivo Conversor Entidades Atributos.<br>

<br>
	
### <a id="padronizacaotab" />2.2 PADRONIZAÇÃO DA TABELA	

<p>Devemos ter as colunas com nome padrão seguindo arquivo Conversor Entidades Atributos, para mantermos sempre o mesmo padrão em todos os desenvolvimentos. <br>

<br>
	
### <a id="permissionamento" />2.3 PERMISSIONAMENTO

<p>É muito importante que esteja claro que os usuários no ambiente de Desenvolvimento tenham permissão para manipular os arquivos (CSV e Excel) e nas tabelas para um desenvolvimento mais eficiente e assertivo. Quanto ao ambiente de produção é importante o uso de usuário de sistema por conta das querys não sofrerem com acesso de usuário tradicional.<br>

<br>
<blockquote>OBS.: é importante e recomendável que todo o ambiente de produção assim como os usuários que permitem acesso serem de responsabilidade do cliente e não da Everis por questões de segurança e LGPD.</blockquote>

<br>

### <a id="direcionamento" />2.4 DIRECIONAMENTO

<p>Todo desenvolvimento para ser preciso deve atender o key user da melhor maneira possível. Tendo isso em vista temos algumas perguntas que precisam ser respondidas para que possamos ser assertivos no desenvolvimento.<br>

* Arquitetura:

	1.	Esse Dashboard será desenvolvido a fim de ser utilizado em Navegadores de internet? Caso sim qual?<br>
	2.	Fisicamente eles serão exibidos em Notebook, TV, Desktop, Tablet, celular ou impresso? Com qual resolução e definição?<br>
	3.	Temos referência do equipamento que vamos utilizar (Marca, modelo e Sistema Operacional)?<br>
	4.	Qual a massa de dados no banco? <br>
		1) Caso não saiba ou tenha referência é possível disponibilizar um Excel com o modelo de dados para ir desenvolvendo?<br>
		2) Se você já utiliza o banco de dados é possível compartilhar a query (código com tabelas e campos)? <br>

* UX:

	1.	Quais perguntas do negócio eu quero responder com esse Dashboard?<br>
	2.	Quem vai acessar o Dash (CEO, diretoria, gerencia, operacional)?<br>
	3.	Quais filtros eu preciso ter?<br>
	4.	Qual período devo manter nesse Dashboard (1 mês, 1 semana, 6 meses ou 1 ano)?<br>
		1) Como tratar o mês corrente (mês atual)?<br>
		2) Após definir o período (por exemplo 12 meses) devo manter o mês corrente + 12 meses ou 11 meses + o mês corrente?<br>

<br>
	
## <a id="padronizacao" />3. PADRONIZAÇÃO DOS ARQUIVOS E DA (S) TABELA(S)

<p>Juntamente com esse documento será disponibilizado o arquivo (Conversor Entidades Atributos), que nos ajuda a manter o padrão quanto ao nome das colunas. Sua utilização é bem simples.<br>

<p>No arquivo abra a guia conversor e insira o nome das colunas na coluna A (Nome Conceitual do Objeto) removendo do nome toda e qualquer preposição (de, da, do, e, a, o). O resultado do nome será apresentado junto a coluna AO e AP (Nome Físico).<br>

<p>Este é o resultado:<br>  

<br>
<img src="/img/padronizaarquivo.png" alt="Padroniza Arquivo" >
<br>	

<p>Essas colunas são as mesmas que o Arquiteto de soluções ou Engenheiro de dados vai implementar e porquê disso, simplesmente porque garante que ao ser reapontado a estrutura dentro da solução não sofra nenhuma alteração no que já foi desenvolvido apenas atualize os dados já que a camada semântica nesse caso é a mesma. Também levamos em conta que todo o cálculo realizado não terá impacto no desenvolvimento já que o nome dos campos permanece o mesmo.<br>

<p>Raramente você terá de mexer neste projeto. Ele não será sustentado por nenhuma Squad ou equipe de TI e também não será evoluído a não ser que você necessite adequar a sua necessidade e incluir novas funcionalidades que façam sentido para o contexto do projeto no qual está atuando.<br>

<br>
	
## <a id="visual" />4. CAMADA VISUAL

<p>Afim de um maior aproveitamento dos Dashboard precisamos fazer com que o desenvolvimento seja atrativo e que ajude nas tomadas de decisões que o key user precisa fazer sem ter muito esforço e sem que a análise seja cansativa.

<br>
	
### <a id="iconografia" />4.1 ICONOGRAFIA

<p>Devemos utilizar ícones para comportar o entendimento do desenvolvimento e reduzir ainda mais o impacto analítico por parte dos usuários.<br>

<br>
<img src="/img/iconografia.png"> 
<br>
	
<p>Os ícones devem ser solicitados ao time de marketing da companhia no qual o projeto está sendo realizado afim de manter o padrão interno.<br>

<br>
	
### <a id="letra" />4.2 LETRA

<p>Por padrão, sempre devemos orientar em utilizar o tipo de letra padrão da solução, já que tipo de letra desenvolvido por companhias pode interferir no desenvolvimento além de que a implementação deixa o processo mais complexo.<br>
	
<p>É importante sempre utilizar um formato que seja legível não apenas para usuários tradicional, mas também por qualquer usuário que possa ter algum problema relacionado a visão, sem deixar de levar em conta o local onde o desenvolvimento será realizado (notebook, monitores ou celulares), pois o tamanho da letra influencia no esforço a ser realizado.<br>

<br>
	
### <a id="cores" />4.3 CORES

<p>As cores nos ajudam na tomada de decisão, além de facilitar o entendimento dos gráficos quando por exemplo se trata de mapa de calor ou até mesmo sobre falar sobre valores positivos ou negativos.<br>

<p>Recomendamos que seja feito o desenvolvimento seguindo a paleta de cores do cliente para que dessa forma o cliente sinta que são da corporação além de compreender que a definição possa ter vindo de uma área especifica. Caso o cliente não possua podemos extrair as cores do próprio site do cliente.<br>

<p>Extraímos as cores usando alguns sites:<br>
	
* Adobe: Para acessar o site [clique aqui](https://color.adobe.com/es/create/color-wheel). Você pode carregar uma imagem e obter tanto o RGB quanto o HEX. <br>

<br>
<img src="/img/cores_adobe.png">
<br>
	
* Imagecolorpicker: Nele você pode carregar a imagem diretamente. [Clique aqui](https://imagecolorpicker.com/) para acessar. <br>

<br>
<img src="/img/cores_imagecolorpicker.png">
<br>
	
* Variações: Não deixando ninguém de fora temos também variações de cores ou paleta de cores direcionadas ao daltonismo. [Clique aqui](https://color.adobe.com/es/create/color-accessibility) para acessar.<br>

<br>
<img src="/img/cores_imagecolorpicker_nopia.PNG">
<br>
		
### <a id="numeros" />4.4 NÚMEROS EM GERAL

<p>Todo desenvolvimento tem como principal objeto ser direcionado ao público para o qual ele deve atender uma demanda e para isso vamos ter que configurar os números para um melhor entendimento e para tanto temos:<br>
	
- Percentual: Sempre deve ser seguindo pelo símbolo %.<br>
- Moeda: Saber qual nacionalidade, pais ou de qual forma o gráfico ou Dashboard vai ser difundido ajuda a utilizada da moeda (real, dólar, euro, peso).<br>
- Casas Decimais: Converse com o key user afim de ter definido previamente a quantidade de casas decimais a serem utilizadas no projeto.<br>

<br>
	
## <a id="wireframe" />5. WIREFRAME 

<p>Antes do desenvolvimento temos que ter o ok por e-mail da estrutura visual do Dashboard. Onde estarão os objetos dentro do Dashboard, afim de mantermos um padrão para o local onde será aplicado o título, filtros, rodapé área de gráficos.<br>
	
<br> 
<img src="/img/wireframe1.png">
<br> 

* Para o desenvolvimento e aprovação vamos utilizar a ferramenta Figma. Além de auxiliar no entendimento da solução final nos ajuda a explicar melhor ao key user como vai ficar o integrável e o que pode ser esperado. Basta [clicar aqui](https://www.figma.com/) para acessar a solução. <br>


<br>
<img src="/img/wireframe2.png">
<BR>
	
<br>
<blockquote>OBS.: Somente após aprovação por e-mail podemos dar início ao desenvolvimento da solução.</blockquote>
<br>

## <a id="arquitetura" />6. ARQUITETURA

<p>Afim de termos uma arquitetura eficiente devemos auxiliar o cliente no desenho da solução.<br>

* <a id="devhomol" />Desenvolvimento | Homologação: Essa estrutura somente o desenvolvedor terá acesso e por isso ele é quem é responsável pelo controle de versão do que foi desenvolvido. Esse controle pode ser feito renomeando os arquivos assim como fazendo uso de repositório em Cloud ou do repositório que o próprio cliente tenha acesso.<br> 
	
<p>No ambiente de desenvolvimento vamos utilizar uma pequena amostragem de dados disponibilizada pelo usuário (Excel, CSV ou Tableas) e nesse momento iniciamos fazendo apontamento para essa estrutura de dados.<br>
	
<p>Ao final enviamos um e-mail ao cliente informando que precisamos que acesse o ambiente para homologar toda a parte visual do relatório e qual o prazo que precisamos de retorno com aceite ou não do que foi desenvolvido.<br>

* <a id="producao" />Produção: Se ajustar para replicar os desenvolvimentos realizados em Desenvolvimento e Homologação para produção.<br>

<p>Nesse caso termos definido a data para conclusão da migração entre os ambientes e consecutivamente agendamento para passagem de conhecimento do que foi desenvolvido ao responsável no cliente.<br>

<br>
	
## <a id="documentacao" />7. DOCUMENTAÇÃO

<p>Todo projeto em um certo ponto chega ao fim ou se mantem em melhoria continua e para que não fique nenhum assunto sem cobertura é importante documentar e para isso temos o arquivo (Documentação - Relatório), afim de evidenciar todo o desenvolvimento. Nesse documento iremos tratar: <br>

<br> 
<img src="/img/documentacao.png" >
<br>
	
### <a id="controle" />7.1 CONTROLE

<p>Teremos algumas informações pertinentes ao projeto:<br>
	
- Nome do projeto.<br>
- Responsável no cliente e pelo desenvolvimento.<br>
- Data tanto de assinatura quanto da criação do documento.<br>
- Amostra visual do que foi desenvolvido. Nesse caso cada gráfico ou filtro chamamos de área.<br> 

<br>
<img src="/img/controle.png" height=600 width=900>
<br>
	
### <a id="calculos" />7.2 CÁLCULOS

<p>Todo o cálculo realizado ao desenvolvimento de cada gráfico será reportado nessa guia.<br>
	
- Coluna| Medida: Nome utilizado em cada medida e dimensão.<br>
- Descrição Técnica da Tabela: Local de origem de nome da tabela.<br>
- Regra: Regra de negócio com sua definição.<br>
- Cálculo: Calculo realizado dentro da solução.<br>
- Uso: Gráficos onde esse cálculo é utilizado. <br>
- Tipo de dado: Tipo de dado apresentado ao ser executado o cálculo.<br>
- Exemplo de dado: Amostragem da informação gerada.<br>
	
<br>
<blockquote>OBS.: Descrição completar que auxilia no entendimento do processo quando necessário.</blockquote>
<br>

### <a id="especificacao" />7.3 ESPECIFICAÇÃO

<p>Vamos descrever todo o processo relacionado a cada item apresentado no gráfico, desde onde o filtro é aplicado até o valor esperado. Para tanto temos:<br>
	
- Janela: faz refência a imagem apresentada na guia controle.  Cada Dashboard será referenciado como uma janela.<br>
- Código: código de controle que referencia a quantidade de janelas.<br>
- Nome: Nome dado em cada gráfico ou filtro se estiver se referenciando aos filtros.<br>
- Data Homologação: Data na qual o key user realizou a homologação.<br>
- OK/NOK: Se o teste realizado está funcionando ou não.<br>
- Comentários: em caso de erros o key user informa quais erros encontrou para que possamos corrigir antes de entrar em produção.<br>
- Cenários: Todos os cenários de testes realizados.<br>
- Instruções de execução: Detalhe de execução.<br>
- Parâmetros de Entrada: Testamos sempre com 2 parâmetros, com filtro ou sem filtro.<br>
- Resultados Esperados: Possibilidade do que vai retornar no teste.<br>
- Resultados Obtidos: O resultado que será encontrado ao executar o teste dentro daquele cenário.<br>
- Comentários: Complemento de informação caso necessário.<br>
	
### <a id="evidencia" />7.4 EVIDÊNCIA

<p>Evidencias descritas e com imagens para que o próprio usuário possa realizar seus testes sem a necessidade de ajuda ou acompanhamento. Nessa guia o key user vai poder analisar gráfico a gráfico se o retorno esperado está de fato acontecendo.

<br>
	
### <a id="filtro" />7.5 DETALHE FILTRO	

<p>Todo resultado esperado nos filtros.<br>

<br>
<img src="/img/detalhefiltro.png">
<br>
	
### <a id="modelagem" />7.6 MODELAGEM	

<p>Modelagem dentro da ferramenta, apresenta possíveis relacionamentos realizados na ferramenta.<br>

<br>
<img src="/img/modelagem.png">
 
<br><br>
	
### Check-List
	
<p>Para facilitar, foi desenvolvido um Checklist para guiar o fluxo de operação do Framework.<br>

> Link para o [Check List](https://github.com/renatomenendes/framework_pinhao/checklist.md#check-list-framework-pinh%C3%A3o)
	
<br><br>	
	
### **Contato para dúvidas e sugestões:**<br>
@: renatomenendes@yahoo.com.br<br>
	
	renatomenendes@yahoo.com.br
