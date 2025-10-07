# 💻 Desafio: Criando uma Máquina Virtual no Microsoft Azure

## 📘 Sobre o Desafio
Este projeto faz parte do laboratório da DIO para consolidar os conhecimentos sobre **Máquinas Virtuais no Azure**.  
O objetivo foi criar, configurar e documentar uma VM, aplicando na prática os conceitos vistos durante as aulas.

---

## 🚀 Etapas Realizadas

### 1️⃣ Acesso ao Portal do Azure
- Acesse [portal.azure.com](https://portal.azure.com)
- Fiz login com minha conta Microsoft.

### 2️⃣ Criação da Máquina Virtual
- No menu lateral, cliquei em **Máquinas Virtuais → Criar → Máquina Virtual do Azure**;
- Selecionei:
  - **Nome:** `vm-desafio-jasson`
  - **Região:** West US 
  - **Imagem:** Windows 11 Pro / Windows Server 2022
  - **Tamanho:** Standard_B1s
  - **Usuário e senha** configurados conforme boas práticas.

### 3️⃣ Configurações de Rede e Segurança
- Criei um **grupo de recursos** chamado `rg-desafio-azure`;
- Configurei uma **porta RDP (3389)** para acesso remoto;
- Mantive regras padrão de firewall e rede virtual.

### 4️⃣ Testando o Acesso
- Baixei o arquivo `.rdp` e conectei via **Área de Trabalho Remota**;
- A máquina foi inicializada corretamente 🎉.

---

## 🧾 Conhecimentos Aplicados
- Criação e gerenciamento de **máquinas virtuais** no Azure;
- Configuração de **rede, segurança e credenciais**;
- Utilização do **Portal do Azure**;
- Boas práticas de **documentação técnica com Markdown e GitHub**.

---

## 🛠️ Tecnologias Utilizadas
- Microsoft Azure  
- Windows (VM)  
- Git & GitHub  
- Markdown  

---

## 👤 Autor
**Jasson Moreiro**  
[LinkedIn](https://www.linkedin.com/in/jasson-moreira-9b9b0825a/) | [GitHub](https://github.com/JassonMoreiro)
