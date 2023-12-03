# RestAPI

 # Api REST e RESTFul

   Uma API, ou interface de programação aplicativos, é um conjunto de regras que definem como aplicativos ou dispositivos podem se conectar e se comunicar uns com os outros.
    
   API REST é uma interface de programação de aplicações (API ou API web) em conformidade com as restrições do estilo de arquitetura REST, permitindo a interação com serviços web RESTFul. REST é a sigla em inglês para "Representational State Transfer", tansferência de estado representacional. Essa arquitetura foi criada pelo cientista da computação Roy Fielding.
    
   A API RESTFul é uma interface que dois sistemas de computador usam para trocar informações de forma segura pela internet. A maioria das aplicações de negócios precisa se comunicar com outras aplicações internas e de terceiros para executar várias tarefas. As APIs RESTFul suportam essa troca de informações porque seguem padrões de comunicação de software seguros, confiáveis e eficientes.

  ## Diferenças entre REST e RESTFul

   Os serviços da Web que implementam a arquitetura REST são chamados de serviços da Web RESTful. O termo API RESTFul geralmente se refere a APIs da Web RESTful. No entanto, você pode usar os termos API REST e API RESTFul de forma intercambiável, apesar da diferença sutil; Todas as API RESTFul são API REST, mas nem todas as API REST podem ser consideradas RESTFul pois as API REST podem não seguir de forma rigorosa todos os princípios da arquitetura REST.

  ## HTTP verbs
   O protocolo HTTP define um conjunto de métodos de requisição responsáveis por indicar a ação a ser executada para um dado recurso. Embora esses métodos possam ser descritos como substantivos, eles também são comumente referenciados como HTTP Verbs. Cada um deles implementa uma semântica diferente, mas alguns recursos são compartilhados por um grupo deles.

   * GET   
   O método GET solicita a representação de um recurso específico. Requisições utilizando o método GET devem retornar apenas dados.

   * HEAD   
   O método HEAD solicita uma resposta de forma idêntica ao método GET, porém sem conter o corpo da resposta.

   * OPTIONS  
   O método OPTIONS é usado para descrever as opções de comunicação com o recurso de destino.

   * POST   
   O método POST é utilizado para submeter uma entidade a um recurso específico, frequentemente causando uma mudança no estado do recurso ou efeitos colaterais no servidor.

   * PUT    
   O método PUT substitui todas as atuais representações do recurso de destino pela carga de dados da requisição.

   * DELETE   
   O método DELETE remove um recurso específico.

   * TRACE   
   O método TRACE executa um teste de chamada loop-back junto com o caminho para o recurso de destino.

   * CONNECT    
   O método CONNECT estabelece um túnel para o servidor identificado pelo recurso de destino.

   * PATCH  
   O método PATCH é utilizado para aplicar modificações parciais em um recurso.

  ## HTTP Status Code

   Os códigos de status de resposta HTTP indicam se uma solicitação HTTP específica foi concluída com êxito. As respostas são agrupadas em cinco classes:

   Respostas Informativas (100 – 199) - Indica que a requisição foi recebida e entendida. Essa resposta é despachada provisoriamente, enquanto o processamento da requisição continua. Serve para alertar ao cliente que espere pela resposta final.
    
   Respostas bem-sucedidas (200 – 299) - Indica que a ação solicitada pelo cliente foi recebida, compreendida, aceita e processada com êxito.
    
   Mensagens de redirecionamento (300 – 399) - O cliente deve tomar medidas adicionais para completar o pedido. Indica que a ação ainda precisa ser levada pelo agente de usuário, a fim de atender à solicitação.
    
   Respostas de erro do cliente (400 – 499) - Classe destinada para os casos em que o cliente parece ter cometido um erro. Exceto quando estiver respondendo a uma solicitação HEAD, o servidor deve incluir uma entidade contendo uma explicação sobre a situação errática; e se é uma condição temporária ou permanente. 
    
   Respostas de erro do servidor (500 – 599) - Indica casos na qual o servidor está ciente do erro e é incapaz de performar a requisição. Exceto quando estiver respondendo a uma solicitação HEAD, o servidor deve incluir uma entidade contendo uma explicação sobre a situação de erro; e se é uma condição temporária ou permanente.

    
  
  ##### Autor do resumo: Pedro Augusto Cardoso Silva - 01403875
