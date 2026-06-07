# azure-lab-maquina-virtua

# Desafio DIO - Criando uma Máquina Virtual no Microsoft Azure

## Objetivo

Este laboratório teve como objetivo consolidar os conhecimentos sobre a criação e gerenciamento de Máquinas Virtuais (VMs) utilizando o Microsoft Azure.

Durante a atividade foi possível compreender os principais conceitos de computação em nuvem, além de realizar a criação e configuração de uma máquina virtual através do Portal Azure.

---

## Conceitos Aprendidos

### O que é uma Máquina Virtual?

Uma Máquina Virtual (VM) é um recurso de computação disponibilizado em nuvem que permite executar sistemas operacionais e aplicações sem a necessidade de possuir um servidor físico dedicado.

As VMs fornecem:

* Escalabilidade
* Flexibilidade
* Alta disponibilidade
* Redução de custos com infraestrutura física

---

## Etapas Realizadas

### 1. Acesso ao Portal Azure

Primeiramente foi realizado o acesso ao Portal Microsoft Azure utilizando uma conta Microsoft.

Portal:
https://portal.azure.com

---

### 2. Criação do Grupo de Recursos

Foi criado um Resource Group para organizar todos os recursos utilizados durante o laboratório.

Exemplo:

Nome: rg-lab-vm

O Grupo de Recursos facilita a administração e exclusão dos recursos criados.

---

### 3. Criação da Máquina Virtual

Durante a criação da VM foram configurados os seguintes parâmetros:

* Assinatura Azure
* Grupo de Recursos
* Nome da Máquina Virtual
* Região
* Sistema Operacional Windows Server
* Usuário Administrador
* Senha de Acesso

Também foram definidas as opções de armazenamento e rede.

---

### 4. Configuração de Rede

Foi criada automaticamente uma Virtual Network (VNet) para comunicação da máquina virtual.

Conceitos estudados:

* Rede Virtual (VNet)
* Endereço IP Público
* Regras de Firewall
* Grupos de Segurança de Rede (NSG)

---

### 5. Conexão com a Máquina Virtual

Após a implantação, foi possível conectar-se à VM utilizando o protocolo RDP (Remote Desktop Protocol).

Passos:

1. Obter o endereço IP público da VM.
2. Abrir o aplicativo Área de Trabalho Remota.
3. Informar IP, usuário e senha cadastrados.
4. Acessar o ambiente Windows Server.

---

## Benefícios das Máquinas Virtuais no Azure

* Provisionamento rápido
* Escalabilidade sob demanda
* Alta disponibilidade
* Segurança integrada
* Integração com outros serviços Azure
* Pagamento conforme utilização

---

## Conceitos Relacionados à AZ-900

Durante o laboratório foi possível identificar conceitos importantes para a certificação AZ-900:

* Computação em Nuvem
* IaaS (Infrastructure as a Service)
* Regiões Azure
* Grupos de Recursos
* Redes Virtuais
* Escalabilidade
* Alta Disponibilidade
* Responsabilidade Compartilhada

---

## Conclusão

Este laboratório permitiu compreender na prática como criar e administrar uma Máquina Virtual no Microsoft Azure, além de reforçar conceitos fundamentais de computação em nuvem.

A experiência demonstrou como os serviços Azure simplificam o provisionamento de infraestrutura, oferecendo escalabilidade, disponibilidade e segurança para ambientes corporativos.
