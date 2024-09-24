# resumo-do-lab6

## Dominando o Armazenamento na Azure

Aqui estão os principais pontos do aprendizado:

Criação de Conta de Armazenamento

Contas de Armazenamento: São fundamentais para armazenar uma variedade de dados no Azure, desde arquivos simples até bancos de dados complexos.

Nome Exclusivo: Cada conta de armazenamento precisa de um nome único, que será utilizado para acesso e gerenciamento dos dados.

Desempenho: As contas podem ser configuradas com desempenho Standard ou Premium, dependendo das necessidades de velocidade e acesso.

Redundância: Existem várias opções de redundância para garantir a disponibilidade e durabilidade dos dados:

LRS (Locally Redundant Storage): Dados são replicados dentro de um único data center.

GRS (Geo-Redundant Storage): Dados são replicados em um data center secundário em uma região diferente.

ZRS (Zone-Redundant Storage): Dados são replicados em diferentes zonas dentro da mesma região.

GZRS (Geo-Zone-Redundant Storage): Combina a replicação zonal e geográfica para maior resiliência.

## Armazenamento de Blobs
Níveis de Acesso: Os dados podem ser armazenados em diferentes níveis de acesso, como quente (frequentemente acessado) ou frio (raramente acessado), para otimizar custos.
Roteamento de Redes e Proteção de Dados

Roteamento de Redes: Configuração de regras de rede para controlar o acesso às contas de armazenamento.

Proteção de Dados: Inclui a capacidade de recuperação de dados, ajudando a garantir a integridade e a disponibilidade dos mesmos.
Criação de Containers e Compartilhamentos

Containers e Compartilhamentos: Dentro de uma conta de armazenamento, você pode criar containers para armazenar blobs, compartilhamentos de arquivos via SMB (porta 445), filas e tabelas.

Permissões e Tokens: Tokens de acesso compartilhado (SAS) podem ser gerados para controlar o acesso aos recursos de armazenamento. As permissões podem ser configuradas conforme necessário para garantir a segurança dos dados.

## Migrações para o Azure
Criação de Projetos de Migração: Planejamento e execução de migrações de servidores, bancos de dados e aplicativos web para o Azure.

Data Box: Soluções como Data Box Disk, Data Box, Data Box Heavy e Import/Export Job facilitam a transferência física de grandes volumes de dados para o Azure.

## Ferramentas de Migração e Gerenciamento

AzCopy: Uma ferramenta de linha de comando prática e funcional disponível para Windows, Linux e macOS, que facilita a cópia de dados para e do Azure.

Gerenciador de Armazenamento do Microsoft Azure: Interface que permite o gerenciamento completo das contas de armazenamento, facilitando a visualização, configuração e monitoramento dos recursos.

## Adicional sobre Contas de Armazenamento no Azure

Gerenciamento de Custo: Monitorar e otimizar os custos associados ao armazenamento no Azure, utilizando ferramentas como o Azure Cost Management.

Segurança Avançada: Implementar medidas avançadas de segurança, como criptografia de dados em trânsito e em repouso, e políticas de acesso baseadas em identidade (IAM).

Automação: Utilizar scripts e ferramentas de automação para simplificar a gestão de contas de armazenamento e processos de migração, garantindo consistência e eficiência.

Monitoramento e Logs: Configurar monitoramento e logs detalhados para rastrear o desempenho e acesso aos dados, ajudando na identificação de problemas e auditoria de segurança.
