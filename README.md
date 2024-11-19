
# Projeto Disciplina: Requisitos de Software

Olá! Este repositório faz parte do projeto da disciplina de Requisitos de Software da UTFPR - Campus Cornélio Procópio. 

Link do Padlet:https://padlet.com/silviohenriquemnds/meu-padlet-requintado-tkvo6qru5c0ilzyc

## 1. Introdução

***1.1.  Nexux***

NOME                               |GitHub
-----------------------------------|----------------------------------------
Julio Cesar Giandoso Filho         |-> https://github.com/JuliooCezar
Rafael Tomé da Silva               |-> https://github.com/RafaelTomee
Silvio Henrique Mendes dos Santos  |-> https://github.com/silvioGPS
Gustavo Gonçaves de Barros         |-> https://github.com/GustavoGBarros
Jefferson Lima Silva               |-> https://github.com/JeffersonLimaSilva
----------------------------------------------------------------------------

***1.2.  Nome do Sistema***
MMC

***1.3.  Propósito do Sistema***

O MMC é um sistema completo para gerenciamento de operações comerciais, que abrange desde o controle de estoque até o gerenciamento financeiro. Seu objetivo é otimizar o processo de administração das lojas de conveniência e lanchonetes independentes, proporcionando maior eficiência, redução de erros e tomada de decisões mais assertivas.

***1.2.  Público Alvo***

O sistema MMC é voltado para lojas de conveniência e lanchonetes independentes que necessitam de uma solução prática e eficaz para administrar suas operações de forma integrada. O foco está em negócios de pequeno a médio porte, que buscam uma plataforma intuitiva e acessível, com o objetivo de otimizar suas rotinas diárias e reduzir os custos operacionais.

***1.3. Descrição dos usuários***

    Idade: 30 a 50 anos
    Formação: Empresários ou profissionais com experiência em gestão de pequenos negócios, como donos de lanchonetes ou lojas de conveniência.
    Objetivos: Obter uma visão geral e detalhada das operações, controlar estoques, gerenciar finanças e otimizar a tomada de decisões com base em relatórios detalhados.

Principais Tarefas:

    Visualizar relatórios de vendas, lucros e despesas.
    Gerenciar o estoque, incluindo compras e reposição de produtos.
    Analisar o fluxo de caixa e controlar as finanças do negócio.
    Monitorar o desempenho da equipe e realizar ajustes operacionais.
    
***Personas:***

*<Imagem, arquivo (PDF), link com as Personas.>*

***Análise da situação atual: antes da introdução de sua solução***

*`1. O que as pessoas fazem?`*
Antes da introdução do sistema MMC, as operações em lojas de conveniência e lanchonetes independentes muitas vezes são feitas
de maneira manual ou utilizando ferramentas isoladas, como planilhas de Excel, anotações em papel, ou sistemas específicos de
cada área (estoque, financeiro, vendas). Isso resulta em um processo fragmentado e ineficiente, com risco de erros, falta de 
visibilidade e dificuldades para integrar informações.

Geralmente, os donos ou gerentes são responsáveis por tudo, desde a gestão do estoque até o controle financeiro. Muitas vezes,
eles não têm uma visão clara de como as finanças e o estoque estão realmente sendo gerenciados, já que dependem de relatórios 
manuais e não têm acesso a informações em tempo real.

*************`2. Quais os artefatos envolvidos?`*****************

Planilhas de Excel:
Usadas para o controle de estoque, fluxo de caixa e registros de vendas. Embora amplamente utilizadas, as planilhas são
suscetíveis a erros, inconsistências e falta de atualização em tempo real, além de dificultarem a análise de dados em conjunto.

Anotações manuais:
O uso de cadernos ou papéis para registrar informações sobre vendas, reposições de estoque e outras atividades operacionais é comum.
Esse processo é altamente propenso a erros, perda de informações e falta de padronização.

Sistemas de PDV isolados:
Embora as lojas de conveniência e lanchonetes usem sistemas de PDV para registrar vendas e pagamentos, esses sistemas geralmente não
estão conectados a outras áreas do negócio (estoque, finanças), o que dificulta a visão integrada da operação.

Relatórios financeiros manuais:
Muitos negócios ainda dependem de relatórios financeiros feitos manualmente, o que gera atrasos na entrega de informações precisas e
dificulta a tomada de decisões rápidas e informadas.

Controle de estoques em papel:
O controle de entradas e saídas de mercadorias muitas vezes é feito com anotações manuais ou simples planilhas, o que pode resultar em
desvios, desorganização e dificuldade de rastrear a origem de problemas no estoque (como falta ou excesso de produtos).

*`3. O que elas precisam saber?`*

As pessoas que operam em lojas de conveniência e lanchonetes independentes, para otimizar suas funções, precisam de acesso a informações
claras, precisas e em tempo real para facilitar a tomada de decisões, aumentar a eficiência e evitar erros.

Visão financeira detalhada: Precisam entender o fluxo de caixa, as despesas e as receitas em tempo real para garantir a saúde financeira do negócio.
Análises de desempenho: Como as vendas estão se comportando, quais produtos estão tendo maior saída, qual é a rentabilidade por categoria e outros 
indicadores de performance.Situação do estoque: Quais produtos estão em falta, quais precisam ser reabastecidos ou descartados, e se há itens com
validade próxima do vencimento.

***Análise das tarefas depois: como serão executadas as suas tarefas com sua solução:***

*`1. O que as pessoas fazem?`*
*`2. Quais os artefatos envolvidos?`*
*`3. O que elas precisam saber?`*

***Cenário: Antes***

*<Preencher com o cenário idealizado antes da aplicação do seu sistema.>*

***Cenário: Depois***

*<Preencher com o cenário idealizado depois da aplicação do seu sistema.>*

## 2. Documentos gerais no repositório

***2.1. Requisitos Funcionais***

*<Link, imagem, arquivo com os requisitos funcionais.>*

Identificador   | Descrição                                                                     | Prioridade       | Dependente      | 
--------------------------------------------------------------------------------------------------------------------------------------
RF01            | O sistema deve permitir que o usuário consulte, adicione, edite e remova      | Alta             |                 |
                | produtos do estoque, incluindo informações como quantidade, preço, validade   |                  |                 |
                | e descrição.                                                                  |                  |                 |
--------------------------------------------------------------------------------------------------------------------------------------
RF02            | O sistema deve permitir gerar relatórios detalhados e gráficos que apresentem | Alta             | RF04, RF03, RF01|
                | receitas, despesas, lucros, fluxo de caixa e vendas diárias, semanais ou      |                  |                 |
                | mensais.                                                                      |                  |                 |
--------------------------------------------------------------------------------------------------------------------------------------                
RF03            | O sistema deve possibilitar o cadastro, edição e exclusão de clientes e       | Média            | RF04, RF02      |
                | fornecedores, incluindo informações como nome, contato, histórico de          |                  |                 |
                | compras/vendas e pagamentos realizados.                                       |                  |                 | 
--------------------------------------------------------------------------------------------------------------------------------------      
RF04            | O sistem deve realizar transações de venda com cálculos automáticos de        | Alta             | RF03, RF01      |
                | valores, aplicação de descontos e emissão de recibos ou notas fiscais.        |                  |                 | 
--------------------------------------------------------------------------------------------------------------------------------------     
RF05            | O sistema deve permitir o registro, consulta e acompanhamento de feedbacks dos| Baixa            |                 |
                | clientes sobre produtos e serviços, com opções para marcar o status.          |                  |                 | 
--------------------------------------------------------------------------------------------------------------------------------------
RF06            | O sistema deve Enviar alertas para o usuário sobre produtos com baixa         | Média            | RF01            |
                | quantidade em estoque ou validade próxima do vencimento.                      |                  |                 |
--------------------------------------------------------------------------------------------------------------------------------------
RF07            | O sistema deve fornecer uma interface inicial com informações consolidadas em | Alta             | RF04, RF02, RF01|
                | tempo real sobre vendas, estoque, fluxo de caixa e desempenho geral.          |                  |                 | 
--------------------------------------------------------------------------------------------------------------------------------------
RF08            | O sistema deve disponibilizar uma funcionalidade de pesquisa para localizar   | Média            | RF04, RF03, RF01|
                | produtos, clientes, fornecedores ou transações rapidamente.                   |                  |                 |
--------------------------------------------------------------------------------------------------------------------------------------
RF09            | O sistema deve implementar autenticação e controle de acesso, definindo       | Alta             |                 |
                |diferentes níveis de permissão para usuários, como administradores e operadores|                  |                 | 
--------------------------------------------------------------------------------------------------------------------------------------
RF10            | O sistema deve conectar o sistema a terminais de ponto de venda (PDV) para    | Alta             | RF04, RF01      |
                | automatizar a entrada de vendas no sistema e manter os dados sincronizados em |                  |                 | 
                | tempo real.                                                                   |                  |                 | 
----------------|-------------------------------------------------------------------------------|------------------|-----------------|                             

***2.2. Requisitos Não Funcionais***

*<Link, imagem, arquivo com os requisitos não funcionais.>*

***2.3. Perguntas***

*<Arquivo com as perguntas realizadas na entrevista .>*

***2.4. Entrevista***

*<Arquivo com as respostas do indivíduo entrevistado e link do drive com upload da gravação.>*

***2.5. Histórias do Usuário***

*<Imagem, arquivo (PDF), link com as Histórias de Usuário.>*

***2.6. Diagramas de Caso de Uso e Especificações***

*<Imagem, arquivo (PDF), link com Diagrama de Caso de Uso.>*

***2.7. Diagramas de Atividades***

*<Imagem, arquivo (PDF), link com Diagrama de Atividades.>*

***2.8. Matrizes de Rastreabilidade***

*<Imagem, arquivo (PDF), link com Matriz de Rastreabilidade.>*

***2.9. Protótipos***

*<Imagem, arquivo (PDF), link com Protótipo.>*

## Referências

*<Esta seção é destinada à descrição das referências utilizadas pelo documento, como por exemplo, URLs e livros. Ver exemplo a seguir:>*

[1] “Glossário da _USina_”, <_id_doc glossário_>, Versão <_versão_>. Localização: <_localização_>.
