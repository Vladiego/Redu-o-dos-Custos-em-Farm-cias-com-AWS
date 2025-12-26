# Redu-o-dos-Custos-em-Farm-cias-com-AWS
Projeto DIO - Redução dos Custos em Farmácias com AWS

# RELATÓRIO DE MPLEMENTAÇÃO DE SERVIÇOS AWS
Data: 26/12/2025
Empresa: Abstergo Industries 
Responsável: Diego Bezerra de Lima
## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Diego Bezerra de Lima. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.
## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
Nome da ferramenta: Amazon EC2 com instâncias Spot e Reserved
Foco da ferramenta: Computação Elástica e Gestão de Capacidade.
Descrição de caso de uso: A empresa migra seu sistema de ERP e gestão de estoque para instâncias EC2. Para processos que não podem ser interrompidos, utiliza-se Instâncias Reservadas. Para processamento de relatórios pesados de vendas e análise de dados de logística, utilizam-se Instâncias Spot, que aproveitam a capacidade ociosa da AWS com descontos de até 90%.
Como reduz custos: Elimina o gasto com servidores físicos ligados 24/7 e utiliza modelos de compra baseados em demanda real.
Principal ganho: Alta escalabilidade para períodos de pico (ex: promoções sazonais) pagando o menor preço possível por CPU.

Etapa 2: 
Nome da ferramenta: Amazon S3 (Simple Storage Service) com Intelligent-Tiering
Foco da ferramenta: Armazenamento de objetos e conformidade de dados.
Descrição de caso de uso: Distribuidoras geram milhões de notas fiscais (XML) e registros de rastreabilidade que precisam ser guardados por anos por lei. O S3 Intelligent-Tiering move automaticamente arquivos que não são acessados há mais de 30 dias para camadas de armazenamento mais baratas (Archive), sem intervenção manual.
Como reduz custos: Reduz drasticamente o custo por GB ao não cobrar preço de "acesso rápido" para arquivos que são apenas para fins de auditoria.
Principal ganho: Automatização do ciclo de vida dos dados e durabilidade de 99%, garantindo conformidade regulatória (ANVISA).
Etapa 3: 
Nome da ferramenta: AWS Cost Explorer
Foco da ferramenta: Visibilidade de custos e previsão orçamentária.
Descrição de caso de uso: A ferramenta é utilizada para identificar quais centros de custo (ex: filial SP vs filial RJ) estão consumindo mais recursos. Através de relatórios detalhados, a empresa identifica "recursos zumbis" (discos ou IPs não utilizados) que estão gerando cobranças desnecessárias.
Como reduz custos: Identifica desperdícios em tempo real e permite criar alertas de orçamento para evitar surpresas na fatura mensal.
Principal ganho: Transparência financeira total, permitindo que a TI prove o ROI (Retorno sobre Investimento) para a diretoria.
## Conclusão
A transição da Abstergo Industries para a nuvem AWS, organizada por meio do Amazon EC2, S3 e Cost Explorer, evidencia que a diminuição de gastos em TI não precisa afetar a performance operacional. Ao contrário:
Eficiência Financeira: A transição do modelo de investimento em capital fixo (CapEx) para despesas operacionais (OpEx) permite que a empresa pague apenas pelo que consome, liberando fluxo de caixa para a expansão do estoque de medicamentos.
Agilidade Logística: Com servidores escaláveis e armazenamento inteligente, a empresa ganha velocidade no processamento de pedidos e na geração de relatórios de conformidade, fundamentais no setor farmacêutico.
Segurança e Governança: O controle total sobre os gastos e a durabilidade dos dados garantem que a distribuidora esteja pronta para auditorias regulatórias sem custos adicionais de infraestrutura
## Anexos
[lista de anexos, como manuais, documentos, planilhas, entre outros]
Assinatura do Responsável pelo Projeto:
[Nome do Responsável pelo Projeto]
