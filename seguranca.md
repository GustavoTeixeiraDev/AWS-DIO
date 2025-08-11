# Relatório de Projeto – Implementação de Medidas de Segurança na AWS

**Data:** 11/08/2025  
**Organização:** Abstergo Farma Distribuidora  
**Participante:** Gustavo Araújo Teixeira 

## Visão Geral

Este projeto tem como objetivo aplicar medidas de segurança utilizando serviços da Amazon Web Services (AWS), visando aumentar a proteção de recursos, dados e operações em um ambiente de nuvem.  
As implementações foram planejadas para garantir isolamento de redes, controle de acesso granular e monitoramento contínuo para prevenção e detecção de incidentes.

Foram definidas três medidas principais que, integradas, fornecem uma base sólida de segurança alinhada às boas práticas da AWS.

## Medidas Implementadas

### 1. Amazon VPC (Virtual Private Cloud) com Subnets e Regras de Segurança
**Objetivo:** Isolar e proteger ambientes de produção e teste.  
**Aplicação no projeto:**  
- Criação de uma VPC dedicada.  
- Configuração de subnets públicas e privadas.  
- Aplicação de regras de segurança restritivas para limitar o tráfego somente a instâncias e serviços autorizados.  
**Benefícios percebidos:** Maior controle de rede, redução de superfície de ataque e segregação eficiente de ambientes.

---

### 2. AWS Identity and Access Management (IAM) com Políticas de Acesso Granular
**Objetivo:** Controlar e restringir o acesso a recursos da AWS de acordo com o princípio do menor privilégio.  
**Aplicação no projeto:**  
- Criação de usuários e grupos com permissões específicas.  
- Implementação de políticas personalizadas em formato JSON.  
- Aplicação de autenticação multifator (MFA) para contas administrativas.  
**Benefícios percebidos:** Redução de riscos de acesso não autorizado e maior rastreabilidade das ações.

---

### 3. AWS CloudTrail e AWS GuardDuty para Monitoramento e Detecção de Incidentes
**Objetivo:** Rastrear atividades e identificar possíveis ameaças no ambiente AWS.  
**Aplicação no projeto:**  
- Configuração do AWS CloudTrail para registrar todas as ações executadas na conta.  
- Ativação do AWS GuardDuty para análise de tráfego e detecção de atividades anômalas.  
- Implementação de alertas para respostas rápidas a incidentes.  
**Benefícios percebidos:** Visibilidade total sobre as operações e capacidade de resposta imediata a eventos suspeitos.

---

Anexos
Manual de Configuração do Amazon VPC
Relatório de Auditoria do AWS CloudTrail
Documentação do AWS GuardDuty

Assinatura do Responsável pelo Projeto:

João Silva
