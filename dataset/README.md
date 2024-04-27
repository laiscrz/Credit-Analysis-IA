# 🎲 Dataset: Solicitações de Crédito da ABX Tecnologia

Este conjunto de dados contém informações sobre as solicitações de crédito recebidas pela ABX Tecnologia, uma empresa que atua no segmento de importação e revenda de produtos. O dataset é composto por 8974 solicitações de crédito de diversos clientes. Cada solicitação pode representar uma transação única de crédito de um cliente específico, e um mesmo cliente pode ter várias solicitações de crédito com valores distintos ao longo do tempo.

## 🎯 Objetivo
O objetivo deste dataset é fornecer insights para auxiliar na análise de crédito dos clientes da ABX Tecnologia. A análise desses dados pode ajudar a empresa a entender melhor o perfil de seus clientes, identificar padrões de comportamento e desenvolver estratégias mais eficazes para concessão de crédito.

## 📝 Colunas/Atributos

O presente dataset é composto por 38 colunas. Abaixo, você encontrará o nome, tipo e a descrição correspondente de cada uma:

| Nº | Coluna / Atributo           | Descrição                                                                                      | Tipo    |
|----|-----------------------------|------------------------------------------------------------------------------------------------|---------|
| 1  | numero_solicitacao          | Número único atribuído a cada solicitação de crédito.                                         | int64   |
| 2  | razaoSocial                 | Razão social da empresa solicitante, anonimizada para proteger a privacidade.                   | object  |
| 3  | nomeFantasia                | Nome fantasia da empresa solicitante, também anonimizado.                                      | object  |
| 4  | cnpjSemTraco                | CNPJ (Cadastro Nacional da Pessoa Jurídica) da empresa solicitante, anonimizado.               | object  |
| 5  | maiorAtraso                 | Maior atraso de pagamento em dias relatado pela empresa solicitante.                           | int64   |
| 6  | margemBrutaAcumulada        | Margem bruta acumulada da empresa, uma medida de rentabilidade.                                 | float64 |
| 7  | percentualProtestos         | Percentual de protestos relacionados à empresa solicitante.                                    | float64 |
| 8  | primeiraCompra              | Data da primeira compra registrada na empresa.                                                 | object  |
| 9  | prazoMedioRecebimentoVendas | Prazo médio de recebimento de vendas do cliente.                                                | int64   |
| 10 | titulosEmAberto             | Valor total de títulos em aberto, ou seja, valores devidos e ainda não pagos.                  | float64 |
| 11 | valorSolicitado             | Valor solicitado de crédito pela empresa.                                                       | float64 |
| 12 | status                      | Status da solicitação de crédito, indicando se foi aprovada, reprovada, etc.                   | object  |
| 13 | definicaoRisco              | Categoria de risco atribuída à solicitação de crédito.                                          | object  |
| 14 | diferencaPercentualRisco    | Diferença entre 1 e o percentual de risco, uma medida complementar ao risco.                   | float64 |
| 15 | percentualRisco             | Percentual de risco associado à solicitação de crédito, onde 0 indica baixo risco e 1 indica alto risco. | float64 |
| 16 | dashboardCorrelacao         | Uma métrica interna de correlação de risco, cujo significado pode não estar claro.             | float64 |
| 17 | valorAprovado               | Valor aprovado de crédito para a solicitação.                                                  | float64 |
| 18 | dataAprovadoEmComite        | Data de aprovação da solicitação por um comitê.                                                 | object  |
| 19 | periodoBalanco              | Período do balanço informado na documentação da empresa.                                       | object  |
| 20 | ativoCirculante             | Valor do ativo circulante informado na documentação da empresa.                                | float64 |
| 21 | passivoCirculante           | Valor do passivo circulante informado na documentação da empresa.                              | float64 |
| 22 | totalAtivo                  | Valor total do ativo informado na documentação da empresa.                                      | float64 |
| 23 | totalPatrimonioLiquido      | Valor total do patrimônio líquido informado na documentação da empresa.                        | float64 |
| 24 | endividamento               | Nível de endividamento da empresa.                                                              | float64 |
| 25 | duplicatasAReceber          | Valor total de duplicatas a receber informado na documentação da empresa.                       | float64 |
| 26 | estoque                     | Valor do estoque informado na documentação da empresa.                                          | float64 |
| 27 | faturamentoBruto            | Faturamento bruto informado na documentação da empresa.                                         | float64 |
| 28 | margemBruta                 | Margem bruta informada na documentação da empresa.                                              | float64 |
| 29 | periodoDemonstrativoEmMeses | Período do demonstrativo financeiro informado na documentação da empresa.                       | float64 |
| 30 | custos                      | Custos informados na documentação da empresa.                                                   | float64 |
| 31 | anoFundacao                 | Ano de fundação da empresa.                                                                    | float64 |
| 32 | intervaloFundacao           | Categoria do ano de fundação da empresa.                                                        | object  |
| 33 | capitalSocial               | Valor do capital social informado na documentação da empresa.                                   | float64 |
| 34 | restricoes                  | Flag indicando se existem restrições relacionadas ao cliente.                                    | object  |
| 35 | empresa_MeEppMei            | Flag indicando se a empresa é um microempreendedor individual (MEI), microempresa (ME) ou empresa de pequeno porte (EPP). | object  |
| 36 | scorePontualidade          | Score de pontualidade do cliente, onde 0 indica baixa pontualidade e 1 indica alta pontualidade. | float64 |
| 37 | limiteEmpresaAnaliseCredito| Limite de crédito fornecido por uma empresa externa de análise de crédito.                      | float64 |
| 38 | dataAprovadoNivelAnalista  | Data de aprovação da solicitação por um analista de crédito.                                   | object  |

## 


> Esse README fornece uma visão geral do dataset, seus objetivos e os problemas a serem resolvidos. A análise desses dados tem o potencial de transformar a abordagem da ABX Tecnologia na concessão de crédito, permitindo decisões mais informadas e estratégias mais eficazes para atender às necessidades de seus clientes.
