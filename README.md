# Laboratório Azure AZ-900

## Conceitos Abordados
- Regiões Azure: Visão geral da infraestrutura global da Microsoft, com mais de 60 regiões.
- Brasil (Brasil South/Southeast):
Brasil South (São Paulo): Disponível para todos os clientes.
Brasil Southeast (Rio de Janeiro): Reservado para cenários de disaster recovery e clientes com requisitos de LGPD (dados não podem sair do Brasil).
Replicação padrão do Brasil South é para os EUA, mas há discussões para futuramente permitir replicação interna (Brasil South → Brasil Southeast).

## Tour pelo Data Center Virtual
- Microsoft Global Infrastructure Explorer: Mostra data centers, cabos submarinos e zonas de disponibilidade.
- Tour Virtual: Visita interativa a um data center da Microsoft, incluindo salas de servidores, centro de operações e sustentabilidade.

## Prática no Portal Azure
- Criando um Grupo de Recursos:
Nome: AZ900-Lab
Região: Leste dos EUA (para demonstração).
Tags (Marcações): Úteis para organização e gestão de custos.

- Rede Virtual (VNet):
Criada no Brasil South para exemplificar recursos em diferentes regiões dentro do mesmo grupo.
Visualização no Visualizador de Recursos mostra a relação entre os recursos.

- Monitoramento e Segurança:
Log de Atividades: Rastreia criação/exclusão de recursos e usuários envolvidos.
Controle de Acesso (IAM): Gerenciamento de permissões (princípio do menor privilégio).
Bloqueios: Evita exclusões acidentais (ex.: recurso travado em "somente leitura").
