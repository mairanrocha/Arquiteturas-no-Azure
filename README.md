# 🌐 Arquiteturas no Microsoft Azure

Este repositório contém um resumo do que aprendi sobre **como construir arquiteturas na nuvem utilizando o Microsoft Azure**, com foco nos principais componentes como **Resource Group**, **Virtual Network (VNet)** e boas práticas de organização de recursos.

---

## 🧱 O que é uma Arquitetura no Azure?

Uma arquitetura no Azure é a forma de organizar e conectar recursos da nuvem (como bancos de dados, aplicações e redes) para resolver um problema ou construir uma aplicação.

---

## 📌 Componentes Essenciais

### ✅ Resource Group (Grupo de Recursos)
- **Definição:** Um contêiner lógico que agrupa recursos relacionados.
- **Uso:** Organizar por ambiente (Ex: Dev, Prod).
- **Boas práticas:** Aplicar **tags** e manter recursos do mesmo ciclo de vida juntos.

---

### 🌐 Virtual Network (VNet)
- **Definição:** Uma rede privada no Azure.
- **Utilidade:** Permite que os recursos se comuniquem de forma segura.
- **Elementos:**
  - **Subnets:** Dividem a rede em zonas internas.
  - **NSG (Network Security Group):** Define regras de acesso (entrada/saída).
  - **Peering:** Conecta duas VNets diferentes.
  - **VPN Gateway:** Comunicação entre rede local e Azure.

---

### 🔧 Outros Componentes Importantes
- **App Service:** Hospeda aplicações Web sem configurar VMs.
- **Azure SQL:** Banco de dados relacional na nuvem.
- **Key Vault:** Armazena senhas, tokens e certificados com segurança.
- **Azure Storage:** Armazenamento de arquivos, blobs, filas etc.
- **Azure Monitor / Application Insights:** Monitoramento e métricas.

---

## 🛠️ Como Construir uma Arquitetura no Azure

1. **Planejamento da Solução**
   - Quais serviços sua aplicação precisa?

2. **Criação de um Resource Group**
   - Definir nome e região.

3. **Criação da VNet com Subnets**
   - Isolar os componentes (ex: Web, Banco).

4. **Implantação dos Recursos**
   - App Service, Azure SQL, Storage etc.

5. **Configuração de Segurança**
   - NSGs, Key Vault, firewalls.

6. **Monitoramento e Custos**
   - Ativar logs, alertas e acompanhar gastos.

---

## 🖼️ Diagrama da Arquitetura

> Diagrama simples representando um App Service se comunicando com um banco Azure SQL, ambos dentro de uma VNet, com segurança através do Key Vault.

![Azure Architecture Diagram]( https://oaidalleapiprodscus.blob.core.windows.net/private/org-cynrxz6Z7MFDHkHjcsaPT2ON/user-KmWZgyZNcruYeGMCJDyxp0xb/img-kcdKnAxTivFv9KYB0RTNFSKk.png?st=2025-05-11T15%3A30%3A00Z&se=2025-05-11T17%3A30%3A00Z&sp=r&sv=2021-08-06&sr=b&sig=WtWyRQ3M0%2BcXyfXbR5kLTqJV5iESYH9UnvH5dCR5rcA%3D)

---

## ✅ Conclusão

Compreender os componentes essenciais do Azure e como conectá-los é o primeiro passo para construir aplicações escaláveis, seguras e organizadas na nuvem. O uso de Resource Groups, VNet e serviços gerenciados facilita o controle e a manutenção da infraestrutura.

---
