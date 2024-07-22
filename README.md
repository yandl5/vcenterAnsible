# Automação do Ciclo de Vida de Máquinas Virtuais com Ansible e AWX

Este repositório contém uma série de playbooks Ansible desenvolvidos para gerenciar o ciclo de vida de máquinas virtuais em um ambiente VMware. Este projeto foi desenvolvido como parte do Trabalho de Conclusão de Curso (TCC) em TI (Redes e Infraestrutura) pela UFRN, em parceria com a JFRN.

## Resumo do Projeto

Este trabalho é dedicado à automação abrangente do ciclo de vida das máquinas virtuais no contexto corporativo. Através das ferramentas de automação Ansible e AWX, o objetivo é aprimorar a gestão eficiente das máquinas virtuais. A sinergia entre Ansible e AWX visa otimizar a eficiência, padronização e controle da infraestrutura virtual. O trabalho enfatiza a importância da automação na satisfação das necessidades organizacionais, mostrando sua capacidade de simplificar operações e lidar com os desafios decorrentes da constante evolução no cenário de TI contemporâneo.

## Playbooks

Este repositório inclui os seguintes playbooks:

- **add_hd.yml**: Adiciona um disco rígido a uma máquina virtual.
- **create_from_template.yml**: Cria uma nova máquina virtual a partir de um template existente.
- **create_snapshot.yml**: Cria um snapshot de uma máquina virtual.
- **create_vm.yml**: Cria uma nova máquina virtual.
- **del_vm.yml**: Deleta uma máquina virtual.
- **delete_hd_vm.yml**: Remove um disco rígido de uma máquina virtual.
- **delete_snapshot.yml**: Deleta um snapshot de uma máquina virtual.
- **expand_disk.yml**: Expande o disco rígido de uma máquina virtual.
- **get_uuid_vm.yml**: Obtém o UUID de uma máquina virtual.
- **poweroff.yml**: Desliga uma máquina virtual.
- **poweron.yml**: Liga uma máquina virtual.
- **update.yml**: Atualiza as configurações de uma máquina virtual.

## Requisitos

Para utilizar esses playbooks, você precisará dos seguintes requisitos:

- Ansible instalado na sua máquina de gerenciamento.
- Acesso ao ambiente VMware onde as máquinas virtuais estão hospedadas.
- Credenciais de acesso válidas para o ambiente VMware.

## Uso

1. Clone este repositório para a sua máquina de gerenciamento.
   ```sh
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
