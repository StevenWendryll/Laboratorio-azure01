# ☁️ Deploy de Máquina Virtual Windows no Azure

> 📚 Atividade prática realizada no Portal do Azure  
> 🎯 Objetivo: Criar e configurar uma VM Windows Server 2022 e validar acesso via RDP + IIS  

---

## 🚀 Objetivo da Atividade

Realizar o provisionamento de uma **Máquina Virtual Windows** no Microsoft Azure, incluindo:

- Criação da VM via Portal  
- Liberação de portas (RDP e HTTP)  
- Acesso remoto via RDP  
- Instalação do servidor web IIS  
- Validação via navegador  

---

## 🛠️ Tecnologias Utilizadas

- Microsoft Azure  
- Windows Server 2022 Datacenter  
- RDP (Remote Desktop Protocol)  
- IIS (Internet Information Services)  
- PowerShell  

---

## 📋 Etapas Realizadas

### 🔐 1. Acesso ao Portal Azure

- Login no portal do Azure  

📸 **Evidência:**

![](assets/img12.png)

---

### 🖥️ 2. Criação da Máquina Virtual

- Serviço selecionado: Máquinas Virtuais  
- Nome da VM: `myVM`  
- Imagem: Windows Server 2022 Datacenter  
- Usuário administrador criado  

📸 **Evidência:**  
> *(Inserir print da tela de criação da VM aqui)*

---

### 🌐 3. Configuração de Rede

- Portas liberadas:
  - RDP (3389)
  - HTTP (80)

📸 **Evidência:**  
> *(Inserir print das regras de porta de entrada aqui)*

---

### ⚙️ 4. Configurações Adicionais

- Habilitado desligamento automático  
- Fuso horário configurado  

📸 **Evidência:**  
> *(Inserir print da aba de gerenciamento aqui)*

---

### ✅ 5. Validação e Criação

- Validação dos recursos  
- Criação da VM iniciada  

📸 **Evidência:**  
> *(Inserir print da validação e criação aqui)*

---

### 🔗 6. Conexão via RDP

- Download do arquivo `.rdp`  
- Conexão com a VM usando credenciais criadas  

📸 **Evidência:**  
> *(Inserir print da conexão RDP aqui)*

---

### 🌍 7. Instalação do IIS

Comando executado no PowerShell:

```powershell
Install-WindowsFeature -name Web-Server -IncludeManagementTools
