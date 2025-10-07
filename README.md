# 💻 Desafio DIO: Criando uma Máquina Virtual no Microsoft Azure

## 📘 Sobre o Desafio
Este projeto faz parte do **Laboratório de Máquinas Virtuais no Azure**, promovido pela [DIO](https://www.dio.me/).  
O objetivo é **colocar em prática** os conceitos estudados nas aulas, **criando e configurando uma máquina virtual** no portal do Azure e documentando todo o processo técnico.

---

## 🎯 Objetivos de Aprendizagem
- Aplicar os conceitos de **criação e gerenciamento de VMs** no Azure;
- **Documentar** de forma clara e estruturada os processos realizados;
- Utilizar o **GitHub** para compartilhar a documentação técnica e fortalecer o portfólio profissional.

---

## 🚀 Etapas Realizadas

### 🟦 1. Acesso ao Portal do Azure
- Acesse o [Portal do Azure](https://portal.azure.com);
- Realizei login com minha conta Microsoft e verifiquei os recursos disponíveis.

### 🟩 2. Criação do Grupo de Recursos
- Criei um grupo de recursos chamado **`rg-desafio-azure`** para organizar os componentes do laboratório.

### 🟨 3. Criação da Máquina Virtual
- No painel lateral, selecionei:  
  **Máquinas Virtuais → Criar → Máquina Virtual do Azure**
- Parâmetros utilizados:
  - **Nome da VM:** `vm-jasson-lab`
  - **Região:** (East US)
  - **Imagem:** Windows 11 Pro
  - **Tamanho:** Standard_B1s (baixo custo)
  - **Usuário administrador:** `jassonadmin`
  - **Autenticação:** senha
- Configurei as portas de entrada necessárias (RDP 3389) para acesso remoto.

### 🟧 4. Configuração de Rede e Segurança
- Criei uma **rede virtual** padrão;
- Configurei um **endereço IP público dinâmico**;
- Mantive as configurações básicas de segurança padrão do Azure.

### 🟥 5. Validação e Implantação
- Revisei todas as configurações e cliquei em **Revisar + Criar**;
- Após a validação, o recurso foi **implantado com sucesso** 🎉.

### 🟪 6. Testando o Acesso via RDP
- Baixei o arquivo `.rdp` gerado pelo Azure;
- Conectei usando o **usuário e senha configurados**;
- A máquina virtual inicializou normalmente, confirmando o sucesso da criação.

---

## 🧠 Conceitos Aplicados
- Criação e gerenciamento de **máquinas virtuais no Azure**;  
- Configuração de **rede, IP e regras de segurança**;  
- Acesso remoto via **RDP**;  
- Organização de recursos no **Portal do Azure**;  
- Documentação técnica utilizando **Markdown** e **GitHub**.

---

## 🧾 Tecnologias Utilizadas
| Tecnologia | Função |
|-------------|--------|
| **Microsoft Azure** | Criação e gerenciamento da VM |
| **Windows 11 Pro** | Sistema operacional da máquina virtual |
| **GitHub** | Publicação da documentação |
| **Markdown** | Formatação do README.md |

---

## 🧑‍💻 Autor
**Jasson Moreiro**  
📍 Estudante de Engenharia da Computação  
🚀 Em formação na DIO | Microsoft Azure & .NET  
🔗 [LinkedIn](https://www.linkedin.com/in/jasson-moreira-9b9b0825a/) | [GitHub](https://github.com/JassonMoreiro)

---

## 🏁 Conclusão
Este desafio foi uma excelente oportunidade para reforçar o aprendizado sobre **infraestrutura em nuvem**, **gerenciamento de recursos no Azure** e **boas práticas de documentação técnica**.  
A criação da máquina virtual foi concluída com sucesso, validando todo o processo estudado durante o módulo.
