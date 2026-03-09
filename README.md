# Simulação de Ataque de Brute Force: Medusa & Kali Linux

> **⚠️ AVISO LEGAL:** Este projeto foi realizado em um ambiente de laboratório controlado (Metasploitable 2) para fins estritamente educacionais e de segurança ética. Nunca execute essas ferramentas em redes ou sistemas sem autorização explícita.

## 📌 Descrição do Desafio
Este projeto demonstra as técnicas de **Ethical Hacking** utilizadas para identificar credenciais vulneráveis em redes corporativas. Através do protocolo SMB, foi simulado um ataque de força bruta paralelo para compreender como configurações fracas podem ser exploradas por cibercriminosos.

## 🛠️ Ferramentas e Ambiente
* **Sistema Operacional:** Kali Linux
* **Alvo (Target):** Metasploitable 2 (Máquina virtual vulnerável)
* **Ferramenta de Ataque:** Medusa (Brute-force paralelo)
* **Protocolo Alvo:** SMB (Server Message Block)
* **Validação:** smbclient

## 🚀 Fluxo de Trabalho Técnico
1. **Preparação de Wordlists:** Criação de dicionários customizados de usuários e senhas.
2. **Configuração do Medusa:** Parametrização para ataques paralelos visando eficiência.
3. **Execução do Ataque:** Teste sistemático de combinações de credenciais contra o serviço SMB.
4. **Pós-Exploração:** Validação do acesso obtido e análise dos logs de sucesso.

## 🛡️ Medidas de Mitigação (Visão Defensiva)
Além da prática de ataque, o projeto destaca como prevenir tais invasões:
* Implementação de **MFA (Múltiplo Fator de Autenticação)**.
* Políticas de senhas complexas e rotação periódica.
* Bloqueio de conta após X tentativas falhas (Account Lockout).
* Monitoramento e alertas de tráfego SMB suspeito.

---

## 👩‍💻 Autora
Feito com 💛 por Bruna Guimarães






 
