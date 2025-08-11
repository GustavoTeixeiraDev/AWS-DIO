# Relatório de Projeto – Desafio de Cloud AWS Practitioner | DIO

**Data:** 11/08/2025  
**Organização:** Abstergo Farma Distribuidora
**Participante:** Gustavo Araújo Teixeira

## Visão Geral

Este projeto faz parte do desafio proposto pela DIO para aplicação prática dos conceitos estudados durante a preparação para a certificação AWS Certified Cloud Practitioner.  
O objetivo foi explorar, configurar e aplicar serviços essenciais da AWS, com foco em compreender sua funcionalidade, integração e casos de uso no contexto de soluções em nuvem.

A execução contemplou três serviços principais, escolhidos para cobrir áreas de computação, armazenamento e segurança, simulando um cenário real de implantação.

## Serviços e Implementações

### 1. Amazon EC2 – Elastic Compute Cloud
**Objetivo:** Hospedagem de aplicação web de demonstração  
**Aplicação no projeto:**  
- Configuração de instância EC2 baseada em Linux.  
- Implantação de servidor web Apache para servir conteúdo estático e dinâmico.  
- Configuração de Security Groups para permitir acesso HTTP e SSH de forma controlada.  

**Benefícios percebidos:** Flexibilidade para escalar recursos, controle total do ambiente e custo sob demanda.

---

### 2. Amazon S3 – Simple Storage Service
**Objetivo:** Armazenamento e distribuição de arquivos de forma segura  
**Aplicação no projeto:**  
- Criação de bucket S3 para armazenamento de imagens e documentos do projeto.  
- Configuração de políticas de acesso para controle de leitura pública apenas quando necessário.  
- Testes de upload, versionamento e geração de URLs pré-assinadas para acesso temporário.  

**Benefícios percebidos:** Alta durabilidade, integração simples com outros serviços AWS e facilidade de distribuição de conteúdo.

---

### 3. AWS IAM – Identity and Access Management
**Objetivo:** Gerenciar identidades e permissões de forma centralizada  
**Aplicação no projeto:**  
- Criação de usuários com permissões específicas para administração e leitura de recursos.  
- Configuração de políticas customizadas alinhadas ao princípio de privilégio mínimo.  
- Ativação de autenticação multifator (MFA) para aumento da segurança.  

**Benefícios percebidos:** Controle granular de acesso e conformidade com boas práticas de segurança.

---
