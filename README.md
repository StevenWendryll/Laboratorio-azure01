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
- Nome da VM: `VmTeste1`  
- Imagem: Windows Server 2022 Datacenter  
- Usuário administrador criado  

📸 **Evidência:**  

![](assets/img1.png)
![](assets/img2.png)
![](assets/img3.png)

---

### 🌐 3. Configuração de Rede

- Portas liberadas:
  - RDP (3389)
  - HTTP (80)

📸 **Evidência:**  

![](assets/img4.png)

---

### ⚙️ 4. Configurações Adicionais

- Habilitado desligamento automático  
- Fuso horário configurado  

---

### ✅ 5. Validação e Criação

- Validação dos recursos  
- Criação da VM iniciada  

![](assets/img5.png)
![](assets/img6.png)
![](assets/img7.png)
![](assets/img8.png)

---

### 🔗 6. Conexão via RDP

- Download do arquivo `.rdp`  
- Conexão com a VM usando credenciais criadas  

---

### 🌍 7. Instalação do IIS

Comando executado no PowerShell:

powershell
```Install-WindowsFeature -name Web-Server -IncludeManagementTools```

📸 **Evidência:**  

![](assets/img10.png)

---

### ✅ 5. Validação do ISS Windows Server

- Na visão geral da VM, passe o mouse sobre o endereço IP para mostrar Copiar para área de transferência. Copie o endereço IP e cole-o em uma guia do navegador. A página de boas-vinda do IIS padrão será aberta.

📸 **Evidência:**  

![](assets/img11.png)

