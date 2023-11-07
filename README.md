# Spring API Gateway

[Documentação do spring-cloud-gateway](https://spring.io/projects/spring-cloud-gateway)

O que e um API Gateway ?

Um API Gateway é um componente fundamental em arquiteturas de 
microsserviços e sistemas distribuídos. Ele atua como um 
intermediário entre clientes (como aplicativos da web, 
aplicativos móveis ou sistemas de terceiros)

1. Roteamento de solicitações: Um API Gateway roteia as solicitações dos clientes para os serviços de backend apropriados. Ele pode fazer isso com base em várias regras, como caminhos de URL, cabeçalhos, métodos HTTP e muito mais. Isso simplifica a comunicação com os serviços subjacentes, pois os clientes não precisam conhecer a topologia da infraestrutura de serviço.
2. Agregação de serviços: Um API Gateway pode combinar várias chamadas de serviços em uma única solicitação para o cliente. Isso é útil quando um cliente precisa de informações de múltiplos serviços para renderizar uma página ou responder a uma solicitação.
3. Balanceamento de carga: O API Gateway pode distribuir o tráfego entre várias instâncias de um serviço de backend para melhorar a escalabilidade e a confiabilidade. Isso ajuda a evitar a sobrecarga de um único serviço.
4. Autenticação e autorização: O API Gateway pode lidar com autenticação e autorização em nome dos serviços de backend. Isso permite a implementação de políticas de segurança consistentes em toda a aplicação e facilita a validação de tokens, autenticação de usuários e controle de acesso.
5. Caching: Um API Gateway pode armazenar em cache respostas de serviços de backend para reduzir a carga dos serviços e melhorar o desempenho. Isso é útil para dados que não mudam com frequência.
6. Monitoramento e análise: O API Gateway pode coletar métricas e logs sobre o tráfego de API, permitindo o monitoramento em tempo real e a análise de desempenho, uso e erros.
7. Transformação de dados: Um API Gateway pode transformar as respostas dos serviços de backend para um formato adequado para o cliente. Isso permite que os clientes recebam dados formatados de maneira consistente, independentemente do serviço subjacente.
8. Proteção contra ataques: O API Gateway pode fornecer camadas adicionais de segurança, como prevenção de ataques DDoS, rate limiting (limitação de taxa) e filtragem de solicitações maliciosas.
9. Gerenciamento de versões: O API Gateway pode ajudar a gerenciar a evolução das APIs, permitindo que os clientes acessem versões específicas dos serviços de backend.

Para fazer a chamada de teste basta fazer:

```shell
curl http://localhost:8080/cep/88048565
```