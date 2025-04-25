# Guia Prático: Criando uma Máquina Virtual no Azure ☁️💻

## 🚀 Objetivo
Documentar o processo de criação e configuração de uma máquina virtual utilizando a plataforma Microsoft Azure.

## 📋 Pré-requisitos
- Conta Microsoft
- Conta ativa no [Microsoft Azure](https://azure.microsoft.com/)
- Navegador atualizado

## 🛠️ Passo a Passo

### 1. Criando a Conta no Azure
- Acesse [https://azure.microsoft.com](https://azure.microsoft.com/)
- Clique em "Comece gratuitamente"
- Siga as instruções e valide seus dados

### 2. Criando a Máquina Virtual
- Acesse o portal: [https://portal.azure.com](https://portal.azure.com)
- Vá em **"Máquinas Virtuais"** > **"Criar"**
- Escolha:
  - Sistema Operacional (Ubuntu, Windows)
  - Tamanho da máquina (ex: B1s - gratuito)
  - Usuário e senha
- Configure as portas:
  - SSH (22) ou RDP (3389)

### 3. Acessando a VM
- Para Ubuntu: use terminal/Putty
  ```bash
  ssh usuario@ip-da-maquina
