# Microsoft-azure-essentials

### <p>Construindo Arquiteturas no Azure - Desafio</p>

<p>Nesse modulo foram abordados alguns assuntos como: pares de região, grupo de recursos e grupos de gerenciamento. 
Além da criação via portal de um grupo de serviço e uma rede virtual.</p>

<p>
  Pares de região: uma de suas funcionalidades é a replicação de recursos caso haja algum evento catastrófico.</br>
  Grupo de recursos: utilizado para centralizar o gereciamento de recursos relacionados utlizados no azure e facilitar
  a leitura do faturamento baseado em cada tipo de grupo criado.</br>
  grupos de gerenciamento: util para organizações que possuem muitas assinaturas e precisam aplicar
  políticas e a conformidade dessas assinaturas.
</p>


### <p>Configurando Recursos e Dimensionamentos em Máquinas Virtuais na Azure - Desafio</p>

<p>Tópicos abordados: tipos de computação, hospedagem de aplicativos e redes virtuais</p>

<p>
  Maquina virtual: são emulações de software de computadores físicos.</br>
  Área de trabalho virtual do azure: disponibiliza um maquina virtual no azure com todas as configurações necessárias
  para que uma pessoa desempenha suas tarefas sem a necessidade de fazer alocação de uma maquina física.</br>
  Contêiner: um ambiente leve para execução de aplicativos especializados.</br>
  Instâncias de Contêiner do Azure: usado para disponibilizar um aplicativo utilizando container (PaaS).</br>
  Aplicativos de Contêiner do Azure: usado para disponibilizar um aplicativo utilizando container (PaaS) e 
  que pode balancear a carga e escalar.</br>
  AKS: serviço de orquestração containers.</br>
  Azure function: uma tarefa de baixa complexidade pode ser executada através de eventos sem exigir 
  uma infraestrutura de servidor durante períodos inativos.</br>
  Rede Virtual do Azure (VNet): utilizado para comunicação entre os recursos do azure, com a internet e
  redes locais.</br>
  ExpressRoute: estende uma conexão local direta com os servidores do azure através de uma conexão privada.
</p>

### <p>Dominando o Armazenamento na Azure - Desafio</p>

<p>Tópicos abordados: comparação dos serviços de armazenamento do azure, cadmadas de armazenamento, opções de
redundância</p>

<p>

  contas de armazenamento: Deve ter um nome globalmente exclusivo, de 3 a 24 caracteres,
  letras minusculas e sem caracteres especiais</br>
  
  [Redundância de armazenamento]</br>
  
  LRS (armazenamento com redundância local): três cópias de um arquivo na região primária 
  [durabilidade (disponibilidade): 11 noves].</br>
  ZRS (armazenamento com redundância de zona): três cópias e cada copia estará dentro de um dos 
  datacenters que formam a região [durabilidade (disponibilidade): 12 noves].</br>
  GRS (armazenamento com redundância geográfica): modelo de copia igual ao do LRS com duplicação 
  na região original e região par [durabilidade (disponibilidade): 16 noves].</br>
  GZRS (armazenamento com redundância de zona geográfica): três zonas de disponibilidade na região 
  primária e um único datacenter na região recundária [durabilidade (disponibilidade): 16 noves].</br>
  Blob do Azure: usado para armazenar grandes quantidades de dados não estruturados como texto
  ou dados binarios.</br></br>
  
  [Camadas de acesso de armazenamento do Azure]</br>
  
  Frequente: dados acessados com frequência.</br>
  Esporádico: dados acessados com pouca frequência e armazenados por pelo menos 30 dias.</br>
  Frio: dados acessados com pouca frequência e armazenados por pelo menos 90 dias.</br>
  Arquivo morto: dados acessados raramente e armazenados por pelo menos 180 dias com
  requisitos de latência flexíveis.</br></br>
  
  Azure Data Box: Utilizado para grande movimentação de dados pois ele armazena até 80 terabyte.</br>
  AzCopy: utilizado para copiar blobs ou arquivos de ou para sua conta de armazenamento 
  [linha de comando - Windows, Linux e MacOs]. Unidirecional (do local para a nuvem)</br>
  Sincronização de arquivos no Azure: mantem os arquivos acessados com menos frequência no local, enquanto
  libera espaço (bidirecional). Funciona em Windows, Linux e MacOs</br>
  
</p>

### <p>Entendendo sobre Segurança e Identidade na Azure - Desafio</p>

<p>Tópicos abordados: serviços de diretório, métodos de autenticação, modelos de segurança</p>

<p>

  Microsoft Entra ID: é o serviço de gerenciamento de identidades e acesso baseado em nuvem do Microsoft Azure.</br>
  Autenticação: identifica a pessoa ou serviço buscando acesso a um recurso.</br>
  Autorização: determina o nível de acesso de uma pessoa ou serviço autenticado (quais recursos podem ser acessados)</br>
  Controle de acesso baseado em função (RBAC): gerenciamento de acesso granular (para cada recurso).</br>
  Confiança zero: conceder menos privilégio o possível.</br>
  Microsoft defender para nuvem: é um serviço de monitoramento que fornece proteção contra ameaças nos datacenters.
  
</p>

### <p>Otimizando Custos no Azure - Desafio</p>

<p>Tópicos abordados: calculadora de custos e preços e gereciamento de custos e marcas.</p>

<p>
  Fatores que afetam o custo: tipo de recurso, consumo, manutenção, área geográfica, tráfego de rede,
  assinatura.</br>
  Azure marketplace: permite que os clientes encontrem, experimentem, comprem e provisionem aplicativos
  e serviços de provedores de serviços.</br>
  Calculadora de custo total de propriedade (TCO): uma ferramenta para estimar a esconomia de custos
  possível ao migra para o Azure.</br>
  Marcas: fornecem metadados aos recursos do azure (não são obrigatórias e nem herdaveis). 
  Organizam recursos que consiste em um par nome-valor.	
</p>

### <p>Gerenciando Politicas em Acessos Azure - Desafio</p>

<p>Tópicos abordados: blueprints, políticas e bloqueios de recursos, portal de confiança do serviço.</p>

<p>
  
  Azure policy: ajuda a impor padrões organizacionais e a avaliar a conformidade em escala. Por exemplo: </br>
  Bloqueios de recursos: proteja os recursos do Azure de exclusão ou modificação acidental.
  Também gerencia bloqueios de assinatura, grupo de recursos ou níveis de recursos individuais
  dentro do porta do Azure.Obs.: bloqueios são herdaveis. Caso um bloqueio seja feito a
  nível de resource group tudo que esta dentro do resource group herdará esse bloqueio.</br>
  Portal de confiança do serviço: mostra quais estratégias a Microsoft segue para proteção
  de dados, validação de conteúdos de inteligência artificial, protocolos e leis que ela
  consegue manter com relação a informações dos clientes entre outras informações.</br>
  Microsoft purview: é uma família de soluções de governança, risco e conformidade de
  dados que ajuda a obter em uma única exibição unificada.
  Azure Trust Center: O Azure Trust Center é uma iniciativa da Microsoft que visa ajudar as organizações a proteger seus dados confidenciais na nuvem e a cumprir leis e        regulamentos aplicáveis. Ele oferece uma estrutura de segurança completa, com suporte de especialistas e conformidade proativa.
</p>

### <p>Ferramentas de Implantação na Azure - Desafio</p>

<p>Tópicos abordados: portal, powershell, CLI, Azure arc, Azure resource manager.</p>

<p>
  Azure arc: Ele simplifica a governança e o gerenciamento ao fornecer uma plataforma de gerenciamento 
  local consistente e de várias nuvens.</br>
  Azure resource manager: usado para criar, atualizar e excluir recursos na assinatura do Azure.</br>
  Infraestrutura como código: garanta a consistência na implantação em todo o escossistema de nuvem.</br>
  Modelos do ARM (Azure resource manager): os modelos são arquivos do tipo json. Usado para criar e 
  implantar a infraestrutura do Azure sem a necessidade de comandos.
  Bicep: usado para criar os recursos de maneira automatizada no Azure.
  
</p>

### <p>Monitoramento Inteligente com o Azure - Desafio</p>

<p>Tópicos abordados: assistente do Azure, integridade do serviço do Azure e Azure monitor.</p>

<p>
  Assistente do Azure: analisa recursos implantandos do Azure e faz recomendações com base
  nas práticas recomendadas para otimizar as implantações do Azure.</br> 
  Integridade do serviço do Azure: mantêm você informado sobre o status geral do Azure,
  status de serviços que podem afetar você e status de recurso específico que está afetando você.</br>
  Azure monitor: maximiza a disponibilidade e o desempenho de aplicativos e serviços coletando,
  analisando e tomando decisões com base na telemetria da nuvem e de ambientes locais.
  
</p>

### <p>Anotações</p>

<p>
  Network security groups (NSG):You can use an Azure network security group to filter network traffic between Azure resources in an Azure virtual network. A network security   group contains security rules that allow or deny inbound network traffic to, or outbound network traffic from, several types of Azure resources. For each rule, you can       specify source and destination, port, and protocol.</br>
  Azure Information Protection (AIP): A Proteção de Informações do Azure (AIP) fornece o serviço de criptografia, o Azure Rights Management, que é usado pelo Microsoft         Purview Information Protection. Ex.: adicionar automaticamente uma marca d’água a documentos do Microsoft Word.</br>
  Azure advisor: O Assistente é um assistente de nuvem digital que ajuda você a seguir as melhores práticas para otimizar suas implantações do Azure. Ele analisa a             configuração de seus recursos e a telemetria de uso e, em seguida, recomenda soluções que podem lhe ajudar a melhorar a relação custo-benefício, o desempenho, a              confiabilidade e a segurança de seus recursos do Azure.</br>
  Azure Key Vault: É usado para armazenar certificados no Azure, você deve usar o Azure Key Vault12, que é um serviço que protege chaves de criptografia, certificados e        segredos na nuvem.</br>
  Azure Service Health: O Azure Service Health fornece informações personalizadas sobre o status dos serviços do Azure e alertas sobre falhas ou interrupções que possam        impactar sua aplicação ou infraestrutura. Ele ajuda a monitorar o estado dos serviços e gera notificações em tempo real sobre problemas e manutenção planejada.</br>
  Azure DevTest Labs: O Azure DevTest Labs é um serviço para criar, usar e gerenciar VMs (máquinas virtuais) de IaaS (infraestrutura como serviço) facilmente em                laboratórios. Os laboratórios oferecem bases e artefatos pré-configurados para a criação de VMs. Os cenários dos DevTest Labs comuns incluem VMs para laboratórios de         desenvolvimento, teste e sala de aula ou treinamento. Os DevTest Labs promovem a eficiência, a consistência e o controle de custos mantendo todo o uso de recursos dentro     do contexto do laboratório.
</p>
