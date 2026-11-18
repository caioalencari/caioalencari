# Olá, eu sou o Caio 👋

**Atuário e desenvolvedor** em Fortaleza (CE). Automatizo processos com Python, dados e IA generativa.

- 🎓 Bacharel em Ciências Atuariais (UFC, 2026) · Pós-graduação em Automação Robótica — RPA e Agentes Inteligentes (Unifor, em andamento)
- 🏛️ 4 anos em uma serventia extrajudicial (registro de imóveis), atuando com gestão de pessoas, indicadores, auditoria interna (ABNT NBR 15906) e no comitê de inteligência artificial
- 🤖 Construo sistemas internos de ponta a ponta, com apoio de agentes de IA (Claude, Gemini) e integrações via API
- 📊 TCC sobre PGBL e VGBL: simulação financeira de 5 a 30 anos e matriz multicritério para o investidor conservador

## 🛠️ Stack

`Python` `Django` `FastAPI` `PostgreSQL` `Docker` `Nginx` `Git` `Google Apps Script` `Power BI` `Excel` `APIs de LLMs (Anthropic, Gemini)` `RPA`

## 🚀 Produtos que desenvolvi

> Os dois primeiros são sistemas internos em produção. O código é privado; abaixo está o que eles fazem e como foram construídos.

### Hub de Treinamentos
Plataforma de capacitação e certificação corporativa (LMS) em uso por **120 colaboradores** para gerenciar treinamentos, avaliações e certificados.
- Django 5.1, PostgreSQL 15, Docker, API REST com JWT e documentação Swagger/OpenAPI
- Certificados em PDF com QR Code de validação e importação de treinamentos por planilha .xlsx
- Módulo de conformidade com controle de evidências, usado em auditoria nacional de qualidade
- Mais de 1.000 testes automatizados, HTTPS (TLS 1.2/1.3) via Nginx e plano de implantação com rollback
- Desenvolvido em fases a partir de um PRD, com apoio de agentes de IA

### Central de Gestão de Pessoas
Sistema de gestão de pessoas com foco no módulo de férias conforme a CLT, seguindo as diretrizes de segurança do Provimento CNJ nº 213.
- Regras da CLT implementadas: vedação de início antes do repouso semanal (art. 134, §3º), fracionamento em até 3 períodos (art. 134, §1º), abono pecuniário (art. 143) e alerta de férias em dobro (art. 137)
- Alerta de desfalque quando colaboradores do mesmo setor pedem férias no mesmo período, e escala mensal consolidada
- Aprovação em duas instâncias (gestor e RH) e trilha de auditoria imutável com usuário, data/hora e IP
- Django 5.1, PostgreSQL 15, Docker, Nginx com HTTPS e HSTS, contêineres sem privilégio de root

### [Verbatim](https://github.com/caioalencari/verbatim) — transcrição de documentos com IA
Interface de OCR de alta acurácia para documentos jurídicos e cartorários usando a API do Gemini.
- FastAPI, conversão de PDF em imagens e histórico de transcrições em SQLite

### [BaixAI](https://github.com/caioalencari/baixai)
Programa para Windows que baixa vídeos e áudios em MP3 ou MP4. Python · licença MIT.

## 📫 Contato

[LinkedIn](https://www.linkedin.com/in/caioalencari) · caioalencarf@gmail.com
