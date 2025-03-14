# Especificações do Projeto



Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto

## Personas

Perfil 1: João Elias Castrovic

![João](https://github.com/user-attachments/assets/fd85ccac-c8eb-4ad1-89a1-651ab578840b)


Perfil 2: Mariana Velasco Antunes

![Mariana Velasco Antunes](https://github.com/user-attachments/assets/2a9501f6-ad3d-46f5-9095-c1a0409a98c7)


Perfil 3: Ricardo Mourani Figueiredo

![Ricardo Mourani Figueiredo](https://github.com/user-attachments/assets/75d5bb0f-7b4c-4f2a-9a2b-01dae72a2885)


Perfil 4: Sofia Alencar Takeda

![Sofia Alencar Takeda](https://github.com/user-attachments/assets/5f836f62-7ff4-40c0-ab99-7e0a915baf7a)



Perfil 5: Lucas Bevenides Monteiro

![Lucas Bevenides Monteiro](https://github.com/user-attachments/assets/97bd21e9-c662-4bf1-86f8-d411ffdc0e25)



Perfil 6: Fernanda Alves Oliveira

![Fernanda Alves Oliveira](https://github.com/user-attachments/assets/763e6ab7-79a8-4d1a-9854-92f1b6a72b39)



## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Usuário do sistema  | Buscar filmes por nome ou gênero  | Encontrar reviews e avaliações         |
|Usuário do sistema  | Avaliar filmes                     | Compartilhar minha opinião com a comunidade |
|Administrador       | Gerenciar as permissões de usuários  | Garantir que cada pessoa tenha acesso apenas ás funcionalidades e informações relevantes ao seu papel |
|Usuário do sistema  | Filtrar filmes por avaliação  | Encontrar opções de bons filmes  |
|Usuário do sistema  | Salvar opções de filmes em uma lista  | Poder assistir em outro dia sem precisar ficar sempre procurando  |
|Usuário do sistema  | Seguir outros usuários  | Ver as avaliações de pessoas que confia e gosta do mesmo gênero de filmes |
|Usuário do sistema  | Ter acesso a lista de filmes mais bem avaliados do momento  | Encontrar mais opções de filmes para assistir |


## Modelagem do Processo de Negócio 

### Análise da Situação Atual

Apresente aqui os problemas existentes que viabilizam sua proposta. Apresente o modelo do sistema como ele funciona hoje. Caso sua proposta seja inovadora e não existam processos claramente definidos, apresente como as tarefas que o seu sistema pretende implementar são executadas atualmente, mesmo que não se utilize tecnologia computacional. 

### Descrição Geral da Proposta

Apresente aqui uma descrição da sua proposta abordando seus limites e suas ligações com as estratégias e objetivos do negócio. Apresente aqui as oportunidades de melhorias.

### Processo 1 – NOME DO PROCESSO

Apresente aqui o nome e as oportunidades de melhorias para o processo 1. Em seguida, apresente o modelo do processo 1, descrito no padrão BPMN. 

![Processo 1](img/02-bpmn-proc1.png)

### Processo 2 – NOME DO PROCESSO

Apresente aqui o nome e as oportunidades de melhorias para o processo 2. Em seguida, apresente o modelo do processo 2, descrito no padrão BPMN.

![Processo 2](img/02-bpmn-proc2.png)

## Indicadores de Desempenho

Apresente aqui os principais indicadores de desempenho e algumas metas para o processo. Atenção: as informações necessárias para gerar os indicadores devem estar contempladas no diagrama de classe. Colocar no mínimo 5 indicadores. 

Usar o seguinte modelo: 

![Indicadores de Desempenho](img/02-indic-desemp.png)
Obs.: todas as informações para gerar os indicadores devem estar no diagrama de classe a ser apresentado a posteriori. 

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto. Para determinar a prioridade de requisitos, aplicar uma técnica de priorização de requisitos e detalhar como a técnica foi aplicada.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| A aplicação deve permitir que o usuário crie e edite um perfil próprio e único(nome, foto de perfil e biografia).  | ALTA | 
|RF-002| A aplicação deve permitir que o usuário faça o login em seu perfil.   | ALTA |
|RF-003| O perfil do usuário deve conter as avaliações e comentários feitos por ele.   | BAIXA |
|RF-004| A aplicação deve permitir que o usuário busque títulos por nome, gênero e/ou avaliação.   | ALTA |
|RF-005| A aplicação deve permitir que o usuário veja reviews e a avaliação dos títulos dadas pelos outros usuários.   | MÉDIA |
|RF-006| A aplicação deve permitir que o usuário avalie um título com uma nota de 1 a 10.   | ALTA |
|RF-007| A aplicação deve prover ao usuário informações gerais sobre o título (sinopse, duração, classificação indicativa, elenco, média das avaliações).   | BAIXA |
|RF-008| A aplicação deve permitir que o usuário salve títulos em listas personalizadas.   | BAIXA |
|RF-009| A aplicação deve permitir que o usuário faça um comentário sobre um título.   | ALTA |
|RF-010| A aplicação deve prover ao usuário uma lista com recomendações de títulos baseados em sua preferência e histórico.   | BAIXA |
|RF-011| A aplicação deve prover ao usuário uma lista com os títulos mais bem avaliados.   | MÉDIA |
|RF-012| A aplicação deve prover ao usuário uma lista com os lançamento de novos títulos.   | MÉDIA |
|RF-013| A aplicação deve permitir que o usuário siga outros usuários.   | BAIXA |
|RF-014| A aplicação deve prover uma interface administrativa para a moderação do sistema.   | MÉDIA |
|RF-015| A aplicação deve prover um jeito rápido de denunciar material inadequado.   | MÉDIA |
|RF-016| A aplicação deve permitir que o usuário curta e comente o review de outro usuário.   | MÉDIA |


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| A aplicação deve ser responsivo para rodar em um dispositivos móvel | MÉDIA | 
|RNF-002| A aplicação deve processar requisições do usuário em no máximo 3s |  BAIXA | 
|RNF-003| A aplicação deve exigir senha de no mínimo 8 caracteres, com letras maiúsculas, minúsculas, números e caracteres especiais| MÉDIA |
|RNF-004| A aplicação deve permitir criação de resenhas apenas a usuários selecionados | MÉDIA |
|RNF-005| A aplicação deve ter suporte ao sistema operacional Android | MÉDIA |

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Usuário comum não poderá criar resenhas        |


itos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)

## Diagrama de Casos de Uso

![Diagrama de casos de uso2 (1)](https://github.com/user-attachments/assets/e0d0d1fb-e496-4ee8-af86-c0958bb8b7a4)



# Matriz de Rastreabilidade

A matriz de rastreabilidade é uma ferramenta usada para facilitar a visualização dos relacionamento entre requisitos e outros artefatos ou objetos, permitindo a rastreabilidade entre os requisitos e os objetivos de negócio. 

A matriz deve contemplar todos os elementos relevantes que fazem parte do sistema, conforme a figura meramente ilustrativa apresentada a seguir.

| ID   |RF-01|RF-02|RF-03|RF-04|RF-05|RF-06|RF-07|RF-08|RF-09|RF-10|RF-11|RF-12|RF-13|RF-14|RF-15|RF-16|RNF-01|RNF-02|RNF-03|RNF-04|RNF-05|
|------|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|------|------|------|------|------|
|RF-01 |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |      |      |      |      |      |      
|RF-02 |  x  |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |      |      |      |      |      |      
|RF-03 |  x  |  x  |     |     |     |     |     |     |     |     |     |     |     |     |     |     |      |      |      |      |      |
|RF-04 |     |     |     |     |  x  |     |     |     |     |     |     |     |     |     |     |     |      |      |      |      |      |
|RF-05 |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |      |      |      |      |      |
|RF-06 |     |     |  x  |  x  |     |     |     |     |     |     |     |     |     |     |     |     |      |      |      |      |      |
|RF-07 |     |     |     |  x  |     |  x  |     |     |     |     |     |     |     |     |     |     |      |      |      |      |      |
|RF-08 |     |  x  |     |     |     |     |     |     |     |     |     |     |     |     |     |     |      |      |      |      |      |
|RF-09 |     |  x  |     |  x  |     |     |     |     |     |     |     |     |     |     |     |     |      |      |      |      |      |
|RF-10 |  x  |  x  |     |  x  |     |  x  |     |     |     |     |     |     |     |     |     |     |      |      |      |      |      |
|RF-11 |     |     |     |     |  x  |  x  |     |     |     |     |     |     |     |     |     |     |      |      |      |      |      |
|RF-12 |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |      |      |      |      |      |
|RF-13 |  x  |  x  |     |  x  |     |  x  |     |     |     |     |     |     |     |     |     |     |      |      |      |      |      |
|RF-14 |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |      |      |      |      |      |
|RF-15 |     |     |     |     |     |     |     |     |     |     |     |     |     |  x  |     |     |      |      |      |      |      |
|RF-16 |  x  |  x  |     |     |  x  |     |     |     |     |     |     |     |     |     |     |     |      |      |      |      |      |         
|RNF-01|     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |      |      |      |      |      |    
|RNF-02|     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |      |      |      |      |      |
|RNF-03|  x  |  x  |     |     |     |     |     |     |     |     |     |     |     |     |     |     |      |      |      |      |      |
|RNF-04|     |  x  |     |     |     |     |     |     |     |     |     |     |     |     |     |     |      |      |      |      |      |
|RNF-05|     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |      |      |      |      |      |


# Gerenciamento de Projeto

De acordo com o PMBoK v6 as dez áreas que constituem os pilares para gerenciar projetos, e que caracterizam a multidisciplinaridade envolvida, são: Integração, Escopo, Cronograma (Tempo), Custos, Qualidade, Recursos, Comunicações, Riscos, Aquisições, Partes Interessadas. Para desenvolver projetos um profissional deve se preocupar em gerenciar todas essas dez áreas. Elas se complementam e se relacionam, de tal forma que não se deve apenas examinar uma área de forma estanque. É preciso considerar, por exemplo, que as áreas de Escopo, Cronograma e Custos estão muito relacionadas. Assim, se eu amplio o escopo de um projeto eu posso afetar seu cronograma e seus custos.

## Gerenciamento de Tempo

Com diagramas bem organizados que permitem gerenciar o tempo nos projetos, o gerente de projetos agenda e coordena tarefas dentro de um projeto para estimar o tempo necessário de conclusão.

![Diagrama de rede simplificado notação francesa (método francês)](img/02-diagrama-rede-simplificado.png)

O gráfico de Gantt ou diagrama de Gantt também é uma ferramenta visual utilizada para controlar e gerenciar o cronograma de atividades de um projeto. Com ele, é possível listar tudo que precisa ser feito para colocar o projeto em prática, dividir em atividades e estimar o tempo necessário para executá-las.

![Gráfico de Gantt](img/02-grafico-gantt.png)

## Gerenciamento de Equipe

O gerenciamento adequado de tarefas contribuirá para que o projeto alcance altos níveis de produtividade. Por isso, é fundamental que ocorra a gestão de tarefas e de pessoas, de modo que os times envolvidos no projeto possam ser facilmente gerenciados. 

![Simple Project Timeline](img/02-project-timeline.png)

## Gestão de Orçamento

O processo de determinar o orçamento do projeto é uma tarefa que depende, além dos produtos (saídas) dos processos anteriores do gerenciamento de custos, também de produtos oferecidos por outros processos de gerenciamento, como o escopo e o tempo.

![Orçamento](img/02-orcamento.png)
