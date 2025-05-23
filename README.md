# resumo-do-lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO.

O que é Cloud?

Cloud Computing (Computação em Nuvem)
A computação em nuvem é um modelo de entrega de serviços de tecnologia em que recursos como armazenamento, processamento de dados, software, redes e muito mais são fornecidos pela internet, em vez de ficarem em servidores e data centers próprios. Com a nuvem, empresas e usuários podem acessar e utilizar esses recursos sob demanda, pagando apenas pelo que utilizam. Isso elimina a necessidade de investir em infraestrutura física cara e difícil de manter. A computação em nuvem permite escala, flexibilidade e agilidade, além de possibilitar o acesso a esses recursos de qualquer lugar e a qualquer momento. Os principais tipos de nuvem incluem a pública, a privada e a híbrida, cada uma com suas características e aplicações específicas.

_____________________________________________________________________________________________________________________________________________________________________________

Infraestrutura

O que é Infraestrutura?

Infraestrutura refere-se ao conjunto de recursos físicos ou virtuais necessários para o funcionamento de sistemas de TI. Inclui servidores, redes, armazenamento, e outras tecnologias essenciais para suportar aplicativos e operações de uma organização. Modelos de infraestrutura podem variar entre on-premise, cloud, ou híbrida, dependendo das  necessidades e estratégias da empresa.

  On-Premise (Local)
  
  Definição: Refere-se a uma infraestrutura de TI que é instalada, gerida e mantida localmente nas instalações físicas da empresa, geralmente com servidores próprios e        controle completo sobre o hardware e o software.
  
O modelo on-premise refere-se à infraestrutura física e aos sistemas de TI que são instalados, mantidos e gerenciados dentro das instalações da própria empresa, ou seja,   em um data center local. Nesse modelo, todas as operações e dados ficam sob o controle total da empresa, que é responsável pela compra, manutenção e operação de servidores, software, rede e outros recursos. Apesar de oferecer maior controle e segurança (pois os dados ficam dentro da empresa), o modelo on-premise exige investimentos altos em equipamentos, espaço físico e mão de obra especializada para manutenção.

Exemplos:

  Servidores físicos e armazenamento local.
  Rede interna com controle total sobre os dados.
  Administração e manutenção interna.
  
Vantagens: Maior controle e personalização.
Desvantagens: Custos altos de manutenção e necessidade de espaço físico.

Modelo Cloud (Nuvem)

  Definição: A infraestrutura em nuvem é baseada em servidores remotos fornecidos por provedores de nuvem como AWS, Google Cloud ou Azure. Os recursos são escaláveis e        pagam-  se conforme o uso, permitindo maior flexibilidade.
  
O modelo cloud (ou modelo de nuvem) é uma infraestrutura baseada na internet, onde a empresa ou o usuário utiliza recursos de TI de um provedor externo. Em vez de ter servidores, bancos de dados e outros sistemas dentro de suas instalações, as empresas alugam esses serviços de fornecedores de nuvem, como Amazon Web Services (AWS), Microsoft Azure ou Google Cloud. Isso permite a escalabilidade, ou seja, é possível aumentar ou diminuir a capacidade dos serviços de acordo com a necessidade, sem a necessidade de investir em infraestrutura própria. Além disso, o modelo de nuvem permite reduzir custos, melhorar a agilidade e acessar serviços avançados que seriam difíceis de implementar localmente.

Exemplos:

  Amazon Web Services (AWS), Microsoft Azure, Google Cloud.
  Armazenamento e processamento de dados na nuvem.

Vantagens: Custos mais baixos, escalabilidade e flexibilidade.
Desvantagens: Dependência da conexão com a internet.

Modelo Hybrid (Híbrido)

  Definição: A infraestrutura híbrida combina recursos on-premises e em nuvem, permitindo que as empresas aproveitem as vantagens de ambos os modelos. Parte dos recursos são   mantidos localmente, enquanto outros são escalados ou movidos para a nuvem, de acordo com a necessidade.

O modelo híbrido combina os benefícios dos modelos on-premise e cloud. Nesse caso, uma empresa mantém parte de sua infraestrutura local, enquanto usa serviços de nuvem para outras operações, criando uma combinação de recursos internos e externos. Por exemplo, uma empresa pode manter dados sensíveis em servidores próprios (on-premise) e, ao mesmo tempo, usar a nuvem para hospedar aplicativos ou serviços que exigem mais escalabilidade. O modelo híbrido oferece flexibilidade, permitindo que as empresas escolham o que é melhor em cada situação. No entanto, esse modelo também exige gestão mais complexa, pois é necessário integrar e monitorar tanto a infraestrutura local quanto os recursos na nuvem.

Exemplos:

  Serviços críticos hospedados localmente, enquanto a carga de trabalho escalável é alocada na nuvem.
  Conexões seguras entre servidores locais e provedores de nuvem.

Vantagens: Flexibilidade de escolher o que fica onde, de acordo com as necessidades.
Desvantagens: Complexidade na gestão.

_____________________________________________________________________________________________________________________________________________________________________________

Serviços

O que são os Modelos de Serviço em Nuvem?

Definição: Modelos de serviço em nuvem definem o nível de controle que a empresa tem sobre a infraestrutura e os serviços fornecidos pelo provedor de nuvem. Eles ajudam a escolher a solução mais adequada às necessidades do negócio, podendo envolver diferentes níveis de abstração e responsabilidades.

  Golden Rules: Regras universais para escolher e implementar os modelos de serviço com base nas necessidades de controle, custo e escalabilidade.
  Exemplo: "Escolha o modelo de serviço adequado conforme o nível de controle necessário."

  House Rules: Regras específicas para cada organização com base em sua arquitetura e objetivos. 
  Exemplo: "Para aplicativos mais complexos, prefira PaaS para abstração e gerenciamento facilitado."

IaaS (Infrastructure as a Service)

Definição: IaaS oferece infraestrutura de TI básica como serviço, fornecendo recursos como servidores virtuais, armazenamento, redes e outros componentes essenciais de TI, com base em uma cobrança por uso.

Exemplos:

  Amazon EC2, Google Compute Engine, Microsoft Azure VMs.
  Armazenamento de dados com serviços como Amazon S3 ou Google Cloud Storage.

Vantagens: Controle total sobre a infraestrutura, escalabilidade e flexibilidade.
Desvantagens: Requer gestão de servidores e configurações, mais responsabilidade do que PaaS ou SaaS.

PaaS (Platform as a Service)

Definição: PaaS oferece uma plataforma de desenvolvimento completa na nuvem, permitindo que os desenvolvedores construam, testem e implementem aplicativos sem se preocupar com a infraestrutura subjacente.

Exemplos:

  Google App Engine, Microsoft Azure App Services, AWS Elastic Beanstalk.
  Ferramentas de banco de dados como Amazon RDS ou Google Cloud SQL.
  
Vantagens: Simplificação no desenvolvimento, abstração da infraestrutura e foco no desenvolvimento do aplicativo.
Desvantagens: Menos controle sobre a infraestrutura, limitações na personalização de configurações.

SaaS (Software as a Service)

Definição: SaaS entrega software e aplicações completas pela nuvem, sendo acessadas via internet, sem necessidade de instalação ou manutenção local. O provedor cuida de tudo, desde a infraestrutura até as atualizações do software.

Exemplos:

  Google Workspace, Microsoft Office 365, Salesforce.
  Ferramentas de comunicação como Slack ou Zoom.

Vantagens: Fácil implementação, sem necessidade de gestão de infraestrutura, pagamento por uso.
Desvantagens: Dependência de internet, menor controle sobre o software e dados.

BaaS (Backend as a Service)

Definição: BaaS fornece soluções de backend prontas para uso em aplicativos móveis ou web, com a gestão de bancos de dados, autenticação de usuários, notificações push e outros recursos comuns.

Exemplos:

  Firebase, AWS Amplify, Backendless.

Vantagens: Rapidez no desenvolvimento, gerenciamento simplificado de backend.
Desvantagens: Dependência do provedor, limitações na personalização.

FaaS (Function as a Service)

Definição: FaaS é uma forma de computação em nuvem onde você executa funções de código específicas, sem precisar gerenciar servidores. Também conhecida como "serverless", permite que o código seja executado em resposta a eventos, com cobrança baseada na execução real.

Exemplos:

  AWS Lambda, Azure Functions, Google Cloud Functions.
  
Vantagens: Escalabilidade automática, pagamento por execução, redução da sobrecarga de gerenciamento de infraestrutura.
Desvantagens: Limitações em tempo de execução e complexidade na manutenção de funções pequenas e event-driven.

DBaaS (Database as a Service)

Definição: DBaaS oferece bancos de dados gerenciados como serviço, permitindo aos usuários acessar e gerenciar bancos de dados na nuvem sem se preocupar com a infraestrutura subjacente.

Exemplos:

  Amazon RDS, Azure SQL Database, Google Cloud SQL.
  
Vantagens: Facilidade de escalabilidade, gerenciamento simplificado de backups e atualizações.
Desvantagens: Menor controle sobre a configuração do banco de dados e personalização.

_____________________________________________________________________________________________________________________________________________________________________________

Regiões

  O Azure oferece mais regiões globais do que qualquer outro provedor de nuvem, com mais de 60 regiões representando mais de 140 países
  As regiões são compostas de um ou mais datacenters muito próximos.
  Eles fornecem flexibilidade e escala para reduzir a latência do cliente.
  As regiões preservam a residência dos dados com uma oferta abrangente de conformidade.

Zonas de disponibilidade

  Fornece proteção contra tempo de inatividade devido a falha do datacenter.
  Separe fisicamente os datacenters dentro da mesma região.
  Cada datacenter é equipado com alimentação, resfriamento e rede independentes. 
  Conectadas por meio de redes privadas de fibra óptica.

Pares de regiões

  No mínimo 300 milhas de separação entre pares de regiões.
  Replicação automática para alguns serviços.
  Recuperação de região priorizada em caso de interrupção.
  As atualizações são distribuídas sequencialmente para minimizar o tempo de inatividade.

Regiões soberanas do Azure (serviços Governamentais dos EUA)

  Atende às necessidades de segurança e conformidade das agências federais, governos estaduais e locais dos EUA e seus provedores de soluções.
  
Azure Governamental:

  Instância separada do Azure.
  Fisicamente isolada de implantações que não sejam do governo dos EUA.
  Acessível somente a pessoal verificado e autorizado.

Regiões soberanas do Azure (Azure China)

A Microsoft é o primeiro provedor estrangeiro de serviços de nuvem pública da China, em conformidade com as regulamentações governamentais.

Recursos do Azure China:

  Instância fisicamente separada dos serviços de nuvem do Azure operados pela 21Vianet.
  Todos os dados permanecem dentro da China para garantir a conformidade.

Recursos do Azure

Os recursos do Azure são componentes como armazenamento, máquinas virtuais e redes que estão disponíveis para criar soluções de nuvem.

Exemplos:

  Máquinas Virtuais, Conyas de armazenamento, Redes Virtuais, Serviços de     Aplicativos, Bancos de dados SQL e Funções.

Grupos de recursos

Um grupo de recursos é um contêiner que você usa para gerenciar e agregar recursos em uma única unidade. 

  Os recursos podem existir em apenas um grupo de recursos.
  Os recursos podem existir em diferentes regiões. 
  Os recursos podem ser movidos para diferentes grupos de recursos. 
  Os aplicativos podem utilizar vários grupos de recursos.

Assinaturas do Azure

Uma assinatura do Azure fornece a você acesso autenticado e autorizado às contas do Azure.

  Limite de cobrança: gere relatórios de cobrança e faturas separados para cada assinatura.
  Limite do controle de acesso: gerenciar e controlar o acesso aos recursos que os usuários podem provisionar com assinaturas específicas.

Grupos de gerenciamento

  Os grupos de gerenciamento podem incluir várias assinaturas do Azure.
  As assinaturas herdam as condições aplicadas ao grupo de gerenciamento.
  É possível oferecer suporte a 10.000 grupos de gerenciamento em um único diretório.
  Uma árvore de grupos de gerenciamento pode oferecer suporte a até seis níveis de profundidade.

Serviços de computação do Azure

A Computação do Azure é um serviço sob demanda que fornece recursos de computação, como discos, processadores, memória, rede e sistemas operacionais.

Exemplos:

  Virtual (Virtuais), Aplicativo(Serviços), Contêiner(Instâncias), Serviços de Kubernetes do Azure(AKS) e Área de Trabalho(Virtual do Azure)

Máquinas virtuais do Azure

As máquinas virtuais do Azure (VMs) são emulações de software de computadores físicos. 

  Inclui processador virtual, memória, armazenamento e rede. 
  Oferta de IaaS que oferece personalização e controle total. 

_____________________________________________________________________________________________________________________________________________________________________________

Máquinas virtuais do Azure

As máquinas virtuais do Azure (VMs) são emulações de software de computadores físicos. 

Inclui processador virtual, memória, armazenamento e rede. 
Oferta de IaaS que oferece personalização e controle total. 

Serviços de contêineres do Azure

Os contêineres do Azure fornecem um ambiente leve e virtualizado que não exige o gerenciamento do sistema operacional e pode responder a alterações sob demanda.

  Instâncias de Contêiner do Azure: uma oferta de PaaS que executa um contêiner ou pod de contêineres no Azure.
  Aplicativos de Contêiner do Azure: uma oferta de PaaS, como instâncias de contêineres, que pode balancear a carga e escalar.
  Serviço de Kubernetes do Azure: um serviço de orquestração para contêineres com arquiteturas distribuídas e grandes volumes de contêineres. 

Azure Functions

Azure Functions: uma oferta de PaaS que dá suporte a operações de computação sem servidor. O código baseado em eventos é executado quando chamado, sem exigir uma infraestrutura de servidor durante períodos inativos.

Serviços de Aplicativo do Azure

Os Serviços de Aplicativos do Azure consistem em uma plataforma totalmente gerenciada para criar, implantar e dimensionar aplicativos Web e APIs rapidamente. 

  Trabalha com .NET, .NET Core, Node.js, Java, Python ou php.
  Oferta de PaaS com requisitos de nível corporativo de desempenho, segurança e conformidade.

Serviços de rede do Azure

A Rede Virtual do Azure (VNet) permite que os recursos do Azure se comuniquem uns com os outros, com a Internet e com as redes locais.

  Pontos de extremidade públicos, acessíveis de qualquer lugar na Internet.
  Pontos de extremidade privados, acessíveis somente de dentro da sua rede.
  As sub-redes virtuais segmentam sua rede para atender às suas necessidades.
  O emparelhamento de rede conecta suas redes privadas diretamente.

DNS do Azure

  Confiabilidade e desempenho aproveitando uma rede global de servidores de nome DNS usando a rede Anycast.
  A segurança do DNS do Azure baseia-se no gerenciador de recursos do Azure, habilitando o controle de acesso baseado em função e o monitoramento e o registro em log.
  Facilidade de uso para gerenciar seus recursos externos e do Azure com um único serviço DNS.
  As redes virtuais personalizáveis permitem que você use nomes de domínio privados e totalmente personalizados em suas redes virtuais privadas.
  Os registros de alias dão suporte a conjuntos de registros de alias para apontar diretamente para um recurso do Azure.

_____________________________________________________________________________________________________________________________________________________________________________

Armazenamento: domínio de objetivo

Descrever os benefícios e o uso

  Comparar os serviços de armazenamento do Azure.
  Descrever as camadas de armazenamento.
  Descrever as opções de redundância.
  Descrever as opções de conta de armazenamento e os tipos de armazenamento.
  Identificar opções para mover arquivos, incluindo o AzCopy, o Gerenciador de Armazenamento do Azure e a Sincronização de Arquivos do Azure.
  Descrever as opções de migração, incluindo as Migrações para Azure e o Azure Data Box.

Contas de armazenamento

  Deve ter um globalmente nome exclusivo.
  Fornecer acesso à Internet em todo o mundo.
  Determinar os serviços de armazenamento e as opções de redundância.

Redundância de armazenamento
___________________________________________________________________________________________________________________________________________________________________
|              Configuração de redundância               |                Implantação               |                     Durabilidade                            |
|       LRS (armazenamento com redundância local)        | Datacenter individual na região primária |                          11 noves                           |
|      ZRS (armazenamento com redundância de zona)       | Três zonas de disponibilidade na região primária |                       12 noves                      |
|     GRZ (armazenamento com redundância geográfica)     |Datacenter único no primário e região secundária |                         16 noves                     |
| GZRS (armazenamento com redundância de zona geográfica | Três zonas de disponibilidade na região primária e um único datacenter na região secundária | 16 noves | 
|_________________________________________________________________________________________________________________________________________________________________|

Serviços de armazenamento do Azure

  Blob do Azure: otimizado para o armazenamento de quantidades massivas de dados não estruturados, como texto ou dados binários.
  Disco do Azure: fornece discos para máquinas virtuais, aplicativos e outros serviços acessarem e utilizarem.
  Fila do Azure: serviço de armazenamento de mensagens que fornece armazenamento e recuperação para grandes quantidades de mensagens, cada uma com até 64 KB.
  Arquivos do Azure: configura um compartilhamento de arquivos de rede altamente disponível que pode ser utilizado usando o protocolo Bloco de Mensagens do Servidor.
  Tabelas do Azure: fornece uma opção de chave/atributo para o armazenamento de dados estruturados não relacionais com um design sem esquema.

Pontos de extremidade públicos do serviço de armazenamento
___________________________________________________________________________________
| Serviço de armazenamento | Ponto de extremidade público                          |
|  Armazenamento de Blobs  | https://<storage-account-name>.blob.core.windows.net  |
| Data Lake Storage Gen 2  | https://<storage-account-name>.dfs.core windows.net   |
|    Arquivos do Azure     | https://<storage-account-name>file.core windows.net   |
|  Armazenamento de filas  | https://<storage-account-name>.queue.core.windowsnet  |
| Armazenamento de Tabelas | https://<storage-account-name>.table.core windows.net |
|__________________________________________________________________________________|

Camadas de acesso de armazenamento do Azure

  Frequente: Otimizada para armazenamento de dados acessados com frequência
  Esporádico:  Otimizada para armazenamento de dados acessados com pouca frequência e armazenados por pelo menos 30 dias.
  Frio: Otimizado para o armazenamento de dados acessados com pouca frequência e armazenados por pelo menos 90 dias.
  Arquivo Morto: Otimizado para o armazenamento de dados acessados raramente e armazenados por pelo menos 180 dias com requisitos de latência flexíveis.

Azure Data Box

  Armazenar até 80 terabytes de dados.
  Mova os backups de recuperação de desastre para o Azure.
  Proteja seus dados em uma caixa robusta durante o trânsito.
  Migre dados do Azure para conformidade ou necessidades regulatórias.
  Migre dados para o Azure de locais remotos com conectividade limitada ou sem conectividade.
