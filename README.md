# resumoApiREST
# Api REST e RESTFul
  Uma API de REST é uma API que se adéqua aos princípios de design do REST ou o estilo de arquitetura do Representational State Transfer. Por esta razão, as APIs de REST são muitas vezes chamadas de APIs de RESTful. A arquitetura REST é composta de um conjunto de diretrizes que podem ser implementadas conforme necessário. Isso faz com que as APIs REST sejam mais rápidas, leves e escaláveis, o que é ideal para a Internet das Coisas (IoT) e o desenvolvimento de aplicativos mobile. Junto a isto, as APIs de REST podem ser desenvolvidas usando praticamente qualquer linguagem de programação e oferecem suporte a uma variedade de formatos de dados. O único requisito é que eles devem alinhar aos seis princípios de design de REST a seguir, conhecidos como restrições de arquitetura:
* Interface uniforme;
* Desacoplamento do cliente-servidor;
* estado definido;
* Capacidade de armazenamento em cache;
* Arquitetura de sistema em camadas;
* Código sob demanda (opcional). 

A API RESTful é uma interface que dois sistemas de computador usam para trocar informações de forma segura pela internet. A maioria das aplicações de negócios precisa se comunicar com outras aplicações internas e de terceiros para executar várias tarefas. Por exemplo, para gerar contracheques mensais, seu sistema interno de contas precisa compartilhar dados com o sistema bancário de seu cliente a fim de automatizar o faturamento e se comunicar com uma aplicação interna de planilha de horas. As APIs RESTful suportam essa troca de informações porque seguem padrões de comunicação de software seguros, confiáveis e eficientes.

 ## Diferenças entre REST e RESTFul

 As principais diferenças entre APIs REST e RESTful está no nível de aderência aos princípios REST. Enquanto as APIs REST seguem os princípios básicos do REST, as APIs RESTful são uma implementação mais completa e estrita desses princípios. APIs RESTful aderem a critérios adicionais, como a interface uniforme, clientes sem estado e operações baseadas em recursos.

* REST: conjunto de princípios de arquitetura;
* RESTful: capacidade de determinado sistema aplicar os princípios de REST.

 ## HTTP verbs
O protocolo HTTP define um conjunto de métodos de requisição responsáveis por indicar a ação a ser executada para um dado recurso. Cada um deles 
implementa uma semântica diferente, mas alguns recursos são compartilhados por um grupo deles.

* GET - O método GET solicita a representação de um recurso específico. Requisições utilizando o método GET devem retornar apenas dados.

* HEAD - O método HEAD solicita uma resposta de forma idêntica ao método GET, mas transfere apenas a linha de status e a seção de cabeçalho.

* POST - Uma solicitação POST é usada para enviar dados ao servidor, por exemplo, informações do cliente, upload de arquivos, etc.

* PUT - O método PUT substitui todas as atuais representações do recurso de destino pela carga de dados da requisição.

* DELETE - Remove todas as representações atuais do recurso alvo fornecidas por um URI.

* CONNECT - O método CONNECT estabelece um túnel para o servidor identificado pelo recurso de destino.

* OPTIONS - O método OPTIONS é usado para descrever as opções de comunicação com o recurso de destino.

* TRACE - O método TRACE executa um teste de chamada loop-back junto com o caminho para o recurso de destino.

* PATCH - O método PATCH é utilizado para aplicar modificações parciais em um recurso.


## HTTP Status Code
 Os códigos de status de resposta HTTP indicam se uma solicitação HTTP específica foi concluída com êxito. As respostas são agrupadas 
em cinco classes:

* Respostas Informativas (100 – 199) - Indica que a requisição foi recebida e entendida. Essa resposta é despachada provisoriamente, 
enquanto o processamento da requisição continua. Serve para alertar ao cliente que espere pela resposta final.

* Respostas bem-sucedidas (200 – 299) - Indica que a ação solicitada pelo cliente foi recebida, compreendida, aceita e processada com 
êxito. O resultado de "sucesso" depende do método HTTP:

  GET: O recurso foi buscado e transmitido no corpo da mensagem;  
  HEAD: Os cabeçalhos de representação são incluídos na resposta sem qualquer corpo de mensagem;  
  PUT ou POST: O recurso que descreve o resultado da ação é transmitido no corpo da mensagem;  
  TRACE: O corpo da mensagem contém a mensagem de solicitação recebida pelo servidor.  

* Mensagens de redirecionamento (300 – 399) - O cliente deve tomar medidas adicionais para completar o pedido. Indica que a ação ainda 
precisa ser levada pelo agente de usuário, a fim de atender à solicitação.

* Respostas de erro do cliente (400 – 499) - Classe destinada para os casos em que o cliente parece ter cometido um erro. Exceto quando 
estiver respondendo a uma solicitação HEAD, o servidor deve incluir uma entidade que contém uma explicação sobre a situação de erro; e 
se é uma condição temporária ou permanente. 

* Respostas de erro do servidor (500 – 599) - Indica casos na qual o servidor está ciente do erro e é incapaz de performar a requisição. 
Exceto quando estiver respondendo a uma solicitação HEAD, o servidor deve incluir uma entidade contendo uma explicação sobre a situação 
de erro; e se é uma condição temporária ou permanente.

Autor do resumo: George José - 01430653
