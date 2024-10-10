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
