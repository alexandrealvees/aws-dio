# RELATÓRIO DE IMPLEMENTAÇÃO DE MEDIDAS DE SEGURANÇA

**Data:** 10/04/2025  
**Empresa:** Abstergo Farma Distribuidora  
**Responsável:** Alexandre Alves

## Introdução

Este relatório apresenta o processo de implementação de medidas de segurança na empresa Abstergo Farma Distribuidora, conduzido por João Silva. O objetivo do projeto foi elencar 3 medidas de segurança em conjunto com os serviços da AWS, com a finalidade de aumentar a segurança na empresa.

## Descrição do Projeto

O projeto de implementação de medidas de segurança foi dividido em 3 etapas, cada uma focada em uma solução de segurança com aplicação direta nas operações da empresa. A seguir, serão descritas as etapas da implementação:

### Medida 1: Amazon VPC (Virtual Private Cloud) com Subnets e Regras de Segurança
**Descrição de caso de uso:**  
Foi criada uma VPC dedicada para isolar os ambientes de produção e teste, com subnets públicas e privadas. Regras de segurança rigorosas foram aplicadas para limitar o acesso aos recursos da VPC, garantindo que apenas instâncias autorizadas possam se comunicar com sistemas sensíveis, como bancos de dados e servidores internos.

### Medida 2: AWS Identity and Access Management (IAM) com Políticas de Acesso Granular
**Descrição de caso de uso:**  
Foram implementadas políticas de IAM para gerenciar o acesso de usuários e sistemas aos serviços AWS de forma granular. Cada usuário ou grupo de usuários foi configurado com permissões específicas baseadas no princípio do menor privilégio, garantindo que apenas as pessoas ou serviços necessários possam acessar os recursos da empresa.

### Medida 3: AWS CloudTrail e AWS GuardDuty para Monitoramento e Detecção de Incidentes
**Descrição de caso de uso:**  
A AWS CloudTrail foi configurada para registrar todas as ações realizadas dentro da AWS, criando um histórico detalhado de atividades para auditoria e conformidade. Além disso, o AWS GuardDuty foi ativado para detectar comportamentos anômalos e potenciais ameaças, como acessos não autorizados ou atividades suspeitas, permitindo respostas rápidas a incidentes de segurança.

## Conclusão

A implementação das medidas de segurança na Abstergo Farma Distribuidora trouxe maior proteção para os dados sensíveis, reduziu riscos operacionais e fortaleceu a conformidade com normas de segurança e regulatórias. Essas medidas aumentaram a eficiência e a produtividade da empresa, garantindo maior confiança nos processos internos. Recomenda-se a continuidade da utilização das ferramentas implementadas, bem como a busca por novas tecnologias que possam melhorar ainda mais os processos de segurança da empresa.

## Anexos
- Manual de Configuração do Amazon VPC
- Relatório de Auditoria do AWS CloudTrail
- Documentação do AWS GuardDuty

**Assinatura do Responsável pelo Projeto:**  
João Silva
