# Desafio-Final-Ethical-Hacking-Capture-The-Flag
🛡️ Pentest – Ambiente Simulado TechCorp Solutions

Este repositório contém o relatório e as evidências referentes ao teste de intrusão (pentest) realizado no ambiente simulado da TechCorp Solutions, como parte de um treinamento autorizado em cibersegurança.

O objetivo deste projeto é demonstrar, na prática, como falhas comuns em sistemas web e serviços expostos podem ser descobertas, exploradas e documentadas de forma profissional.



📌 Sobre o Ambiente

Empresa (simulada): TechCorp Solutions

Finalidade: Treinamento prático em cibersegurança

Tipo de Teste: Black Box

Ferramentas utilizadas:

Kali Linux

curl

Nmap

Gobuster / Dirbuster

FTP client

Testes manuais de SQL Injection

Testes de XSS



🚩 Flags Encontradas

Durante o pentest foram identificadas 8 vulnerabilidades, cada uma representada por uma flag disponibilizada no ambiente simulado. Todas elas foram analisadas, exploradas e documentadas:

Flag	Descrição	Tipo de Vulnerabilidade
FLAG{b4sic_s0urc3_c0d3_1nsp3ct1i0n}	Código-fonte exposto	Informação sensível
FLAG{r0b0ts_txt_l34k4g3}	Vazamento via robots.txt	Configuração insegura
FLAG{ftp_4nonym0us_4cc3ss}	FTP com acesso anonymous	Serviço mal configurado
FLAG{d4t4b4s3_cr3d3nt14ls_3xp0s3d}	Credenciais expostas	Arquivo sensível público
FLAG{sql_1nj3ct10n_m4st3r}	SQL Injection	Falha crítica
FLAG{h1dd3n_d4t4_1n_d4t4b4s3}	Dados ocultos no DB	Armazenamento inseguro
FLAG{xss_r3fl3ct3d_vuln3r4b1l1ty}	XSS Refletido	Falta de validação
FLAG{s3cr3t_p4n3l_d1sc0v3ry}	Painel secreto descoberto	Endpoint exposto
📄 Relatório Técnico

O relatório completo do pentest está incluído neste repositório em um arquivo específico.
Ele contém:

Escopo

Metodologia

Passo a passo de descoberta das vulnerabilidades

Evidências

Impactos técnicos e reais

Recomendações detalhadas

Conclusão geral


🎯 Objetivo do Projeto

Este repositório foi criado com propósito educacional para:

Demonstrar um fluxo realista de pentest

Documentar vulnerabilidades em formato profissional

Ajudar estudantes e iniciantes a entender como funciona uma análise completa

Servir como portfólio técnico na área de cibersegurança

🧰 Ferramentas Utilizadas

Nmap → Varredura de portas e enumeração de serviços

Gobuster/Dirbuster → Descoberta de diretórios

curl → Requisições manuais e coleta de dados

FTP Client → Acesso ao serviço vulnerável

Browser DevTools → Inspeção de código

SQL Injection Manual → Bypass de login e dump de dados

Payloads XSS → Exploração client-side


📚 Aprendizados

Ao concluir este projeto foi possível reforçar:

Identificação de falhas de configuração

Análise de serviços expostos

Execução de SQL Injection e XSS na prática

Leitura de evidências e análise de impacto

Boas práticas de documentação em segurança

Cadeias de ataque e pivotamento entre vulnerabilidades


📌 Aviso Importante

Este projeto foi realizado em um ambiente completamente autorizado e simulado.
Nunca execute testes de intrusão em sistemas reais sem permissão formal.

pdf com o relatório logo acima
