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

