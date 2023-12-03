 # Api REST e RESTFul
 API REST, ou API RESTful, é uma interface de programação de aplicações (API) que segue os princípios da arquitetura REST. REST é um conjunto de restrições e princípios de arquitetura que definem como as APIs devem ser projetadas e implementadas.

As APIs REST são usadas para permitir que dois sistemas de computador se comuniquem entre si. Elas são frequentemente usadas para conectar aplicações web a serviços back-end, mas também podem ser usadas para conectar aplicações móveis, dispositivos IoT e outros tipos de sistemas.

As APIs REST funcionam usando um conjunto de métodos HTTP para representar as operações que podem ser realizadas em um recurso. Os métodos HTTP mais comuns usados em APIs REST são:

GET: Recupera um recurso.
POST: Cria um novo recurso.
PUT: Atualiza um recurso existente.
DELETE: Exclui um recurso.
Por exemplo, uma API REST que fornece informações sobre produtos pode usar os seguintes métodos HTTP:

GET /produtos: Recupera uma lista de todos os produtos.
POST /produtos: Cria um novo produto.
PUT /produtos/id: Atualiza o produto com o ID especificado.
DELETE /produtos/id: Exclui o produto com o ID especificado.
As APIs REST também usam um esquema de URI para identificar os recursos que podem ser acessados. O esquema de URI geralmente consiste em um caminho que identifica o recurso e um conjunto de parâmetros que podem ser usados para filtrar ou restringir os resultados.

As APIs REST oferecem uma série de vantagens, incluindo:

Simplicidade: As APIs REST são relativamente simples de projetar e implementar.
Portabilidade: As APIs REST são independentes de linguagem e plataforma, o que as torna fáceis de usar com qualquer tipo de aplicação.
Escalabilidade: As APIs REST são escaláveis e podem ser facilmente dimensionadas para atender a demandas crescentes.
As APIs REST são uma tecnologia essencial para o desenvolvimento de aplicações web e móveis modernas. Elas permitem que aplicações de diferentes sistemas se comuniquem entre si de forma eficiente e segura.

    ## Diferenças entre REST e RESTFul

    
REST e RESTful são dois termos que são frequentemente usados ​​de forma intercambiável, mas há uma diferença sutil entre os dois. REST é um acrônimo para Representational State Transfer, que é um estilo de arquitetura para sistemas distribuídos. RESTful é um adjetivo que se refere a um sistema que segue os princípios de REST.

Em outras palavras, REST é um conceito geral, enquanto RESTful é uma implementação específica de REST. Uma API RESTful é uma API que segue os princípios de REST, incluindo:

Cliente-servidor: O cliente e o servidor são entidades separadas que interagem entre si.
Estadoless: O servidor não mantém estado do cliente.
Cacheable: O cliente pode armazenar em cache as respostas do servidor para melhorar o desempenho.
Uniform interface: O servidor fornece uma interface uniforme para todos os recursos.
Os métodos HTTP são usados ​​para representar as operações que podem ser realizadas em um recurso. Os métodos HTTP mais comuns usados ​​em APIs RESTful são:

GET: Recupera um recurso.
POST: Cria um novo recurso.
PUT: Atualiza um recurso existente.
DELETE: Exclui um recurso.
As URIs são usadas para identificar os recursos que podem ser acessados. As URIs geralmente consistem em um caminho que identifica o recurso e um conjunto de parâmetros que podem ser usados ​​para filtrar ou restringir os resultados.

As APIs RESTful oferecem uma série de vantagens, incluindo:

Simplicidade: As APIs RESTful são relativamente simples de projetar e implementar.
Portabilidade: As APIs RESTful são independentes de linguagem e plataforma, o que as torna fáceis de usar com qualquer tipo de aplicação.
Escalabilidade: As APIs RESTful são escaláveis e podem ser facilmente dimensionadas para atender a demandas crescentes.

    ## HTTP verbs

HTTP verbs, também conhecidos como métodos HTTP ou métodos de solicitação, são os comandos que os clientes da web usam para interagir com os servidores da web. Eles definem o tipo de operação que o cliente deseja realizar em um recurso. Os verbos HTTP mais comuns são:

GET: Recupera uma representação de um recurso. Este é o verbo HTTP mais comum e é usado para recuperar dados de um servidor.
POST: Envia dados para serem processados ​​em um recurso especificado. Este verbo é usado para criar novos dados em um servidor.
PUT: Atualiza um recurso existente. Este verbo é usado para modificar dados existentes em um servidor.
DELETE: Exclui um recurso existente. Este verbo é usado para remover dados de um servidor.
HEAD: Recupera apenas as informações de cabeçalho de um recurso, sem recuperar o corpo. Este verbo é usado para verificar o status de um recurso ou para obter seus cabeçalhos.
OPTIONS: Obtém as opções HTTP que o servidor suporta para um determinado recurso. Este verbo é usado para verificar quais operações são permitidas em um recurso.
PATCH: Atualiza uma parte específica de um recurso existente. Este verbo é semelhante ao PUT, mas ele só atualiza uma parte específica do recurso, em vez do recurso inteiro.
Os verbos HTTP são sempre enviados como parte de uma mensagem de solicitação HTTP. A mensagem de solicitação também inclui o URL do recurso, os cabeçalhos e um corpo opcional. O servidor responde à mensagem de solicitação com uma mensagem de resposta, que inclui o código de status, os cabeçalhos e um corpo opcional.

Os verbos HTTP são essenciais para a construção de aplicações web. Eles fornecem uma maneira simples e consistente para os clientes interagirem com os servidores.

Em resumo, um verbo HTTP é uma palavra ou frase que indica a ação que um cliente deseja realizar em um recurso. Os verbos HTTP são usados ​​para definir as operações que podem ser realizadas em um recurso, como recuperar, criar, atualizar ou excluir.

Aqui estão alguns exemplos de como os verbos HTTP são usados:

GET /produtos: Recupera uma lista de produtos.
POST /produtos: Cria um novo produto.
PUT /produtos/1: Atualiza o produto com o ID 1.
DELETE /produtos/1: Exclui o produto com o ID 1.
Os verbos HTTP são uma parte fundamental do protocolo HTTP. Eles permitem que os clientes e servidores se comuniquem de forma eficaz e consistente.


    ## HTTP Status Code

    Os códigos de status HTTP são números de três dígitos que indicam o status de uma solicitação HTTP. Eles são usados para comunicar o resultado de uma solicitação entre um cliente e um servidor. O primeiro dígito do código indica a categoria geral da resposta, enquanto os dois dígitos restantes fornecem informações mais específicas sobre o status.

    ---

    Autor do resumo: Gabriela Queiroga - 01569138
