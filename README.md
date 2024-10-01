# resumo-do-lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO

Microsoft Azure - Localizando Serviços por Categoria:
Aprendi a como localizar os serviços da azure e que eles estão organizados por categorias.

Criando máquinas Virtuais na Azure:
Ao criar máquinas virtuais na AZURE, precisamos saber qual a disponibilidade que os recursos deverão cumprir. Com base nisso o SLA será maior ou menor. Se maior, o custo também deverá ser maior.


Configurando uma instância de Banco de Dados na Azure:
Quando criamos uma instância ou recurso, inclusive de banco de dados, é necessário uma série de informações como por exemplo, identificar o servidor, o SLA. No final é possível verificar uma previsão do custo que aquela instância vai gerar.

Construindo Arquiteturas no Azure:
Foi possível explorar a infraestrutura global da Azure;
Identificar como é feita a replicação dos dados de uma region para outra;
Criar um grupo de recursos, identificado pela assinatura e região;
Saber como controlar acessos com o IAM;

Configurando Recursos e Dimensionamentos em Máquinas Virtuais na Azure:
Quando vamos criar uma máquina Virtual na azure, podemos também criar algumas máquinas com configurações pré-definidas.
é possível escolher também máquinas que já possuam aplicações pré-instaladas. 
Aprendi como realizar a configuração de escala e definir o modo de dimensionamento.

Dominando o Armazenamento na Azure:
Storage account deve ter um nome único no mundo - 3 a 24 caracteres, não aceita maiúsculas nem caracteres especiais.
Desempenho: No modelo standard você paga conforme o uso. Já o Premium, você já inicia pagando (modelo recomendado para quem precisa de baixa latência).
Referente à redudância: LRS (Armazenamento com redundância local), GRS (Armazenamento com redundância geográfica), ZRS(Armazenamento com redundância de zona), GZRS (Armazenamento com redundância de zona geográfica).
Migrações para a azure. Um exemplo é o Data Box.
Data Box Disk: 35 TB --> 10 dias sem custo extra
Data Box: 80 TB --> 10 dias sem custo extra
Data Box Heavy: 800 TB --> 20 dias sem custo extra

Import/Export Job: 1 TB

AzCopy está disponível para Windows, Linux e MacOs.
Precisa ter criado um storage account (Conta de armazenamento)
O AzCopy é um modelo mais leve e unilateral.

Gerenciador de armazenamento do Microsoft Azure
está disponível para Windows, Linux e MacOs.

Entendendo sobre segurança e Identidade na Azure:
Microsoft Entra Id: Os usuários do onprimisse são replicados para a nuvem, mas o contrário não ocorre.
RBAC --> permissionamento para executar determinadas ações.
O microsoft defender te dá opções de monitoramento, inclusive em ambientes onde existem mais de uma solução de nuvem sendo utilizada.


Otimizando Custos no Azure:
Neste módulo entendi como é feita a previsibilidade dos custos da azure a partir da calculadora e a comparação dos custos no meu ambiente onPrimesse em relação à nuvem. Também entendi a importância da utilização das tags (marcas) nos recursos ou grupos de recursos da cloud. é possível por exemplo, à partir delas, separar os recursos por centro de custo.

Gerenciando Políticas em acessos azure:
Portal de confiança da Azure --> Saber como a microsoft protege os dados do cliente.
Policies: Regras aplicadas aos resources groups e recursos.
Locks: Pode ser a nível de resourse group ou recurso. Quando aplicado ao resource group, os recursos abaixo dele respeitam esse bloqueio. Quando o recurso é movido para outro resource group ele deixa de herdar o bloqueio.
Microsoft Purview: Acesso ao portal de governança, segurança dos dados e compliance.

Ferramentas de Implantação na Azure:
Os modos de implantação podem ser via portal, cloud shell, via linha de comando - precisa ter um storage account
associado à conta. É possível por exemplo importar e exportar arquivos. É possível escolher o powershell ou o bash,
dependendo da sua preferência. Existe um interpretador destes comandos. No export template eu consigo visualizar o
JSON que tem os comandos para criação de um recurso. Sobre o Bicep, a quantidade de linhas de comandos é mais enxuta
se comparado ao modelo ARM. Sobre o ARQ, ela é uma ferramenta de gerenciamento multi-cloud, permite a inclusão de
infraestruturas existentes. Posso administrar recursos que não sejam do azure. Não existe concorrente direto em outras
clouds para este tipo de recurso.

Monitoramento Inteligente com o Azure:
Assistente do azure: faz recomendações, analisa recursos implantados. É cloud native.
Integridade do serviço do azure é uma coleção de serviços que mantêm você informado sobre o status geral do azure,
status de serviços que afetam você e status de recurso específico que está afetando você.
Status do azure: visão global da integridade de todos os serviços da azure em todas as regiões da azure.
Focada nos serviços e regiões que você está usando.
Resource Health: Fornece informações sobre os recursos de nuvem individuais.
Azure Monitor: maximiza disponibilidade e desempenho. Usa telemetria.
