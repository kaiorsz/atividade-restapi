# Pesquisa sobre REST API

## Definição

Uma REST API (Application Programming Interface) é um conjunto de padrões e diretrizes que permite a comunicação entre sistemas de software, como a internet, por exemplo. Ela é baseada nos princípios da arquitetura REST (Representational State Transfer), que define um conjunto de diretrizes para a criação de serviços web escaláveis e flexíveis. As REST APIs permitem que sistemas cliente enviem solicitações a sistemas servidores para acessar, manipular e gerenciar recursos, como dados ou funcionalidades, usando métodos padronizados do protocolo HTTP, incluindo GET, POST, PUT e DELETE. Essa abordagem oferece uma forma eficiente e interoperável de integração entre sistemas distribuídos, facilitando a construção de aplicações modernas e acessíveis pela internet.

## Principais Características

1. **Arquitetura Cliente-Servidor**: As REST APIs seguem o modelo cliente-servidor, onde o cliente envia requisições ao servidor e este fornece as respostas correspondentes.

2. **Estado da Representação (Stateless)**: Cada requisição feita pelo cliente ao servidor contém todas as informações necessárias para ser compreendida e processada pelo servidor. Não há estado armazenado no servidor entre as requisições.

3. **Recursos Identificados**: Os recursos, que podem ser objetos, dados ou serviços, são identificados de forma única por meio de URIs (Uniform Resource Identifiers).

4. **Operações HTTP**: As operações HTTP, como GET, POST, PUT e DELETE, são utilizadas para realizar ações nos recursos identificados. Cada operação tem um significado específico, como obter um recurso (GET), criar um novo recurso (POST), atualizar um recurso existente (PUT) ou excluir um recurso (DELETE).

5. **Representação dos Recursos**: As representações dos recursos, geralmente em formato JSON ou XML, são transferidas entre cliente e servidor. Isso permite que os clientes interpretem e manipulem os recursos de forma independente da sua implementação no servidor.

6. **Interoperabilidade**: As REST APIs são projetadas para serem independentes de linguagem de programação e plataforma, o que facilita a interoperabilidade entre diferentes sistemas e tecnologias.

Essas características tornam as REST APIs uma escolha popular para o desenvolvimento de serviços web que necessitam de uma comunicação eficiente e flexível entre sistemas distribuídos.
