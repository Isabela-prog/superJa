## API sistema de delivery de Super mercado


Nessa aplicação teremos um sistema completo de cadastro,ataulização,\
deleção e busca de todos os produtos, por meio do id e pelo nomeDoProduto (método específico escolhido).\
Bem como, para categoria (método específico será buscar por setor) e usuário (não terá um método específico de busca).\
Nesse projeto, na classe service de Produto, temos a regra de negócio de que se o prduto for maior do que 50.00, 
será aplicado um desconto de 10%. Já na classe Service de Usuario teremos toda a autenticação do Spring Security.\
Ao final da criação, criamos um Swagger e subimos a API para um servidor do Render.

## Etapas: 
- [x] Package model (contém as classes que representam as entidades do banco de dados)
- [x] Fazer modificações no arquivo application.properties - criar bd
- [x] Criar classe Produto, Usuário e Categoria, UsuarioLogin
- [x] Atributos Usuário (id, nome, senha, usuario, foto)
- [x] Atributos Produto (id, nomeDoProduto, estoque, preco, validade)
- [x] Atributos Categoria (id, setor)
- [x] Usuário Login - mesmos atributos de usuário, porém com o Token (essa classe é necessária para o processo de autenticação)
- [x] Package repository (classses responsáveis pela persistência de dados usando Spring Data JPA)
- [x] Criar classe UsuarioRepository 
- [x] Criar classe ProdutoRepository - buscar por nomeDoProduto
- [x] Criar classe CategoriaRepository - buscar por setor
- [x] Package controller (classes responsáveis por expor as funcionalidades como endpoints REST)
- [x] Criar classe UsuarioController
- [x] Criar métodos (cadastrar, atualizar, consultar todos, consultar por id e logar)
- [x] Criar classe CategoriaController
- [x] Criar métodos (cadastrar, atualizar, excluir, consultar todos, consultar por id e consultar por setor)
- [x] Criar classe ProdutoController
- [x] Criar métodos (cadastrar, atualizar, excluir, consultar todos, consultar por id e consultar por nomeDoProduto)
- [x] Criar relacionamento entre classes - Produto se relaciona tanto com Categoria, como com Usuario
- [x] Fazer modificações no pom.xml - Dependências do Spring Security
- [x] Package Service
- [x] Criar classe ProdutoService - método específico desconto para produtos acima de 50.00
- [x] Criar classe UsuarioSercie - processo de autenticação do Usuário através do Spring Security
- [x] Testar métodos através do Insomnia
- [x] Fazer modificações no arquivo application.properties - adc application-dev.properties 
- [x] Fazer modificações no pom.xml - Dependências do Swagger
- [x] Criar SwaggerConfig
- [x] Criar Dockerfile
- [x] Testar o Swagger
- [x] Fazer modificações no pom.xml - Dependências do postgreSql
- [x] Criar bd no Render
- [x] Conectar bd com repositório do github
- [x] Fazer o Deploy

</br>

> A parte mais desafiadora do projeto foi fazer o Deploy no Render.  

</br></br> Esse projeto foi realizado por **Isabela Santos, Abiqueila, Evelyn Santos, Thainara Cruz, Hellen Gleice e Mayte**, no Cruso Java Fullstack Brasil 
com intuito de aplicar conhecimentos adquiridos ao longo das aulas.
