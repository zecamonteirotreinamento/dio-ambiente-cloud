# 🚀 Criando uma Máquina Virtual no Azure

Ao criar uma máquina virtual no **Azure**, é possível escolher modelos pré-definidos com algumas configurações, o que otimiza a criação. Essas pré-definições podem ser alteradas futuramente.

## 🛠️ Configuração Manual
Caso opte por configurar a máquina virtual manualmente, será necessário definir os seguintes itens:

- **Assinatura**
- **Grupo de recursos**
- **Nome da máquina virtual**
- **Região**
- **Opções de disponibilidade**
- **Zona de disponibilidade**
- **Tipo de segurança**
- **Imagem e arquitetura**
- **Outras configurações essenciais**

## 📊 Configuração de Escala
A configuração de escala é fundamental durante a criação das máquinas. As opções necessárias incluem:

- **Contagem e limite de instâncias**
- **Escalonamento e redução horizontal**
- **Duração da consulta**

## 📏 Escolha do Tamanho da VM
O **Portal do Azure** apresenta uma tabela com os tamanhos das VMs e uma descrição sobre a usabilidade recomendada para cada tamanho. Esse é um dos itens necessários para selecionar ao criar uma VM.

## 💾 Configuração do Disco
Uma boa prática é selecionar a opção **"Excluir com VM"**, pois ao excluir uma VM, o uso do disco continua sendo cobrado. Esses discos que permanecem ativos são chamados de **"discos órfãos"**.

## 🌐 Configuração de Rede
Na criação da VM, é necessário **selecionar ou criar uma rede virtual** para seu uso. Assim como no disco, na configuração de rede é recomendável selecionar a opção **"Excluir o IP público e a NIC quando a VM for excluída"**, para evitar cobranças desnecessárias.

## 📈 Monitoramento e Backup
Durante a configuração da VM, é possível habilitar opções como:

- **Backup**
- **Horário de desligamento**
- **Configuração de alertas**

## 🔧 Extensões e Tags
Por fim, é possível **adicionar extensões e tags** à VM. Após todas as configurações, o Azure apresenta o **custo estimado**, que é calculado por **hora de uso**.

---
📝 **Dica:** Sempre revise as configurações antes de finalizar a criação para evitar cobranças indesejadas! 💡
