# Challenge_BI_Alura
A proposta do Challenge BI da Alura foi criar um dashboard a cada semana e no final, um curriculum utilizando a ferramenta Power BI.
<p>A primeira empresa, <strong>Alura Log</strong>, necessita analisar dados sobre a <strong>log&iacute;stica</strong> de entregas do seu neg&oacute;cio.<br />A segunda empresa, <strong>Alura Shop</strong>, precisa de um dashboard para monitorar a campanha de <strong>marketing</strong> durante um m&ecirc;s.<br />A terceira empresa, <strong>Alura Store</strong>, precisa entender como anda a sua &aacute;rea <strong>financeira</strong>, pensando em <strong>hip&oacute;teses</strong>.</p>

<p>A primeira empresa, <strong>Alura Log</strong>, necessita analisar dados sobre a <strong>log&iacute;stica</strong> de entregas do seu neg&oacute;cio.<br />A segunda empresa, <strong>Alura Shop</strong>, precisa de um dashboard para monitorar a campanha de <strong>marketing</strong> durante um m&ecirc;s.<br />A terceira empresa, <strong>Alura Store</strong>, precisa entender como anda a sua &aacute;rea <strong>financeira</strong>, pensando em <strong>hip&oacute;teses</strong>.</p>
<h1><strong>Semana 01: Desafio de log&iacute;stica - Alura Log</strong></h1>
<p>No primeiro desafio, foram apresentadas as principais m&eacute;tricas da &aacute;rea para que as melhores decis&otilde;es possam ser tomadas. </p>
<p>Vamos verificar a qualidade dos servi&ccedil;os da Alura Log atrav&eacute;s de um dashboard criado no Power BI.</p>
<h3><span style="text-decoration: underline;"><strong>Base de Dados</strong></span></h3>
<ol>
<li>tabela pedidos - cont&eacute;m o registro de todos os pedidos feitos pelos clientes.</li>
<li>tabela produtos - cont&eacute;m os produtos cadastrados e seus valores.</li>
<li>tabela ve&iacute;culos - cont&eacute;m ve&iacute;culos registrados que fazem o transporte dos produtos</li>
<li>tabela estoque - cont&eacute;m o registro de estoque dos produtos por m&ecirc;s</li>
</ol>
<h3><span style="text-decoration: underline;">Ferramentas Utilizadas no Projeto</span></h3>
<p>Foi utilizado o Power BI para o desenvolvimento do Dashboard.</p>
<h3><span style="text-decoration: underline;">Tratamento dos Dados</span></h3>
<p><strong>Tabela Pedidos:</strong></p>
<ul>
<li>Altera&ccedil;&atilde;o da extens&atilde;o do arquivo (de .CSV para .csv)</li>
<li>Altera&ccedil;&atilde;o de tipo e localidade da coluna "Data da Compra" para Ingl&ecirc;s e posteriormente para portugu&ecirc;s.</li>
</ul>
<p>&nbsp;</p>
<p><strong>Tabela Estoque:</strong></p>
<ul>
<li>Na coluna "Data Atualiza&ccedil;&atilde;o", substitui&ccedil;&atilde;o dos caracteres "-" por "/",&nbsp; elimina&ccedil;&atilde;o do caracter "." e altera&ccedil;&atilde;o do tipo (de texto para data).</li>
</ul>
<p>&nbsp;</p>
<p><strong>Tabela Produtos:</strong></p>
<ul>
<li>Cria&ccedil;&atilde;o de uma nova coluna para separar Categoria e Produto.</li>
<li>Remo&ccedil;&atilde;o do Undescore e primeira letra de cada palavra em mai&uacute;sculo&nbsp; na coluna Produto.</li>
<li>Altera&ccedil;&atilde;o de tipo da coluna pre&ccedil;o.</li>
</ul>
<p>&nbsp;</p>
<p><strong>Tabela Ve&iacute;culos:</strong></p>
<ul>
<li>Primeira letra de cada palavra em mai&uacute;sculo na coluna Tipo.</li>
<li>Colunas no tipo correto.</li>
<li>ID Ve&iacute;culo padronizado apenas com n&uacute;meros inteiros.</li>
</ul>
<p>&nbsp;</p>
<h3><span style="text-decoration: underline;">M&eacute;tricas</span></h3>
<ul>
<li>Entregas no prazo.</li>
<li>Entregas antecipadas em 1 semana ou mais.</li>
<li>Entregas Atrasadas.</li>
<li>Entregas com 3 ou mais dias de atraso.</li>
<li>Faturamento.</li>
<li>Ve&iacute;culos dispon&iacute;veis.</li>
<li>M&eacute;dia de estoque.</li>
<li>M&eacute;dia de S2D.</li>
<li>Propor&ccedil;&atilde;o de pedidos por estado.</li>
  
  <h1>Semana 2: Desafio de marketing - Alura Shop</h1>
<p>O desafio dessa semana &eacute; um estudo de caso sobre m&eacute;tricas de Marketing. A AluraShop investiu em publicidade e agora ela precisa saber a efetividade dessa a&ccedil;&atilde;o atrav&eacute;s de um dashboard estrat&eacute;gico e objetivo.</p>
<h2>&nbsp;</h2>
<h3>Base de Dados</h3>
<p>A base de dados consiste em duas tabelas no formato JSON:</p>
<ul>
<li>Tabela dispositivos</li>
<li>Tabela idade e g&ecirc;nero</li>
</ul>
<h3>Ferramentas Utilizadas no Projeto</h3>
<p>Foi utilizado o Power BI para o desenvolvimento do Dashboard.</p>
<h3>Tratamento dos Dados</h3>
<p>Nas tabelas de Dispositivos e Idade e G&ecirc;nero, foram efetuados os seguintes tratamentos:</p>
<ul type="disc">
<li>Ajuste de tipagem</li>
<li>Substitui&ccedil;&atilde;o de underscore por espa&ccedil;o</li>
<li>Coloquei cada palavra em Mai&uacute;scula</li>
<li>Substitui&ccedil;&atilde;o dos valores null por 0</li>
<li>Substitui&ccedil;&atilde;o de c&eacute;lulas em branco por 0</li>
<li>Exclus&atilde;o das linhas contendo "All" na tabela de dispositivos.</li>
</ul>
<h3>M&eacute;tricas</h3>
<ul>
<li>Total de Investimento na campanha</li>
<li>Custo por clique</li>
<li>Total do investimento em que houve convers&atilde;o em compras</li>
<li>Total de Convers&atilde;o em compras</li>
<li>Taxa de convers&atilde;o</li>
<li>N&uacute;mero total de compras</li>
<li>Retorno do investimento (ROAS) agrupado por idade e g&ecirc;nero</li>
<li>Ticket m&eacute;dio de investimento por cada compra, agrupado por dispositivos</li>
<li>Jornada de compra desde a visualiza&ccedil;&atilde;o da p&aacute;gina at&eacute; a compra realizada</li>
<li>Valor de convers&atilde;o em compras por dia</li>
</ul>
<p>&nbsp;</p>
  
<h1>Semana 3 e 4: Desafio financeiro - Alura Store</h1>
<p>Para o &uacute;ltimo caso, criei um dashboard financeiro para a Alura Store, com a finalidade de verificar as principais m&eacute;tricas e posteriormente uma p&aacute;gina para realizar an&aacute;lises de diversos cen&aacute;rios.</p>
<h3>Base de Dados</h3>
<p>A base de dados &eacute; em um banco de dados no MySQL com a seguinte estrutura:</p>
<p><strong>Tabela Pedidos</strong></p>
<ul>
<li>Data da compra</li>
<li>ID pedido</li>
<li>ID produto</li>
<li>Quantidade</li>
</ul>
<p><strong>Tabela Produtos</strong></p>
<ul>
<li>ID produto</li>
<li>Categoria produto</li>
<li>Pre&ccedil;o</li>
<li>Custos</li>
</ul>
<p><strong>Tabela Vendedores</strong></p>
<ul>
<li>ID vendedor</li>
<li>Vendedor</li>
</ul>
<p><strong>Tabela Notas Fiscais</strong></p>
<ul>
<li>ID nota</li>
<li>ID pedido</li>
<li>ID vendedor</li>
<li>ID pedido</li>
<li>Imposto</li>
<li>Valor venda</li>
<li>N&uacute;mero da nota</li>
<li>Frete</li>
</ul>
<h3>Ferramentas Utilizadas no Projeto</h3>
<p>Foi utilizado o Power BI para o desenvolvimento do Dashboard e o MySQL para restaura&ccedil;&atilde;o do arquivo do banco de dados.</p>
<p>&nbsp;</p>
<h3>Tratamento dos Dados</h3>
<p style="margin: 0in; font-family: Calibri; font-size: 11.0pt;"><strong>Tabela Produtos</strong></p>
<ul style="direction: ltr; unicode-bidi: embed; margin-top: 0in; margin-bottom: 0in;" type="disc">
<li style="margin-top: 0; margin-bottom: 0; vertical-align: middle;"><span style="font-family: Calibri; font-size: 11.0pt;">Tipagem de dados</span></li>
<li style="margin-top: 0; margin-bottom: 0; vertical-align: middle;"><span style="font-family: Calibri; font-size: 11.0pt;">Troca de underscore por espa&ccedil;o e primeira letra mai&uacute;scula</span></li>
</ul>
<p style="margin: 0in; font-family: Calibri; font-size: 11.0pt;">&nbsp;</p>
<p style="margin: 0in; font-family: Calibri; font-size: 11.0pt;"><strong>Tabela Vendedores</strong></p>
<ul style="direction: ltr; unicode-bidi: embed; margin-top: 0in; margin-bottom: 0in;" type="disc">
<li style="margin-top: 0; margin-bottom: 0; vertical-align: middle;"><span style="font-family: Calibri; font-size: 11.0pt;">Tipagem de dados</span></li>
<li style="margin-top: 0; margin-bottom: 0; vertical-align: middle;"><span style="font-family: Calibri; font-size: 11.0pt;">Ajuste nos nomes dos vendedores </span></li>
<li style="margin-top: 0; margin-bottom: 0; vertical-align: middle;"><span style="font-family: Calibri; font-size: 11.0pt;">Troca de nome de um vendedor que estava duplicado</span></li>
</ul>
<p style="margin: 0in; font-family: Calibri; font-size: 11.0pt;">&nbsp;</p>
<p style="margin: 0in; font-family: Calibri; font-size: 11.0pt;"><strong>Tabela Notas Fiscais</strong></p>
<ul style="direction: ltr; unicode-bidi: embed; margin-top: 0in; margin-bottom: 0in;" type="disc">
<li style="margin-top: 0; margin-bottom: 0; vertical-align: middle;"><span style="font-family: Calibri; font-size: 11.0pt;">Tipagem de dados</span></li>
<li style="margin-top: 0; margin-bottom: 0; vertical-align: middle;"><span style="font-family: Calibri; font-size: 11.0pt;">Ajuste nos valores que continham "," na coluna valor_venda</span></li>
<li style="margin-top: 0; margin-bottom: 0; vertical-align: middle;"><span style="font-family: Calibri; font-size: 11.0pt;">Ajuste dos valores nas colunas frete e valor_venda</span></li>
</ul>
<p><span style="font-size: 11pt;"><strong><span style="font-family: Calibri;">M&eacute;tricas</span></strong></span></p>
<ul>
<li>Custos</li>
<li>Despesas</li>
<li>Lucro</li>
<li>Receita</li>
<li>Ticket M&eacute;dio</li>
</ul>
<p>&nbsp;</p>

<h1>Curriculum</h1>
<p>Para desenvolver meu CV, utilizei como refer&ecirc;ncia uma jogo de video game que jogava quando era crian&ccedil;a. Rock'n Roll Racing &eacute; um jogo de corrida, com uma tem&aacute;tica de fic&ccedil;&atilde;o cient&iacute;fica com uma trilha sonora contendo cl&aacute;ssicos do Rock.</p>
<p>Bem, isso j&aacute; mostra um pouco do que sou (al&eacute;m de entregar a idade): gosto de video games e ou&ccedil;o muito rock'n roll.</p>
<p>Utilizei o paint e power point para editar as imagens e para apresentar minhas habilidades e trajet&oacute;ria, algumas visualiza&ccedil;&otilde;es do Power BI cumpriram seu papel. O que n&atilde;o poderia faltar era a m&uacute;sica, e para isso, importei um visual de HTML para rodar a trilha sonora do pr&oacute;prio jogo enquanto a pessoa estiver olhando o arquivo.</p>
<p>O principal aprendizado com o Curriculum foi a din&acirc;mica dos Indicadores e Sele&ccedil;&otilde;es. Ter entendido como funcionam, vai permitir que os meus pr&oacute;ximos dashboards fiquem mais din&acirc;micos e interessantes.</p>
  
<h1>Links dos Dashboards</h1>
<p><strong>Semana 1: Alura Log</strong></p>
<p><a href="https://app.powerbi.com/view?r=eyJrIjoiMjFiNjBiZDgtNzBjOS00ZmFjLWIxZGMtMmQ0ZWVjYmJhMjg5IiwidCI6IjE3NWY1MTJhLWFlM2EtNDQ1MS1hYjQ2LTJjOWI3ZTFhNjg1OCJ9&amp;pageName=ReportSection">https://app.powerbi.com/view?r=eyJrIjoiMjFiNjBiZDgtNzBjOS00ZmFjLWIxZGMtMmQ0ZWVjYmJhMjg5IiwidCI6IjE3NWY1MTJhLWFlM2EtNDQ1MS1hYjQ2LTJjOWI3ZTFhNjg1OCJ9&amp;pageName=ReportSection</a> </p>
<p><strong>Semana 2: Alura Shop</strong></p>
<p><a href="https://app.powerbi.com/view?r=eyJrIjoiYzY4ZGRlMmYtMTRlZC00YmUyLTg4MzQtN2E1MmJhYzMyY2Y3IiwidCI6IjE3NWY1MTJhLWFlM2EtNDQ1MS1hYjQ2LTJjOWI3ZTFhNjg1OCJ9&amp;pageName=ReportSection">https://app.powerbi.com/view?r=eyJrIjoiYzY4ZGRlMmYtMTRlZC00YmUyLTg4MzQtN2E1MmJhYzMyY2Y3IiwidCI6IjE3NWY1MTJhLWFlM2EtNDQ1MS1hYjQ2LTJjOWI3ZTFhNjg1OCJ9&amp;pageName=ReportSection</a></p>
<p><strong>Semana 3: Alura Store</strong></p>
<p><a href="https://app.powerbi.com/view?r=eyJrIjoiNDEwZDgyMGEtNzY4NS00NzYyLTlkMTAtOTM5Zjc5Njk0NjE4IiwidCI6IjE3NWY1MTJhLWFlM2EtNDQ1MS1hYjQ2LTJjOWI3ZTFhNjg1OCJ9&amp;pageName=ReportSection">https://app.powerbi.com/view?r=eyJrIjoiNDEwZDgyMGEtNzY4NS00NzYyLTlkMTAtOTM5Zjc5Njk0NjE4IiwidCI6IjE3NWY1MTJhLWFlM2EtNDQ1MS1hYjQ2LTJjOWI3ZTFhNjg1OCJ9&amp;pageName=ReportSection</a></p>
<h3><strong>Curriculum</strong></h3>
<p><a href="https://app.powerbi.com/view?r=eyJrIjoiMjQyMjhjY2YtNTkwMi00NTczLWJlODAtYmMwZDE4NGQ3Mzk1IiwidCI6IjE3NWY1MTJhLWFlM2EtNDQ1MS1hYjQ2LTJjOWI3ZTFhNjg1OCJ9&amp;pageName=ReportSection76550faf86829a8f8b8d">https://app.powerbi.com/view?r=eyJrIjoiMjQyMjhjY2YtNTkwMi00NTczLWJlODAtYmMwZDE4NGQ3Mzk1IiwidCI6IjE3NWY1MTJhLWFlM2EtNDQ1MS1hYjQ2LTJjOWI3ZTFhNjg1OCJ9&amp;pageName=ReportSection76550faf86829a8f8b8d</a></p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
