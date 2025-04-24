# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 10/04/2025  
**Empresa:** Abstergo Farma Distribuidora  
**Responsável:** Alexandre Alves

## Introdução

Este relatório apresenta o processo de implementação de ferramentas baseadas na Amazon Web Services (AWS) na empresa Abstergo Farma Distribuidora, conduzido por João Silva. O objetivo principal foi identificar e implementar três serviços AWS estratégicos com foco em redução de custos operacionais imediatos e otimização da infraestrutura tecnológica voltada à cadeia de distribuição farmacêutica.

## Descrição do Projeto

O projeto foi dividido em três etapas, cada uma focada em um serviço AWS com aplicação direta nas operações da empresa. A seguir, descrevemos as soluções adotadas e seus respectivos casos de uso:

### Etapa 1: Amazon EC2 (Elastic Compute Cloud)
**Foco da ferramenta:** Virtualização de servidores de gestão de pedidos e faturamento

**Descrição de caso de uso:**  
Os servidores internos responsáveis pela gestão de pedidos, emissão de notas fiscais e controle de estoque foram migrados para instâncias EC2. Com isso, eliminou-se a necessidade de manutenção de servidores locais, otimizando a escalabilidade e permitindo crescimento sob demanda, especialmente em períodos de alta demanda (ex.: campanhas de vacinação ou aumento sazonal de vendas).

### Etapa 2: Amazon S3 (Simple Storage Service)
**Foco da ferramenta:** Armazenamento seguro de documentos regulatórios e históricos de pedidos

**Descrição de caso de uso:**  
Foram criados buckets S3 para armazenamento de documentos como receitas digitalizadas, laudos de qualidade, comprovantes de distribuição, além do histórico de transações com farmácias clientes. A política de ciclo de vida do S3 permite arquivamento automático de documentos antigos, reduzindo custos sem comprometer a conformidade com exigências da ANVISA e outras entidades reguladoras.

### Etapa 3: AWS Lambda
**Foco da ferramenta:** Automação de rotinas administrativas e logísticas

**Descrição de caso de uso:**  
Funções serverless foram utilizadas para automatizar tarefas recorrentes, como notificações de status de entrega para farmácias parceiras, auditorias automáticas de validade de medicamentos em estoque e geração de relatórios diários. A solução eliminou a necessidade de servidores para tarefas agendadas e aumentou a precisão e agilidade dos processos internos.

## Conclusão

A adoção de serviços AWS na Abstergo Farma Distribuidora trouxe eficiência operacional, redução imediata de custos com infraestrutura física, e aumento da capacidade de resposta frente à demanda de mercado. Além disso, garantiu maior segurança de dados sensíveis e conformidade com normas regulatórias do setor farmacêutico. Recomenda-se a continuidade do uso das ferramentas implementadas, bem como a exploração de outros recursos AWS, como o Amazon RDS e AWS IoT para rastreamento logístico.
