# CRUD de Farmácia

Esse é um sistema CRUD para farmácias. O projeto permite o gerenciamento de produtos e categorias, facilitando a organização e consulta de informações sobre os produtos disponíveis na farmácia.

## Funcionalidades: 

- Cadastro, consulta, atualização e remoção de produtos.

- Cadastro, consulta, atualização e remoção de categorias.

- Relacionamento entre categorias e produtos.

 ### 🛠️ Construído com:
  
- **Linguagem**: Java  
- **Framework**: Spring Boot  
- **Banco de Dados**: MySQL   
- **IDE utilizada**: Spring Tools Suite (STS)
- **Ferramenta de Testes**: Insomnia

### 🚀 Instalação e execução do projeto

Essas instruções permitirão que você obtenha uma cópia do projeto em operação na sua máquina local para fins de desenvolvimento e teste.


### 📋 Pré-requisitos

Antes de iniciar, certifique-se de ter os seguintes itens instalados:

- [Java 17+](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html)
- [Spring Boot](https://spring.io/projects/spring-boot)
- [MySQL](https://www.mysql.com/downloads/)
- [Insomnia](https://insomnia.rest/) 

### 🔧 Instalação

 1. Clone o repositório:

```bash
git clone https://github.com/larissamata/CRUD-Farmacia.git
```

 2. Acesse a pasta do projeto:

```bash
cd CRUD-Farmacia
```

3. Configure o banco de dados:

```sql
CREATE DATABASE farmacia;
```

 4. Atualize o arquivo 'application.properties' com suas credenciais do MySQL:

```properties
spring.datasource.url=jdbc:mysql://localhost:8080/farmacia
spring.datasource.username=seu_usuario
spring.datasource.password=sua_senha
```

5. Execute o projeto:

```bash
mvn spring-boot:run
```

- Se tudo estiver correto, o servidor Spring Boot será iniciado na porta 8080 (ou outra configurada).

 ### ⚙️ Executando os testes
  
  🔩 **Testes de API**

Você pode testar os endpoints utilizando o Insomnia. Os endpoints são:

### Produto:

- **GET** `/produtos` - Consulta todos os produtos

- **GET** `/produtos/{id}` - Consulta produto por ID

- **GET** `/produtos/nome/{nome}` - Consulta produto por nome

- **POST** `/produtos` - Cria um novo produto

- **PUT** `/produtos/{id}` - Atualiza um produto existente

- **DELETE** `/produtos/{id}` - Deleta um produto


### Categoria:

- **GET** `/categorias` - Consulta todas as categorias
  
- **GET** `/categorias/{id}` - Consulta categoria por ID
  
- **GET** `/categorias/descricao/{descricao}` - Consulta categoria por descrição

- **POST** `/categorias` - Cria uma nova categoria

- **PUT** `/categorias/{id}` - Atualiza uma categoria existente

- **DELETE** `/categorias/{id}` - Deleta uma categoria


## Autora:

💻🌟 Desenvolvido por: Larissa Mata. 


  


   
