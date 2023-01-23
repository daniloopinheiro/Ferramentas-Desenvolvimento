# Ferramentas de Desenvolvimento Interessantes

## [GitLiveName](https://marketplace.visualstudio.com/items?itemName=TeamHub.teamhub)

![image](https://user-images.githubusercontent.com/64677271/214046935-cfb74903-2ee6-4076-ad10-99516704f250.png)

🤕 Dor: falta de ferramentas de comunicação projetadas especificamente para desenvolvedores

💡 Solução: GitLive — amplie seu IDE com superpoderes colaborativos em tempo real

Supondo que sua equipe use o Git, o GitLive é um aprimoramento óbvio da funcionalidade integrada do Git do seu IDE. Uma vez instalado, ele adiciona uma exibição de equipe mostrando todo o trabalho em andamento para cada colaborador do seu repositório Git. Qualquer ramificação não obsoleta à frente de master/main é considerada um trabalho em andamento e você pode inspecionar as diferenças dos arquivos alterados, bem como visualizar o problema associado ou a solicitação pull.

Mas meu recurso favorito é provavelmente a detecção automática de conflito de mesclagem. A diferença entre suas alterações locais e o trabalho em andamento de seus colegas de equipe é mostrada para seu arquivo aberto atual na calha de seu editor. Ele mostra o tipo de alteração (adição, exclusão, modificação ou conflito) e você pode inspecioná-lo para ver o diff, de qual ramificação é e até mesmo escolher em seu arquivo local.

O GitLive pode ser muito útil para equipes maiores e especialmente útil para projetos de código aberto ou interno, pois esses recursos funcionam até mesmo em forks. O que também é legal é que, como os dados vêm direto do Git, não há necessidade de entrada manual para mantê-los atualizados.

## [CódigoVer Mapas](https://www.codesee.io/)

![image](https://user-images.githubusercontent.com/64677271/214047064-c513dc63-b4ab-4067-89ec-49449f6d2b80.png)

🤕 Dificuldade: Bases de código densas e sofisticadas e falta de compreensão compartilhada de como todo o código e funcionalidade são mapeados entre si.

💡 Solução: CodeSee Maps — uma ferramenta para desenvolvedores mapearem visualmente sua base de código.

O CodeSee Maps fornece diagramas de código auto-atualizados e gerados automaticamente. Eles sincronizam sua base de código à medida que o código evolui para que você possa identificar rapidamente as dependências entre códigos e navegar entre arquivos e pastas. Ele pode realmente melhorar sua compreensão da base de código e orientar a integração, o planejamento e as revisões. A ferramenta é voltada principalmente para desenvolvedores, mas é de grande valia para quem interage com a equipe.

Para começar a usar o CodeSee Maps, você precisará autorizar o CodeSee em sua conta de usuário do GitHub e, em seguida, instalar e autorizar a ação CodeSee Architecture Diagrams GitHub nos repositórios para os quais você gostaria de criar mapas. No momento, eles oferecem suporte apenas ao GitHub, mas o BitBucket e o GitLab estão no roteiro.

## [DeepSource](https://deepsource.io/)

![image](https://user-images.githubusercontent.com/64677271/214047126-b7cc887e-b9b2-48e6-92ab-fad4f28d94b7.png)

🤕 Dificuldade: revisões de código demoradas, propensas a erros humanos

💡 Solução: DeepSource — plataforma de análise estática rápida e confiável

O DeepSource é um analisador de código estático que pode ajudá-lo a automatizar as revisões de código e economizar muito tempo para sua equipe. Ele pode encontrar problemas na base de código e enviar PRs automaticamente para corrigi-los (e até mesmo avaliar o código recebido nos PRs e corrigi-los também). Os analisadores suportados incluem, entre outros, Docker, Java, JavaScript, Go, Python, Ruby, bem como PHP e SQL atualmente em versão beta. Ele se integra ao GitHub, GitLab e Bitbucket (auto-hospedado também está disponível).

Também existe a possibilidade de implantar no local. Como isso pode melhorar a maneira como sua equipe trabalha? O site deles afirma que o uso da ferramenta pode economizar 3,8 horas em média por desenvolvedor a cada semana, então você faz as contas!

## [Appsmith](https://www.appsmith.com/about-us)

![image](https://user-images.githubusercontent.com/64677271/214047179-9bb6ce79-1496-4350-b28c-faac2277c5f3.png)

🤕 Dor: A necessidade de inúmeras aplicações CRUD dentro de uma organização, que acaba por ser uma tarefa repetitiva e muitas vezes demorada.

💡 Solução: Appsmith — uma estrutura de código aberto para criar ferramentas internas.

Appsmith se descreve como “A ferramenta de interface do usuário para desenvolvedores ocupados” e realmente é isso! É ótimo para equipes que criam muitos aplicativos internos hospedados em sua própria infraestrutura e firewall. Você pode facilmente criar painéis de administração, fluxos de trabalho e painéis de aparência atraente arrastando e soltando widgets personalizáveis pré-fabricados. Você pode integrar com qualquer API REST ou GraphQL e usar JS ou uma biblioteca para criar lógica para seu aplicativo.

## [WayScript](https://wayscript.com/)

![image](https://user-images.githubusercontent.com/64677271/214047224-bda90af6-3726-487c-a2d8-369b8568f448.png)

🤕 Dificuldade: configurar ferramentas e aplicativos internos é demorado e mantém os desenvolvedores longe dos problemas reais que estão tentando resolver.

💡 Solução: WayScript — a maneira mais rápida de transformar seu código local em um aplicativo hospedado.

WayScript é um hub de desenvolvimento para ferramentas internas. Ele fornece contêineres pré-configurados nos quais você pode criar para que o código funcione com a infraestrutura existente de sua equipe. Você pode configurar rapidamente APIs (que tradicionalmente é uma tarefa longa, mas também obrigatória para clientes técnicos), servidores, tarefas cron, inpoints personalizados, interfaces e muito mais. Quando a ferramenta estiver pronta, você pode implantá-la com um clique e enviá-la para sua equipe. Você pode usá-lo baixando o aplicativo local ou por meio do aplicativo da web.
