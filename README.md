# Criando Máquinas Virtuais na Azure

Este laboratório tem como objetivo consolidar os conhecimentos em máquinas virtuais na Azure, aplicando os conceitos de criação, configuração e conexão.

## 📖 Descrição do Desafio

Este projeto faz parte do Bootcamp da DIO e tem como objetivo consolidar os conhecimentos sobre **Máquinas Virtuais no Azure**. Durante o desafio, criei e configurei uma VM para praticar os conceitos aprendidos.

---

## 🎯 Objetivos de Aprendizagem

- Aplicar os conceitos aprendidos em um ambiente prático;
- Documentar os processos técnicos de forma clara e estruturada;
- Utilizar o GitHub como ferramenta de documentação técnica.

---

## 🛠️ Passo a Passo da Criação da VM

### 1. Acessando o Portal do Azure

- Acessei o [Portal do Azure](https://portal.azure.com).
- Naveguei até **Máquinas Virtuais** > **Criar**.

### 2. Configurações da VM

- **Imagem:** Ubuntu Server 24.04 LTS
- **Grupo de Recursos:** ProjetoDio
- **Região:** (US) West US 3
- **Tamanho da VM:** Standard D2s v3 (2 vCPUs, 8 GiB de memória)
- **Usuário/Admin:** azureuser
- **Autenticação:** Chave SSH

![Configurações da VM](imagens/image_67a056.png)

### 3. Implantação

- A criação foi iniciada no dia `21/08/2025` às `20:41`.
- O processo levou alguns minutos até ser concluído com sucesso.

![Andamento da Implantação](imagens/image_71ac21.png)

![Implantação Concluída](imagens/image_71abe2.png)

### 4. Conexão à VM

- Após a implantação, a conexão foi estabelecida via SSH utilizando o PowerShell no Windows e a chave de autenticação privada.

```bash
ssh -i "C:\Users\joao\Downloads\BootCampDio_key.pem" azureuser@20.14.77.14

5. Detalhes da Máquina Virtual

Detalhe	Valor
Nome	BootCampDio
Sistema Operacional	Ubuntu Server 24.04 LTS
Geração	Gen2
vCPUs	2
Memória RAM	8 GiB
IP Público	20.14.77.14
Endereço IP Privado	10.0.0.4
Rede Virtual/Sub-rede	BootCampDio-vnet/default
Grupo de Recursos	ProjetoDio

🚀 Tecnologias Utilizadas
Microsoft Azure

Linux (Ubuntu Server 24.04 LTS)

Git & GitHub
