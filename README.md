# labDIO-vmAzure

# Criando uma Máquina Virtual no Azure

## Resumo
Este projeto documenta o processo de criação e configuração de uma máquina virtual no Microsoft Azure como parte do desafio da DIO.

## Passo a Passo

### 1. Criar Conta no Azure
- Acessar o Portal Azure e criar a conta (disponível também em assinatura gratuita).

### 2. Criar a Máquina Virtual
- Busque por "Máquinas Virtuais"
- Clique em "Criar" e selecione "Máquina virtual"
- Configure:
  - Selecione a Assinatura, o grupo de recurso e crie um nome para esta VM
  - Selecione uma região e o tipo de disponibilidade necessária (com ou sem redundância)
  - Sistema Operacional: Linux ou Windows
  - Tamanho: B1s (grátis)
  - Crie um Usuário e senha para acessar a VM
  - Selecione as opções de conexão RDP e HTTP (80)
  - Siga com a revisão e criação da VM

### 3. Acessar a VM
- Linux: via SSH
- Windows: via RDP
  - Faça o download do arquivo RDP e siga com o preechimento do usuário e senha para abrir o sistema na VM
- Validar se está rodando corretamente

## Conclusão
Esse laboratório reforçou o uso prático da criação de VMs e gestão via portal Azure.
