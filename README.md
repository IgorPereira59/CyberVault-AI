# CyberVault AI — Protótipo CyberGuardian

Protótipo funcional de interface desenvolvido para o Projeto Integrador do curso de **Análise e Desenvolvimento de Sistemas (UNIPÊ — 2026)**.

## 🔗 Demonstração Online
Acesse o protótipo navegável (8 telas): **[https://igorpereira59.github.io/CyberVault-AI/](https://igorpereira59.github.io/CyberVault-AI/)**

## 🛡️ Arquitetura Demonstrada (3 Camadas + Governança)
- **Camada 1 — Triagem Determinística:** Classificação de telemetria (`SRV-DB-CLIENTES`) com saída estruturada em JSON validada por Regex.
- **Camada 2 — Contenção SOAR (`iptables`):** Geração automatizada de regras de isolamento com preservação explícita da porta administrativa **SSH TCP 2222** (`10.250.0.0/24`).
- **Camada 3 — Parecer Forense & LGPD:** Relatório técnico em 5 seções alinhado ao **Art. 48 da Lei nº 13.709/2018 (LGPD)**, Modo Co-Piloto (*Human-in-the-Loop*) e Trilha de Auditoria **SHA-256**.

## ⚠️ Aviso de Escopo Acadêmico
Este repositório contém exclusivamente a camada de interface e simulação visual para fins acadêmicos e testes de usabilidade. Todos os logs, endereços IP e eventos apresentados são dados simulados em ambiente isolado.

## 👥 Equipe
- Arthur Evangelista
- Guilherme Moreira
- Igor Pereira Canindé de Brito
