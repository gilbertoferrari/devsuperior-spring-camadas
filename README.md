# DevSuperior Spring camadas. 

Projeto Springboot que aplica as responsabilidades de uma API REST. 

## Responsabilidades. 
Devemos separar as responsabilidades na elaboração do projeto. 
### Controller. 
Responder as interações do usuario. 
> No caso de uma API REST, essas interações são as requisições. 
### Service. 
Realizar operações de negócios. 
> Um metodo de camada service deve ter um significado relacionado ao negócio.
> podendo executar várias operações.
> Exemplo: registrarPedido[verificar estoque, salvar pedido, baixar estoque, enviar email]. 
### Repository. 
Realizar operações individuais de acesso ao banco de dados. 

